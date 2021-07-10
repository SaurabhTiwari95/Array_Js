# Array_Js
## Array.prototype.filter()
 ```
  This filter() method creates a new array with all elements that pass the test implemented by the provided function
 ```
 #### Return Value
 ```
  A New Array with the elements that pass the test. If no elements pass the test an empty array will be returned.
 ```
 ```
  const words = ['spray','limit','elite','exuberant','destruction','present'];
  const result = words.filter(word => word.length > 6);
  console.log(result);
 ```
 ## Syntax
 
 #### Arrow function
 ```
    filter((element) => { ... } )
    filter((element, index) => { ... } )
    filter((element, index, array) => { ... } )
```
 #### Callback function
```
     filter(callbackFn)
    filter(callbackFn, thisArg)
```
#### Inline callback function
```
    filter(function callbackFn(element) { ... })
    filter(function callbackFn(element, index) { ... })
    filter(function callbackFn(element, index, array){ ... })
    filter(function callbackFn(element, index, array) { ... }, thisArg)
 ```
 
