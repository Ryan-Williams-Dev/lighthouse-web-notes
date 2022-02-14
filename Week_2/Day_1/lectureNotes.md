# Lecture - Week 2 - Day 1

---

## Testing

* Functions without return values are super hard to test
* console.assert NO NOT USE, counter-intuitive
* nodejs.org for documentation of js/node backend stuff
* documentation orr assertions for testing
* square brackets in documentation means optional, not array
* `assert.equal` uses `==` `assert.strictequal` uses `===`
* `require()` is common JS syntax
* `import __ from __` is not used by node
*  could use `.strict` to use it all in strict mode
* Errors are your friend, root out all problems. not let them go by
* lots of syntax does not work in the browser, the node wrapper function makes it possible
* module is the object that wraps our code
* our exported function gets placed into this node wrapper object
* The require function RUNS the file it is importing, so any console logs ect that are in there will run

### package.json

* meta information about our project
* lists all of our dependencies
* npmjs.com for packages
* `--save-dev` installs it only as a dev dependency
* no not install globally
* .gitignore file, put anything you want git to ignore and NOT track

### Mocha 

* throw new Error
* it() will return a pass unless it throws an error
* describe organises our tests into groups, but it not strictly needed


TDD - Test driven development.
write the tests first, then write the code to fit those tests.


