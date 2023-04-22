CSS Transitions

Review

_CSS Transitions_ are a powerful tool for providing visual feedback to users. We’ve learned a lot about transitions, so let’s review:

CSS Transitions have 4 components:

- A _property_ that will transition.
- The _duration_ which describes how long the transition takes.
- The _timing function_ that describes the transition’s acceleration.
- The _delay_ to pause before the transition will take place.

A simple transition can be described with a property and a duration, which can be written like this:

    transition-property: color;transition-duration: 1s;

Many properties’ _state changes_ can be transitioned, including color, background color, font size, width, and height. `all` is also a valid transition property that causes every changing property to transition.

The shorthand property `transition` can be used to describe all four components of a transition at once. By using the comma (`,`) operator, many transitions can be described in one CSS rule.

If you want to learn more about CSS Transitions, we recommend MDN’s [Using CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions) doc.

Good work, you now have the tools to make your web pages come to life!
