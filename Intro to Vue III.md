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

## Links to examples on CodePen

* [Vue: Simple Component](https://codepen.io/Amo-Prince/pen/OBMvGQ)
* [Vue: Component Props](https://codepen.io/Amo-Prince/pen/VEexvW)
* [Vue: Isolated Component Scope](https://codepen.io/Amo-Prince/pen/qJbYmr)
* [Vue: Components (comments)](https://codepen.io/Amo-Prince/pen/MPKXZr)
* [Vue: Components (comments)_I](https://codepen.io/Amo-Prince/pen/RerBwP)
* [Vue: Components with events](https://codepen.io/Amo-Prince/pen/VEeBBj)
* [Vue: Components with multiple events](https://codepen.io/Amo-Prince/pen/ePJPgR)
* [Vue: Components with multiple events](https://codepen.io/Amo-Prince/pen/jeWvMR)
* [Vue: Components with events I](https://codepen.io/Amo-Prince/pen/zmrLXY)
* [Vue: Components exercise](https://codepen.io/Amo-Prince/pen/gBPZYo)


