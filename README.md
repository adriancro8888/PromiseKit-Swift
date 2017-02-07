# PromiseKit-Swift
A sample app that implements PromiseKit promises  to fetch Weather info and than displays in the app.You can read about PromiseKit [here](http://promisekit.org/)
This sample app shows how you can use PromiseKit to simplify asynchronous network calls.

Promises are about managing asynchronicity. Unlike traditional methods, such as callbacks via completions or selectors, promises can be easily chained together, so a sequence of asynchronous actions can be expressed. Promises are also like operations in that they have an execution lifecycle and can be cancelled.
A PromiseKit Promise executes a code block that is fulfilled with a value. Upon fulfillment, its then block is executed. If that block returns a promise, then that will be executed, fulfilled with a value and so on. If there is an error along the way, an optional catch block will be executed instead. 
