# @leadnfe/rest-client

> REST client services for different Ajax libraries

## Installation

```
npm install @leadnfe/rest-client --save
```

## Quick example

```js
const rest = require('@leadnfe/rest-client');

const app = feathers();
const restClient = rest('https://api.leadnfe.com/')
app.configure(restClient.fetch(window.fetch));
const messages = app.service('messages');
```

## Documentation

Please refer to the [@leadnfe/rest-client documentation](https://api.leadnfe.com/docs/client/rest.html) for more details.

## License

Copyright (c) 2018

Licensed under the [MIT license](LICENSE).
