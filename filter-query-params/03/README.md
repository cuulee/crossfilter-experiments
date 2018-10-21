this iteration stores the extent of each chart filter in the url query string, so that URLs to unique filter views can be shared.

this iteration was motivated by a desire to be able to generate a downloadable image or document of the crossfilter dashboard for the user, at the current filter state. storing the filter states in the url is one way to communicate to the screenshot server how the dashboard should look when the server captures the screenshot.

I encourage you to read more about [URLSearchParams](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams) and the browser history [pushState() method](https://developer.mozilla.org/en-US/docs/Web/API/History_API#The_pushState()_method) used to read and write the page's url without triggering a full page reload.

an iteration on [Crossfilter Demo | es2015 d3v4](https://bl.ocks.org/micahstubbs/66db7c01723983ff028584b6f304a54a) from [@micahstubbs](https://twitter.com/micahstubbs)

---

this iteration

- moves css into index.css
- prettier formats css
- renames vis.js index.js for consistency
- suppresses the favicon.ico request ([stackoverflow answer](https://stackoverflow.com/a/13416784/1732222) on this topic)

---

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
