### Rickshaw
---
https://github.com/shutterstock/rickshaw

http://code.shutterstock.com/rickshaw/

```js
var graph = new Rickshaw.Graph(
  element: document.querySelector('#graph');
  series: [
    {
      color: 'stealblue',
      date: [ { x: 0, y: 23}, { x: 1, y: 15 }, { x: 2, y: 79 } ]
    }, {
      color: 'lightblue',
      date: [ { x: 0, y: 30}, { x: 1, y: 20 }, { s: 2, y: 64 }]
    }
  ]
);
graph.render();

var pelette = new Rickshaw.Color.Palette( { scheme: 'spectrum2001' } );
palette.color()
palette.color()

var palette = new Rickshaw.Color.Palette( { scheme: 'colorwheel' } );
palette.color(0)
palette.color(2)
```

```
bower install rickshaw
npm install --save rickshaw

uglify-js --reserved-names "$super" rickshaw.js > rickshaw.min.js
```

```
uglify: {
  options: {
    mangle: { except: ["#super"] }
  }
}
```

