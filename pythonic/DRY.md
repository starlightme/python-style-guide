# DRY原则 -- 不要重复你自己

Don't repeat yourself（不要重复你自己，简称DRY）是面向对象编程中的基本原则，程序员的行事准则。
旨在软件开发中，减少重复的信息。

DRY的原则是──系统中的每一部分，都必须有一个单一的、明确的、权威的代表──指的是（由人编写而非机器生成的）代码和测试所构成的系统，必须能够表达所应表达的内容，但是不能含有任何重复代码。
当DRY原则被成功应用时，一个系统中任何单个元素的修改都不需要与其逻辑无关的其他元素发生改变。此外，与之逻辑上相关的其他元素的变化均为可预见的、均匀的，并如此保持同步。

但过度的强调DRY，以及过早优化都是不对的，我们应该尽量避免过度抽象.有时候一定程度的冗余反而是好事.

关于抽象的原则，可以参看阮一峰的[这篇文章](http://www.ruanyifeng.com/blog/2013/01/abstraction_principles.html)
