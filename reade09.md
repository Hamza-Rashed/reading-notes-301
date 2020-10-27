# functional programming 
functional programming is a programming paradigm where programs are constructed by applying and composing functions. 
It is a declarative programming paradigm in which function definitions are trees of expressions that each return a value, 
rather than a sequence of imperative statements which change the state of the program.

In functional programming, functions are treated as first-class citizens, meaning that they can be bound to names 
(including local identifiers), passed as arguments, and returned from other functions, just as any other data type can. 
This allows programs to be written in a declarative and composable style, where small functions are combined in a modular manner.

Functional programming is sometimes treated as synonymous with purely functional programming, a subset of functional programming which treats all
functions as deterministic mathematical functions, or pure functions. When a pure function is called with some given arguments, it will always
return the same result, and cannot be affected by any mutable state or other side effects. This is in contrast with impure procedures, 
common in imperative programming, which can have side effects (such as modifying the program's state or taking input from a user). 
Proponents of purely functional programming claim that by restricting side effects, programs can have fewer bugs, be easier to debug and test,
and be more suited to formal verification.

![](https://i.imgur.com/fQUJjqf.png)

# Refactoring


Refactoring is a disciplined technique for restructuring an existing body of code, altering its internal structure without changing its external behavior.

Its heart is a series of small behavior preserving transformations. Each transformation (called a "refactoring") does little, but a sequence of these transformations can produce a significant restructuring. Since each refactoring is small, it's less likely to go wrong. The system is kept fully working after each refactoring, reducing the chances that a system can get seriously broken during the restructuring.

![](https://resources.jetbrains.com/help/img/idea/2020.2/ws_js_refactoring_rename_file_intention_custom_naming_convention.png)
