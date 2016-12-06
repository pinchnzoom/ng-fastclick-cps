# ng-fastclick-cps - Child Protective Services

This directive adds the 'needsclick' class 

This is a fork of [8bitDesigner's](https://github.com/8bitDesigner) faulty [ng-fastclick](https://github.com/8bitDesigner/ng-fastclick)
which is a very thin (3 line!) Angular wrapper around the [FT's](https://github.com/ftlabs) fantastic [FastClick](https://github.com/ftlabs/fastclick)

## Installation

In your Angular project, run `bower install --save ng-fastclick-cps` to save the
module. Then, in your HTML, add:

``` html
<script src="/path/to/bower_components/ng-fastclick-cps/dist/index.min.js"></script>
```

And lastly, in your Angular module, include `ng-fastclick` as a dependency:

``` javascript
angular.module('my-app', ['ng-fastclick-cps'])
```

