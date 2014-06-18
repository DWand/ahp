## What is it

This web-based desktop application is a simple realization of the [analytic hierarchy process (AHP)](http://en.wikipedia.org/wiki/Analytic_hierarchy_process).

You can:
* add alternatives
* add criteria:
  * absolute - each alternative has a concrete value (like speed or weight)
  * relative - you can compare alternatives to each other (like style or experience)
* set criteria priorities
* discover which alternative is better based on utility and cost
* save / load results (JSON)

Limitations:
* Only one level of hierarchy is currently available


## Dependencies

This application is written to run with [node-webkit](https://github.com/rogerwang/node-webkit). With a little modifications it also can be used with a regular browser but with file system access limitations.


## Technologies

This project uses:

1. [node-webkit](https://github.com/rogerwang/node-webkit)
2. [AngularJS](http://angularjs.org/)
3. [Semantic UI](http://semantic-ui.com/)


## Notes

* Ukrainian language of the UI
* This is not a production oriented product, use it for your own risk