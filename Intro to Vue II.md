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


## Links to some examples on CodePen


[Vue Directives practice](https://codepen.io/Amo-Prince/pen/jvPXdo)
[Vue: Methods (comments)](https://codepen.io/Amo-Prince/pen/GXJegK)
[Methods](https://codepen.io/Amo-Prince/pen/RYPdVw)
[Vue: Methods in Forms](https://codepen.io/Amo-Prince/pen/OoVGwE)
[Vue Methods: Sorting](https://codepen.io/Amo-Prince/pen/rZOPvW)
[Vue Computed props(https://codepen.io/Amo-Prince/pen/oPjmOy)
[Vue Computed: Exercise](https://codepen.io/Amo-Prince/pen/GXpLVy)
[Vue: Watchers II](https://codepen.io/Amo-Prince/pen/WarMqO)
[Vue: Watchers I](https://codepen.io/Amo-Prince/pen/ZqQrJJ)
[Vue: Slots](https://codepen.io/Amo-Prince/pen/qJbQjW)
