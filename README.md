# moeda
[![Build Status](https://travis-ci.org/thompsonemerson/moeda.svg?branch=master)](https://travis-ci.org/thompsonemerson/moeda)
[![GitHub version](https://badge.fury.io/gh/thompsonemerson%2Fmoeda.svg)](https://badge.fury.io/gh/thompsonemerson%2Fmoeda)
[![npm version](https://badge.fury.io/js/moeda.svg)](http://badge.fury.io/js/moeda)
> A foreign exchange rates and currency conversion using cli


<p align="center">
  <img src="demo.gif" alt="demo gif">
</p>


#### Info
The `moeda` use JSON API [Fixer.io](http://fixer.io/) for current and historical foreign exchange rates published by the European Central Bank.
The rates are updated daily around 4PM CET.


#### Install
```
$ npm install -g moeda
```

#### CLI
```
Usage
  $ moeda <amount> <currency> [<...currencies>]

Some currency
  [ usd, eur, gbp, brl... ]

Examples
  $ moeda 1 usd

Result
             Euro: 0.92
  Libra Esterlina: 0.82
   Real Brazilian: 3.15

  Conversion of USD 1

Your own currencies to convert

  $ moeda 1 usd eur rub aud

Result

             Euro: 0.91
   Russian Rouble: 62.92
Australian Dollar: 1.30

  Conversion of USD 1
```


### Contributing
Help improve these docs. Open an [issue](https://github.com/thompsonemerson/moeda/issues/new) or submit a pull request.

1. Navigate to the main page of the repository
1. [Fork it!](https://github.com/thompsonemerson/moeda#fork-destination-box)
1. Create your feature branch: `git checkout -b my-new-feature`
1. Commit your changes: `git commit -m 'Add some feature'`
1. Push to the branch: `git push origin my-new-feature`
1. Submit a pull request =D


### History
See [Releases](https://github.com/thompsonemerson/moeda/releases) for detailed changelog.


### License
[MIT License](http://thompsonemerson.mit-license.org/) © Emerson Thompson
