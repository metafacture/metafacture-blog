# Metafacture Blog

This project is the source for the new metafacture blog.
This project was created with the gatsby template [gatsby-starter-blog](https://github.com/gatsbyjs/gatsby-starter-blog).

## Installation

Gatsby is build with Node.js.

### Install Node.js

#### Windows

Download and install the latest Node.js version from [the official Node.js website]( https://nodejs.org/en/).

#### Unix

Download the lastest nvm version.
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.1/install.sh | bash
```

Set default Node.js version. When nvm is installed, it does not default to a particular node version. You’ll need to install the version you want and give nvm instructions to use it. This example uses the version 10 release, but more recent version numbers can be used instead.

```
nvm install 10
nvm use 10
```

### Install gatsby

```
npm install -g gatsby-cli
```

npm install

## Start developing

The site runs with:

```
cd metafacture-blog
npm install
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
