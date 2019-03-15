# ember-animated-tools

Renders the debugging toolbar seen on [Ember Animated's docs site](https://ember-animation.github.io/ember-animated) which can be used to slow down and inspect your animations.


Compatibility
------------------------------------------------------------------------------

* Ember.js v2.18 or above
* Ember CLI v2.13 or above


Installation
------------------------------------------------------------------------------

```
ember install ember-animated-tools
```


Usage
------------------------------------------------------------------------------

Add the slideable widget:

```hbs
<AnimatedTools />
```

Or add it, but keep it hidden until a hotkey reveals it:

```hbs
<AnimatedTools @hideUntilKeys="Ctrl-Shift-KeyA" />
```

Or if you want to use the lower-level pieces, you can directly place the `<MotionIndicator />` or `<TimeControl />` components wherever you like.



Contributing
------------------------------------------------------------------------------

See the [Contributing](CONTRIBUTING.md) guide for details.


License
------------------------------------------------------------------------------

This project is licensed under the [MIT License](LICENSE.md).
