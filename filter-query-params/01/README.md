this iteration prettier formats the js

---

this iteration converts the code to [ES2015](https://babeljs.io/learn-es2015/) in something like the [airbnb style](https://github.com/airbnb/javascript)

forked from [@alexmacy](https://twitter.com/alexmacy)'s block: [Updated Crossfilter.js demo](https://bl.ocks.org/alexmacy/ebe599703421757852d36bcf71174dfc)

see also an [earlier iteration](https://bl.ocks.org/micahstubbs/6eab2af6785d9e01589f714131640f40) that retains the plot width and table width of the original Crossfilter example at [http://square.github.io/crossfilter/](http://square.github.io/crossfilter/)

[commit history](https://github.com/micahstubbs/crossfilter-experiments/commits/master)

---

This is an updated version of [this demo](http://crossfilter.github.io/crossfilter/) of the crossfilter library. Crossfilter has been one of my favorite - and what I think to be on of the most underrated - JavaScript libraries. It hasn't seen much of any updates in quite a while, so I wanted to find out how it would work with version 4 of d3.js.

There were some issues that came up with how d3-brush has been [updated for v4](https://github.com/d3/d3/blob/master/CHANGES.md#brushes-d3-brush). Big thanks goes to Alastair Dant ([@ajdant](https://twitter.com/ajdant)) for helping to figure out a couple of those issues!

Also worth reading, is [this discussion](https://github.com/plotly/plotly.js/issues/1316) started by
Robert Monfera ([@monfera](https://twitter.com/monfera)).
