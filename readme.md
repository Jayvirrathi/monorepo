# A Monorepo with Lerna - Node.js & React.js .

> A Full Stack Project - Node.js & React.js

## Prerequisites

-   Nodejs
-   lerna (globally)

## Build Setup

```bash
# install dependencies
npx lerna bootstrap --hoist

# serve with hot reload at localhost:3000 & localhost:5000
npm start
```

## Clean Dependencies

```bash
npx lerna clean -y
```

## other commands

```bash
lerna run test --scope=web

lerna run test --scope={web,}
```
