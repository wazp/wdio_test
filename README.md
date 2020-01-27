# WDIO Test case, showing bug with test.error in `afterTest()` hook

This is a tiny test case showing a bug with the test.error object when using it from the `afterTest()` hook.

## Expected behavior:
Get the correct object, with the error in it's own key. In version  it was available under the key `test.err.message` and `test.err.type`.

