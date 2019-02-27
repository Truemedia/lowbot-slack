# Mind Stack slack
Slack adapter for Mind Stack

## This is a work in progress

## Installation

NPM
```bash
    npm i --save mindstack-slack
```

Yarn
```bash
    yarn add mindstack-slack
```

## Usage
Node
```js
    const Bot = require('mindstack');
    const slack = require('mindstack-slack');

    let botInstance = new Bot()
      .useAdapter(slack);
```
