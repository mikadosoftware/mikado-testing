mikado-testing
==============

Examples and tools to make testing (or writing tests)
much more ... natural

I don't write enough tests.  I don't have any good excuses
but if I make it much much easier to, perhaps I will improve.

I prefer functional testing as the coverage is greater and
usually the intent is easier to define, and generally unit testing
is small and specific.  And starts to ossify much earlier.

Tests must be run on every commit / before every commit / push
SO that implies a local docker build / jenkins build so that I can
do the testing (which if it is an API implies quite a lot of other things)

Basic problem with testing

* unit tests can run right there in one module, with no dependancies
* Every other test has some setup, some dependancies.  (yes you can mock but I find that immediately ossifies the tests, and

Third problem - prod monitoring is a QA is a test
The tests need to work in production as well as in my local dev machine.




[ ] get pyexpect working as bare bones functional tester
[ ] get api tester (requests) working for apis
[ ] gete selenium working for UI testing
