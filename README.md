# Stripe Node.js Express Payment Gateway Implementation

[![Version](https://img.shields.io/npm/v/stripe.svg)](https://www.npmjs.org/package/stripe)
[![Build Status](https://travis-ci.org/stripe/stripe-node.svg?branch=master)](https://travis-ci.org/stripe/stripe-node)
[![Coverage Status](https://coveralls.io/repos/github/stripe/stripe-node/badge.svg)](https://coveralls.io/github/stripe/stripe-node)
[![Downloads](https://img.shields.io/npm/dm/stripe.svg)](https://www.npmjs.com/package/stripe)
[![Try on RunKit](https://badge.runkitcdn.com/stripe.svg)](https://runkit.com/npm/stripe)

The Stripe Node library provides convenient access to the Stripe API from
applications written in server-side JavaScript.

Please keep in mind that this package is for use with server-side Node that
uses Stripe secret keys. To maintain PCI compliance, tokenization of credit
card information should always be done with [Stripe.js][stripe-js] on the
client side. This package should not be used for that purpose.

## Documentation

See the [`stripe-node` API docs](https://stripe.com/docs/api/node#intro) for Node.js.

## Installation

Install the packages with:

```sh
npm install
```

## Usage

The package needs to be configured with your account's secret key which is
available in your [Stripe Dashboard][api-keys]. Require it with the key's
value:

```js
const stripe = require('stripe')('sk_test_...');
```

## RUN

The application run with given cmd:

```sh
node app.js
```
