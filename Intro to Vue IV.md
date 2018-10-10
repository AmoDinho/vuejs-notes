# Intro to Vue IV

The maintainers of Vue provided a CLI that allows you to get up and running with the best practicies for your Vue apps. 
There two ways to get started: 


Grab the [Vue CLI](https://cli.vuejs.org/) by running the following in your terminal:

```
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

Once that is done, run the following and follow the instructions to create a project:

```
vue create my-project
# OR
vue ui
```

The other way is to use the CLI from a [Codesandbox template](https://codesandbox.io].

## Lifecycle methods

* `beforeCreate()`
* `created()`
* `beforeMount()`
* `mounted()` => `beforeUpdate()`/`updated()`/`activated()`/`deactivated()`
* `beforeDestroy()`
* `destroyed()`

Lifecycle hooks are auto-bound to the instance that will allow you access to the component's state and methods. Avoid using arrow functions on a lifecycle method, it will return the parent.
