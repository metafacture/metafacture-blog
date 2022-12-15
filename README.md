# Metafacture Blog

This project is the source for the [metafacture blog](https://blog.metafacture.org/).

This project was created with the gatsby template [gatsby-starter-blog](https://github.com/gatsbyjs/gatsby-starter-blog).

## Installation

Gatsby is build with Node.js.

### Install Node.js

#### Windows

Download and install the latest Node.js version from [the official Node.js website]( https://nodejs.org/en/).

#### Unix

[Install the lastest nvm version](https://github.com/nvm-sh/nvm#installing-and-updating).

Set default Node.js version. When nvm is installed, it does not default to a particular node version. You’ll need to install the version you want and give nvm instructions to use it.
See [here](https://github.com/nvm-sh/nvm#bash) to automatically switch to the correct node version (not necessary, but handy).

```
nvm install 18
nvm use 18
```

### Install gatsby

```
npm install -g gatsby-cli
```


## Start developing

The site runs with:

```
cd metafacture-blog
npm install # if you experience strange ERESOLVE dependecy errors, try "npm install --legacy-peer-deps gatsby"
gatsby develop
```

The site is now running at `http://localhost:8000`!

## Build

To create a production build and output the built static files into the public directory, run:

```
cd metafacture-blog
gatsby build
```

If you want to view the production build locally, run:

```
gatsby serve
```

Once this starts, you can view your site at http://localhost:9000.
