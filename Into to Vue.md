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

[Image of directives]()
