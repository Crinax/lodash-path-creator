# lodash-path-creator

Simple, smallest and zero-dep library for node.js :D

## Knock-knock, I'm here

Why simple? Just look at this:

```javascript
const lpc = new require('lodash-path-creator')();

console.log(lpc.one.two.three.four.five.$);
// Output: 'one.two.three.four.five'
```

## API

`constructor(stopWord: string = '$')` - constructor with unnecessary stopWord (default `$`)

I think, that's all...
Hope you enjoy :D