WTF
===

Scratch repo so I can figure out what github is doing weirdly without pumping test commits through my normal repos. github is great, but sometimes it's really hard to figure out what magic it's doing.

* [Link to repository owner's profile](.)
* [Link to tree???](./master/)
* [Link to README???](./README.markdown)

<hr>

Running
-------

There are a number of ways to run the `puppet-module` program:

1. **From an official gem:** Install it by running:

        sudo gem install puppet-module

2. **From a locally-built gem:** Checkout the source code and from the checkout
directory, run:

        \# Build the gem
        rake gem
        \# Install the file produced by the above command, e.g.:
        sudo gem install pkg/puppet-module-0.3.0.gem

3. **From a source code checkout:** Checkout the source code and from the checkout
directory, run:

        alias puppet-module=$PWD/bin/puppet-module

Basics
------

Display the program's built-in help by running:
