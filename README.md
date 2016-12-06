# ng-fastclick-cps - Child Protective Services

## Angular Fastclick Child Protective Services, was designed... 
To what: Allow any children inside of element with the '.needsclick' class to ignore fastclick.

To how: By targeting elements with the .needsclass on up through the DOM.

To why: Because ng-fastclick did not work with the angular-datepicker plugin on Phonegap builds on iOS. 

This plugin was designed to work with [fragaria's](https://github.com/8bitDesigner) faulty [angular-daterangepicker](https://github.com/fragaria/angular-daterangepicker)  

This is a fork of [8bitDesigner's](https://github.com/8bitDesigner) faulty [ng-fastclick](https://github.com/8bitDesigner/ng-fastclick)
which is a very thin (3 line!) Angular wrapper around the [FT's](https://github.com/ftlabs) fantastic [FastClick](https://github.com/ftlabs/fastclick)

### Installation

In your Angular project, run `bower install --save ng-fastclick-cps` to save the
module. Then, in your HTML, add:

``` html
<script src="/path/to/bower_components/ng-fastclick-cps/dist/index.min.js"></script>
```

And nextly, in your Angular module, include `ng-fastclick-cps` as a dependency:

``` javascript
angular.module('my-app', ['ng-fastclick-cps'])
```

And Lastly, add the '.needsclick' class for elements that you want to avoid using fastclick functionality.
``` html
<any class="needsclick"></any>
```



