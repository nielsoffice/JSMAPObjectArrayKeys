# JSMAPObjectArrayKeys 
JavaScript this is really amazing to know that we can assigned a key in arrays of data in object

```JS
// new Map();
// JSArrayWithKeys_Object
const keys = new Map();

// Set keys and Value
keys.set('key1',[1,2,3]);
keys.set('key2','k2 is string! ');

console.log(keys);

// Get keys and Value
keys.get('key');

console.log(keys.get('key2'));

```

```JS
 // Console.log() | result 
 Map(2) {'key1' => Array(3), 'key2' => 'k2 is string! '}
 [[Entries]]
  0: {"key1" => Array(3)}
  1: {"key2" => "k2 is string! "}
  size: 2
 [[Prototype]]: Map
 k2 is string! 
```
