## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.


### Provide examples for all three, below:

#### Scope:
There are two scopes. Local and Global. A variable that is declared inside of a function is local, outside is global.

  var globalVariable =;
(function() {
  "use strict";
  let localVariable = 2 + 2;

})();

#### Hoisting:
Javascript moves all variable and function declarations (and only actual declarations) to the top of the current scope.


#### Compartmentalization:

Compartmentalized code is used to avoid overriding global variables upon execution.

In the Scope example, we are compartmentalizing localVariable to the function. If called outside of the function it will be undefined. 
