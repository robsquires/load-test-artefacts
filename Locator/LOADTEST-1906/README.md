INSTRUCTIONS
===========

LOCATOR TESTS
-----------

There are three tests: lts_020.jmx, lts_021.jmx, lts_025.jmx which are located in this directory.

(.jmx are JMeter XML files)


REVIEWING TESTS
--------------

1. "brew install jmeter"
2. Open a .jmx file

Test Structure
--------------

The tests are contained within a Test Plan

* HTTP Request Defaults => HTTP defaults including host name and proxy
* View Test Results => A "listener" that returns HTTP responses. Memory
  intensive and used for debugging purposes.
* Aggregate Report => This gives us average response times, throughput errors etc
* HTTP Header Manager => Enter all your browser header strings here
* Constant Throughput Timer => This ensures a fixed RPS. 200 RPS = (200 x 60)
* Thread Group => The number of threads we want to use for the test, plus ramp-up time
* HTTP Request => The actual request with params. ${*} is a variable
* CSV Data Set Config => The data file that we are reading


Aidy Lewis




