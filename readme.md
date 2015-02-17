# wifi-password [![Build Status](http://img.shields.io/travis/kevva/wifi-password.svg?style=flat)](https://travis-ci.org/kevva/wifi-password)

> Get current wifi password


## Install

```
$ npm install --save wifi-password
```


## Usage

```js
var wifiPassword = require('wifi-password');

wifiPassword(function (err, password) {
	console.log(password);
	//=> johndoesecretpassword
});
```


## API

### wifiPassword([name], cb)

#### name

Type: `string`

Get the wifi password for a specified *known* network.

#### cb(err, password)

Type: `function`

The callback will return the password to the network.


## CLI

```
$ npm install --global wifi-password
```

```
$ wifi-password --help

Usage
  $ wifi-password
  johndoesecretpassword
```


## License

MIT © [Kevin Mårtensson](https://github.com/kevva)
