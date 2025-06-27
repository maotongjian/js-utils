# function-utils

A tiny utility library for `debounce` and `throttle` in JavaScript.

## Installation

```bash
npm install function-utils
```

## Usage

```js
import { debounce, throttleTime } from 'function-utils';

const log = debounce(() => console.log('debounced!'), 500);

const throttled = throttleTime(() => console.log('throttled!'), 1000);
```

## Functions

- `debounce(fn, delay)`
- `debounceImmediate(fn, delay, immediate)`
- `throttleFlag(fn, delay)`
- `throttleTime(fn, delay)`

## License

MIT
