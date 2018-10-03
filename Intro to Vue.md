# Directives & Data Rendering

## DIRECTIVES
v-text
mastuche like templates

v-html
for strings that html elements that need to be rendered

v-show / v-if

A conditional that displays info once it has met a requirement. 

v-else/v-else-if
Conditionally render items

v-for
Loops through a set of values 

v-on / @
for binding click events 


v-bind / :
can be used for class binding or style binding


v-model
Creates relationship between data in instance and form input to dynamically update vaules

v-pre 
will not update once its been rendered

v-once 
will print inner text how it is.


v-cloak

## Modifiers

v-model.trim : strips whitespace from string

v-model.number changes strings to number inputs

v-model.lazy won’t populate the content automatically, it will wait to bind until an event happens. 

## Multiple Bindings

```

<div @="
  click   : onClick,
  keyup   : onKeyup,
  keydown : onKeydown
">
</div> 

```


MODIFIERS
@mousemove.stop is comparable to e.stopPropogation()

@mousemove.prevent this is like e.preventDefault()

@submit.prevent this will no longer reload the page on submission

@click.once not to be confused with v-once, this click event will be triggered once.

@click.native so that you can listen to native events in the DOM

![Image of directives](https://github.com/AmoDinho/vuejs-notes/raw/master/screenshot-css-tricks.com-2018.08.21-12-29-12.png)

## Codepen links to some examples:



[Intro To Vue](https://codepen.io/Amo-Prince/pen/oMYQQv)

[Intro To Vue_IV](https://codepen.io/Amo-Prince/pen/JBbwrG)

[Vue:V-ON or @](https://codepen.io/Amo-Prince/pen/mGdgQQ)
[Vue: V-ONCE/V-PRE](https://codepen.io/Amo-Prince/pen/Pdogjy)
[Vue:V-BIND](https://codepen.io/Amo-Prince/pen/PdogGB)
[Vue Modifiers](https://codepen.io/Amo-Prince/pen/QVWogr)

