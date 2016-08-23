DOES THE COMMIT REALLY FIXES THE BUG?
=====================================

In OpenStack, provide unit tests in a bug fix is "almost" mandatory, since as
any rule, there are exceptions. As a reviewer, isn't always clear that the
proposed fix really fixes the issue. A good way to make sure that's the case
is to run the provided unit tests without the fix itself, if the tests pass
either the fix isn't correct or the test don't really test the bug scenario.

This (WIP) tool provides quick way for a reviewer to run unit tests without
manually reseting the actual fix.
