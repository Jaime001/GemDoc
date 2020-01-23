# "How to create a gem in Ruby with Bundler"

## What is a gem?

In Ruby, a ***gem*** is a library package as in JS which are installed in the system for later use.

# What is inside a gem?

* /lib
* / bin
* / spec
* .gemspec
* Documentation


### /lib: 
> Stores the main ruby ​​file where the code for the gem's functionality is entered.

### /bin: 
> Contains the console and the program setup.

### Documentation: 
> Contains information about the gem, how to install it, what it is for and how to use it.

### .gemspec: 
Contains the specifications of gems such as:
* authors =
* records
* name
* summary
* version
> The rest of the specifications are recommended or optional.


**Now that we know a little more about what a gem contains, let's create one!**
# What is Bundler?
> Bundler provides a consistent environment for Ruby projects by tracking and installing the exact gems and versions that are needed. For more documentation: https://bundler.io

# Bundler installation

> For install bundler add the follow command: 
* $ bundle install

Once installed, in the directory in which we want to create the gem and enter the following command:
* $ bundle gem [name]

### The gem will be generated automatically and will be ready to use.
