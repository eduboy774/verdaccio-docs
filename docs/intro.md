---
sidebar_position: 1
---

# Verdaccio

Let's discover **Verdaccio in less than 5 minutes**.

## Getting Started

Get started by  **briefy introduction**.

Or **try Verdaccio immediately** with **[verdaccio.com](https://verdaccio.org/)**.

### What you'll need

- [Node.js](https://nodejs.org/en/download/) version > 12 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.


## Introduction

**Verdaccio** is a lightweight private npm proxy registry built in Node.js

Using a private npm registry like Verdaccio is one of the Top 10 NPM Security Best Practices recommended by the Open Web Application Security Project (OWASP).

### What is Registry
- A registry is a repository for packages, that implements the CommonJS Compliant Package Registry specification for reading package's   information.
- Provide a compatible API with npm clients (yarn/npm/pnpm).
- Semantic Versioning compatible (semver).


### Installing CLI Command

- Before using Verdaccio in production, please read and be [ aware of the best practices ](https://verdaccio.org/docs/best/).

- Verdaccio must be installed globally using either of the following methods:

- You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

#### Using `npm` 
```
npm install --location=global verdaccio
```


#### or Using `yarn`

```
yarn global add verdaccio
```

#### or Using `pnpm`

```bash
pnpm install -g verdaccio
```

#### or With `docker image`
```bash
docker pull verdaccio/verdaccio:nightly-master
```
## Check Installed Verdaccio
```bash
> verdaccio
```
#### Result
(node:20650) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
(Use `node --trace-deprecation ...` to show where the warning was created)
- info --- config file  - /Users/eduboy/.config/verdaccio/config.yaml
- info --- the "crypt" algorithm is deprecated consider switch to "bcrypt" in the configuration file. Read the documentation for additional details
 - info --- using htpasswd file: /Users/eduboy/.config/verdaccio/htpasswd
 - info --- plugin successfully loaded: verdaccio-htpasswd
 - info --- plugin successfully loaded: verdaccio-audit
 - warn --- http address - http://localhost:4873/ - verdaccio/5.27.0