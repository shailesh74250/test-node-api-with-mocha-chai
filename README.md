# test-node-api-with-mocha-chai

## Mocha: Testing Environment

Mocha is a javascript framework for node.js which allows async testing. let's say it
provides the Environment in which we can use our favorite assertion libraries to test the code.

Mocha comes with tons of great features, the website shows a long list but here are the ones I like the most:

simple async support, including promises.
async test timeout support.
before, after, before each, after each hooks (very useful to clean the environment where each test!).
use any assertion library you want, Chai in our tutorial.

## Chai: Assertion library

So with mocha we actually have the environment for making our tests but how do we test
HTTP calls for example ? Moreover, How do we test whether a GET request is actually returning the JSON
file we are expecting, given a defined input ? we need an assertion library, that's
why mocha is not enought.

Chai shines on the freedom of choosing the interface we prefer: "should", "expect", "assert" they are all available. 
I personally use should but you are free to check it out the API and switch to the others two.
Lastly Chai HTTP addon allows Chai library to easily use assertions on HTTP requests which suits our needs.
