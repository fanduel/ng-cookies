# ngCookie

Example of usage:

```
    angular.module('myModule', ['ngCookie'])
        .controller('myCtrl', ['cookies',
          function(cookies) {
            cookies.set('testCookie', 'testValue');
            cookies.get('testCookie');
         } 
     ]); 
 ```
 
## Using with Rails

In the Gemfile: `gem 'rails-assets-ng-cookies', source: 'https://rails-assets.org'`

In application.js `//= require ng-cookies`
