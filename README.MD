# SanCamel

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
