
# N-API Hello

This is a very simple module written in C++ using N-API addon for Node.js.

## Install and run

```javascript
npm install
npm start
```

## Considerations

From [official documentation](https://nodejs.org/api/n-api.html#n_api_n_api):

> _N-API (pronounced N as in the letter, followed by API) is an API for building native Addons. It is independent from the underlying JavaScript runtime (ex V8) and is maintained as part of Node.js itself. This API will be Application Binary Interface (ABI) stable across versions of Node.js. It is intended to insulate Addons from changes in the underlying JavaScript engine and allow modules compiled for one version to run on later versions of Node.js without recompilation._

This project was based on [Node Add-on Examples repo](https://github.com/nodejs/abi-stable-node-addon-examples).
