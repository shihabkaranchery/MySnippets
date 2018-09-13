
## Advanced Javascript Notes

### "use strict";

* enable strict mode
* unable to use delete (can't delte any variable or function)
* eval variable declaration will not work

### pass by value and pass by reference

* primitive types such as string, number, boolean pas by value. Objects are pass by reference
    ```
    var a = 1
    function foo(a){
        a = 2;
    }
    foo(a)
    console.log(a)
    #Output
    1
    ```
* pass by value, copy the value only, modification inside the element won't effect
* pass by refrence, if any changes in the object withing the function it will change outside the scope

    ```
    // pass by reference
    var a = {"b": "ball"}
    function foo(a){
        a.a = "apple"
    }
    foo(a)
    console.log(a)
    #Output
    {b: "ball", a: "apple"}

    var a = {"b": "ball"}
    function foo(a){
        a = {"a": "apple"}
    }
    foo(a)
    console.log(a)
    #Output
    {b: "ball"}
    
    ```

