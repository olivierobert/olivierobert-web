<p align="center">
   Codebase for <a href="https://olivierobert.com">olivierobert.com</a>
</p>

---

## Get Started

### Prerequisites

- [GCC](https://gcc.gnu.org/install/)
- [Make](https://www.gnu.org/software/make/)
- [Ruby](https://www.ruby-lang.org/en/downloads/) ![ruby-version-image](https://img.shields.io/badge/ruby-3.2.2-brightgreen.svg) 
- [Node](https://nodejs.org) ![node-version-image](https://img.shields.io/badge/node-18.12.1-brightgreen.svg)
- [Yarn](https://yarnpkg.com)

### Install

```sh
cd olivierobert-web
bundle install && yarn install
```
> Learn more: [Bridgetown Getting Started Documentation](https://www.bridgetownrb.com/docs/).

## Development

To start the site in development mode, run `bin/bridgetown start` and navigate to [localhost:4000](https://localhost:4000/).

To load the site up within a Ruby console (IRB), run `bin/bridgetown console`.

## Deployment

To build and deploy the site, run `bin/bridgetown deploy`.

Bridgetown sites can be deployed to hosts like Render, Vercel, and traditional web servers by building and copying the output folder to the HTML root.

> Learn more: [Bridgetown Deployment Documentation](https://www.bridgetownrb.com/docs/deployment) for more information.
