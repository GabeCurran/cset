**How do you feel about the pace of the program so far? Is it too slow? Too fast? Or just right?**

In all honesty, I have been struggling to keep up. I don't think it's necessarily because the class is going "too fast" at all though. For some reason, certain things are just taking a bit to really stick. I constantly find myself looking something up again to double check the syntax or even just to see how it works exactly again.
I'm perfectly fine with that of course, it just gives me anxiety because I'm always worried that I'm going to fall behind or fail an assignment.
I get physically/mentally tired very quickly and so it's definitely been an exhausting few weeks. However, I also don't really feel like I *want* to go slower.

**Why do you think functions are a useful tool to organize large programs?**

To me, I feel like functions are like little pieces of program. I imagine them as puzzle pieces for the solution. It's elegant in a way, how they section off code from the rest of the program and just do their own job. They help prevent clutter, repetitive actions and help things run more efficiently. It also becomes much easier to re-use these sections of code by just calling the function again.

**In class, we've been using the analogy of a zoo to explain scope. Describe the different types of scope using this analogy and provide examples using real JavaScript code.**

The two main types of scopes would be Global scope and Local scope.

Global Scope & Local Scope;
This is like the walls of a zoo with habitats inside. The walls contain everything but you'll have to dig deeper to find the things inside it.
An example in code would be this "zookeeper" binding;
```
let zookeeper = 1
let food = "low"
  function Lions() {
  let food = "full"
    return ["roar", zookeeper]
  };
console.log(food)
console.log(Lions())

// => low
// => roar, 1
```

The global binding, "zookeeper" is still seen within the function.
However, food is still seen as low because even though it's full inside the "Lions" function, it cannot be read by the console.log outside.

The two types of Local Scopes are:
***Lexical**; Defined by a function* and
***Block**; Defined by curly brackets*
