# JSMAPObjectArrayKeys 
JavaScript this is really amazing to know that we can assigned a key in arrays of data in object.
<br />You can also convert object to Map;
<br />const objData = { ... }
<br />const mapJS = new Map(objData);
<br />
<br />console.log(mapJS);
<br />....

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

```JS
// Demo 2
const datas = new Map([
  ['one-key','This is one value'],
  ['two-key','This is two value'],
  ['three-key','This is three value'],
  ['four-key','This is four value'],
  ['five-key','This is five value'],

]);

console.log(datas);
```

```JS
// Console.log() | Result 
Map(5) { 'one-key'   => 'This is one value',   'two-key'  => 'This is two value', 
         'three-key' => 'This is three value', 'four-key' => 'This is four value', 
         'five-key' => 'This is five value'}
[[Entries]]
  0 : {"one-key" => "This is one value"}
  1 : {"two-key" => "This is two value"}
  2 : {"three-key" => "This is three value"}
  3 : {"four-key" => "This is four value"}
  4 : {"five-key" => "This is five value"}
 size : 5
[[Prototype]] : Map
```

```JS
// Get the values of new MAP([ .... ])
console.log(datas.values());

// Get the keys of new MAP([ .... ])
console.log(datas.keys());
```
