# Lowbot slack
Slack adapter for lowbot

## This is a work in progress

## Installation

NPM
```bash
    npm i --save lowbot-slack
```

Yarn
```bash
    yarn add lowbot-slack
```

## Usage
Node
```js
    const LowBot = require('lowbot');
    const slack = require('lowbot-slack');

    let botInstance = new LowBot()
      .useAdapter(slack);
```
