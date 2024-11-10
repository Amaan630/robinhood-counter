# Vue Robinhood-Style Counter

Non continuous effect (more like robinhood)

![non-continuous](./non-continuous-ezgif.com-video-to-gif-converter.gif)

Continuous effect (it'll count through the numbers in-between). This effect is a bit less stable, if anyone can figure it out lmk.

![continuous](./continuous-ezgif.com-video-to-gif-converter.gif)

## Installation

You can just copy the `MechanicalCounter.vue` file directly into your project and it should work.

## Example usage

```
<MechanicalCounter
    :start="9999.0"
    :end="899.0"
    before="$"
    after="/mo"
    is-price
    continuous />
```

start: the starting number

end: the ending number

before: the text to show before the number (non numerical characters would need to go here)

after: the text to show after the number (non numerical characters would need to go here)

is-price adds the commas

continuous switches the effect to the continuous counter. By default this is false.
