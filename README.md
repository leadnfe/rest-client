# @leadnfe/rest-client

> LeadNFe REST API Client

## Instalação

```
npm install @leadnfe/rest-client --save
```

## Exemplo

```js
const rest = require('@leadnfe/rest-client');
const restClient = rest('https://api.leadnfe.com/')
app.configure(restClient.fetch(window.fetch));
const messages = app.service('messages');
```

## Documentação

Por favor utilize a documentação oficial [@leadnfe/rest-client documentation](https://api.leadnfe.com/docs/client/rest.html) para mais detalhes.

## License

Copyright (c) 2018

Licensed under the [MIT license](LICENSE).
