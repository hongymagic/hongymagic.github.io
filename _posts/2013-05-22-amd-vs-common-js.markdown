---
layout: post
title: AMD vs. CommonJS
category: posts
---

There's been a quite a lot of heated discussions surrounding [AMD][] and
[CommonJS][] modules. What needs to be realised is that we tend to discuss
these two in two separate notions:

1. Module definition; and
2. Module loading.

Having used both [CommonJS][] and [AMD][] previously, personally, I would
prefer the following:

- Less ceremonal/verbose syntax of [CommonJS][];
- *Optionally* load modules asynchronously like [AMD][].

This behaviour should be consistent across anywhere JavaScript can be run ie.,
browsers, rhino, node.js and more.

- [TODO] Catch up on ES6 discussion thread on modules

*by [hongy][] with* ♥

[hongy]: https://twitter.com/hongymagic
[AMD]: http://wiki.commonjs.org/wiki/Modules/AsynchronousDefinition
[CommonJS]: http://wiki.commonjs.org/wiki/Modules/1.0
