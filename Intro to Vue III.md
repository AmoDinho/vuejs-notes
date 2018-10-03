# Templates

Vue uses HTML based template syntax for the Vue instance to be bound to the DOM.

## Components

A group of elements that grouped into a group that can be accessed by one element.


**props** allows one-way communication tht holds a variable that is waiting to be filled out by what the parent sends down. 

Object and arrays need their defaults to be returned from a function: 

```
text: {
  type: Object,
  default: function(){
    return {message: 'hello mr shq'}
   }
  }
```

We use v-bind or : to dynamically bind props to data on the parent:

```
//not using state of the parent
<child count="1"></child>

//using the state of the parent
<child :count="count"></child>


```
