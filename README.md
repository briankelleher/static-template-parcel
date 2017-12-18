# Loki Starter

This is a static HTML template hooked up with build tools using Parcel as an application bundler (instead of webpack).  Much simpler.

## Requirements

* Node v8+
* Yarn

## Installation

Switch to node 8.  If you are using NVM, you can do this:

```bash
# With node 8 already installed:
nvm use 8

# If you do not have node 8 already installed:
nvm install 8
```

Next, install dependencies:

```
yarn global add parcel-bundler
yarn install
```

Lastly, start the server:

```
npm run server
```

Then open your browser at http://localhost:1234

## Building for Production

```
npm run build
```

Should build a production ready verison of the site in the dist/ folder.

## Questions

Submit Bug Request.