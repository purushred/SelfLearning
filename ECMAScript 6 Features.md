Some of the new features of ES6:
--------------------------------
Support for 'const' constants (also known as “immutable variables”) <br>
   * const is a immutable parameter. Cannot re-assign once declared.
   * let is a block scoped. Multiple parameters cannot be declared in the same block.
   * var is a function scoped.
Block-Scope support for both variables, constants, functions <br>
   * 
Arrow functions <br>
   * Shorthand notation for writing a function.
   * Ex: function add(a,b) { return a+b }
          let result = (a,b) => a+b;
          
Extended Parameter Handling <br>
Template Literals and Extended Literals <br>
Enhanced Regular Expression <br>
Destructuring Assignment <br>
    * let arr = [10,20,30];
      const [a,b,c] = arr;
      let obj = {name:"Purush",age:30}
      const {name, age} = obj;
      let arr = [10,20,30,40,50]
      const [a,b,...rest] = arr;
Modules, Classes, Iterators, Generators <br>
Enhanced Object Properties <br>
Support for Map/Set & WeakMap/WeakSet <br>
    * Set <br>
       * Contains collection of unique values.
       * Value can be primitives or object references.
       Ex: let set = new Set():
       set.add(10);
       set.add(20);
       set.add(30);
       set.delete(30) -> return true
       set.has(20) -> return true
       set.forEach(item => console.log("Item:",item));
       set.size;
    * WeakMap <br>
       * It is like Map but the key must be an object.
       * The object references are held weakly, meaning the objects will be eligible for GC if no references to the object.
       * The keys are not enumerable like in Maps.
       Ex: let weakMap = new WeakMap();
           let obj1 = {"name":"Purushotham"}
           let obj2 = {"age": 30}
           weakMap.set(obj1, "Value1");
           weakMap.set(obj2, "Value2");
           weakMap.has(obj1) -> returns true
           weakMap.delete(obj2) -> returns true
      
Promises, Meta-Programming ,Internationalization and Localization <br>
