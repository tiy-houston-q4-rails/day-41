Day-41 - Rails Testing 
=====

### Model Tests

* Create a blank Rails App
* Create a bank account class
* Write tests to describe depositing money into the bank account
* Write tests to describe withdrawing money from the bank account

### Create a simple API for an ATM to use
* post to `/withdraw/:account_id`, and test that the account will be withdrawn
* this should have a controller test

Notes:
-----

* You cannot go negative in this bank, so withdrawls that would go negative
  should error (throw exception, or just keep account balance the same)
* Only get the models and test. No UI. No Login.

Extra:
-----

* Get your app live and working on http://travisci.org/

Links
-----

* http://www.mattsears.com/articles/2011/12/10/minitest-quick-reference
* Intro to TDD:
  https://rubyoffrails.com/videos/18-introduction-to-test-driven-design-tdd
* Testing 3 ways:
  https://rubyoffrails.com/videos/12-testing-3-ways-rspec-minitest-test-unit
