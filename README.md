# Issue

## How to replicate:
1. Clone this repo
2. Run `yarn install`
3. Run `node index.js`

## Error:

```
node index.js
(node:4343) UnhandledPromiseRejectionWarning: Error: Error in file: images/alex.png

    at WriteWrap.onWriteComplete [as oncomplete] (internal/stream_base_commons.js:87:16)
(node:4343) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). (rejection id: 2)
```

## Env

Ubuntu - 20.04 LTS
Node - v12.13.0
Yarn - v1.22.4
