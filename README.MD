# SanCamel

[![Maintainability](https://api.codeclimate.com/v1/badges/3db9af5a76aa62568f0f/maintainability)](https://codeclimate.com/github/reiosantos/ng-san-stepper/maintainability)
[![Build Status](https://travis-ci.com/reiosantos/ng-san-stepper.svg?branch=master)](https://travis-ci.com/reiosantos/ng-san-stepper)
[![Test Coverage](https://api.codeclimate.com/v1/badges/3db9af5a76aa62568f0f/test_coverage)](https://codeclimate.com/github/reiosantos/ng-san-stepper/test_coverage)


Module to transform all sorts of values to camel case

# USAGE
## Installation in package.json

```bash
npm i -S san-camel
```

### Example with Objects

```js
import {SanToCamelCase} from "san-camel/dist";

const testObject = { "my-name": "some name", "another-name": "guess it" }
const formattedValue = SanToCamelCase(testObject);

// output: { myName: "someName", anotherName: "guess it" }

```

### Example with Strings

```js
import {SanToCamelCase} from "san-camel/dist";

const testObject = "test-the-string-dude";
const formattedValue = SanToCamelCase(testObject);

// output: testTheStringDude

```

### Example with Arrays of objects

```js
import {SanToCamelCase} from "san-camel/dist";

const testObject = [{"this is bad": "is it", }, {"this dude": "is it working"}];
const formattedValue = SanToCamelCase(testObject);

// output: [ { thisIsBad: 'is it' }, { thisDude: 'is it working' } ]

```

## Remarks

- Thanks to all ;)
