NG-Communicate-Ctrls
====================

A lot of friends learning Angular ask me about this topic (communicating between controllers).  So much, in fact, that I'm writing a blog post about it.

The real answer is that there are a number of ways, **but, the best practice is to keep controllers from being aware of each other as much as possible** (personally, I would insist they should never be aware of each other).

The following directories include examples of each strategy.  This codebase will be updated as I write the articles:

* **parent-child**: demonstrates Parent-Child controller communication using shared scope.
* **pubsub**: demonstrates using Angular's `emit`, `broadcast`, and `on` facility to communicate between components.
* **service**: demonstrates using a third-party mechanism to synchronize state between controllers.
* **router**: demonstrates how to pass state via route transitions in an application.