this iteration converts the code to [ES2015](https://babeljs.io/learn-es2015/) in something like the [airbnb style](https://github.com/airbnb/javascript) 

forked from [@alexmacy](https://twitter.com/alexmacy)'s block: [Updated Crossfilter.js demo](https://bl.ocks.org/alexmacy/ebe599703421757852d36bcf71174dfc) 

this iteration retains the plot width and table width of the original Crossfilter example at [http://square.github.io/crossfilter/](http://square.github.io/crossfilter/)

see also this [later iteration](https://bl.ocks.org/micahstubbs/66db7c01723983ff028584b6f304a54a) with improved plot and table widths

[commit history](https://github.com/micahstubbs/crossfilter-experiments/commits/master)

---

This is an updated version of [this demo](http://crossfilter.github.io/crossfilter/) of the crossfilter library. Crossfilter has been one of my favorite - and what I think to be on of the most underrated - JavaScript libraries. It hasn't seen much of any updates in quite a while, so I wanted to find out how it would work with version 4 of d3.js.

There were some issues that came up with how d3-brush has been [updated for v4](https://github.com/d3/d3/blob/master/CHANGES.md#brushes-d3-brush). Big thanks goes to Alastair Dant ([@ajdant](https://twitter.com/ajdant)) for helping to figure out a couple of those issues! 

Also worth reading, is [this discussion](https://github.com/plotly/plotly.js/issues/1316) started by 
Robert Monfera ([@monfera](https://twitter.com/monfera)). 