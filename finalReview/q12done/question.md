What is the output of the following?  Please explain (credit given for the explanation only). 

Hint: This tests your understanding of "hoisting". It might help to write down what is happening step by step.

```
  function bar() {
    return foo;
    foo = 10;
    function foo() {}
    var foo = '11';
  }

  console.log(typeof bar());
```

It outputs "undefined."
Return is able to complete and terminate the function with foo as a variable but not with an attached value: thus it is undefined.
