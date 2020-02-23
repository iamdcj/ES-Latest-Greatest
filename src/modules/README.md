# Modules

A JavaScript module is a chunk of JS code living in its own file, containing various bindings, e.g. functions and regular variable declarations, with some or all `export`ed for use across the various parts of the application via an `import`.

##### a-module.js

```
const userName = "David";

const logUserHelper = () => {
  console.log(userName);
}

export { logUserHelper };

```

## **Benefits**

- Modules allow for a cleaner, better-structured codebase.

## Named Exports vs. Default

## **Modules Background**

Modular javaScript isn't anything new in JS applications, however prior to ES2015 there wasn't native support for modules; developers had to code modules themselves, or use a third-party library to provide javaScript modules.

### Module Pattern

### NPM

Node Package Manager is the defacto package manager for JavaScript; it runs on node and contains a database of javaScript packages available for download and utilisation within applications.

The packages we download are essentially contain a bunch of exported modules.
