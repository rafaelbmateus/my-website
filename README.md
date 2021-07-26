# Website

This website is built using [Docusaurus 2](https://docusaurus.io/),
a modern static website generator.

![Screenshot (2)](https://user-images.githubusercontent.com/8009492/127031430-e1622a86-240c-456e-92c1-c101fed6d240.png)

## Installation

```console
make install
```

## Local Development

```console
make start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```console
make build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

```console
make deploy user=<Your GitHub username>
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
