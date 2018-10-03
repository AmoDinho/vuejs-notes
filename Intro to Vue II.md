# Methods, Computed, Watchers

## Methods
Are bound to a Vue instance and used for functions to access in directives

# Computed Properties

Used for calculations that will be cached and updated when needed.


### Methods
* Runs whenever an update occurs
* Not cached
* Typically invoked from v-on/@, but flexible
* Getter/setter

### COMPUTED
* Runs only when a dependency has changed
* Cached
* Should be used as a property, in place of data
* By default getter only, but you can define a setter


# Watchers

### Reacters
Reactive programming has async data streams.

A stream is a sequence of contious events ordered in time that offer hooks to observe it. 

We can access the old and new values, as well as gaining access to nested values with 'deep':

```
watch: {
  watchedProperty (value, oldValue) {
    //your dope code here
  }
},

```
