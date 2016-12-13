DOES THE TESTS PASS WITHOUT THE CHANGES IN THE COMMIT?
------------------------------------------------------

In OpenStack, provide unit tests in a bug fix or new feature is "almost".
Thus, as a reviewer, isn't always clear that the proposed tests really checks
if an issue was fixed or correctly tests a feature. A good way to verify
that's the case is to run the provided unit tests without the changes in the
commit itself, if the tests pass either the fix/feature isn't correct or the
test don't really test the bug/feature scenario.

This (WIP) tool provides quick way for a reviewer to run unit tests without
manually reseting the actual change.
