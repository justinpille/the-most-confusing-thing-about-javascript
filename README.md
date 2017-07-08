# The Most Confusing thing about JavaScript

It is important to note the distinction between the way a prototype is associated with a constructor (through its `prototype` property) and the way objects *have* a prototype (which can be retreived with Object.getPrototypeOf). The actual prototype of a constructor is `Function.prototype` since constructors are functions. Its `prototype` *property* will be the prototype of instances created through it but is not its *own* prototype.

-- Eloquent JavaScript page 104.

The `prototype` property points to the object that will be asigned as the prototype of instances created with that function when using `new`.

-- A Plain English Guide to JavaScript Prototypes
Sebastian Porto Feb 22nd, 2013
http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/
