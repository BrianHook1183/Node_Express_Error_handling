# Node & Express: Error handling

## Instructions
Your goal for this checkpoint is to get the tests to pass. To do so, you will be building two functions to handle errors:

1. A "catch all" middleware function that is called whenever a non-existing route is called. The response should be as follows:
```An error occurred: Could not find route.```
1. An error handler middleware function that is called during an error (e.g. when the next() function is called with an argument). The error should be as follows, where <error> is whatever is the first argument of the error handler:
```An error occurred: <error>```