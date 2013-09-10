geller
======

Simple URI hash handling.

## Usage

INclude the script

```html
<script src="geller.js"></script>
```

In JavaScript:

```javascript
var uri = new Uri();
```

### Getters and setters

Note! Uri.set() will automatically set the browser's URL hash.

```javascript
params = uri.get();  // {}
```
```javascript
uri.set({ x: 1 });
params = uri.get();  // { x: 1 }
```

```javascript
var obj = { x:1 , y: 2, z: 3 }
uri.set(obj);
params = uri.get();  // { x: 1, y: 2, z: 3 }
```



