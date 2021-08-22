# magento2-api

[![Version](https://status.david-dm.org/gh/brunocordioli072/magento2-api.svg)](https://david-dm.org/brunocordioli072/magento2-api)

> A Node.JS module, which provides an object oriented wrapper for the Magento v2 Rest API.

















## :cloud: Installation

```sh
# Using npm
npm install --save magento2-api

# Using yarn
yarn add magento2-api
```













## :clipboard: Example



```js
const {Magento2Client} = require('magento2-rest-client');

const options = {
  url: 'http://www.test.com/index.php/rest',
  consumerKey: '<OAuth 1.0a consumer key>',
  consumerSecret: '<OAuth 1.0a consumer secret>',
  accessToken: '<OAuth 1.0a access token>',
  accessTokenSecret: '<OAuth 1.0a access token secret>',
};
const client = Magento2Client(options);

const stores = await client.stores.list();
```















## :scroll: License

[MIT][license] © [Bruno Cordioli][website]






[license]: /LICENSE
[website]: https://www.linkedin.com/in/bruno-cordioli-machado-4b2a47180/
