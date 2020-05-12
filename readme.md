# flows

Barebones realtime graph greator.

Leverages [GraphViz](https://graphs.grevian.org/) to turn basic `DOT` code into
pretty flowcharts:

```
digraph {
  A -> B;
  B -> C;
  A -> C;
}
```

## run

Serve up a localhost server and you're up and running:

```
cd ~/src/flows && python -m http.server
```

## todo

- Add download and import functions
- Make UI reactive
- Clean up interface

## credit

Flows is, at the moment, just a re-skin of the creator of the underlying
dagre-d3.js's [interactive
demo](https://dagrejs.github.io/project/dagre-d3/latest/demo/interactive-demo.html).
