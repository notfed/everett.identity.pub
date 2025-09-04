# Many Worlds Explorer

See [http://mw.identity.pub/](http://mw.identity.pub/).

<p>Preview:</p>

<p align="center">
<a href="http://mw.identity.pub/"><img src="ss.png" alt="alt text" width="500"></a>
</p>

### Motivation

The [many-worlds interpretation of quantum mechanics](https://en.wikipedia.org/wiki/Many-worlds_interpretation) says that the universe is deterministic. (I.e., that is is, and only is, a vector in Hilbert space evolving deterministically according to the [Schrödinger equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation).)

So why does quantum mechanics give us random numbers, e.g. with a [quantum coin flip](https://en.wikipedia.org/wiki/Quantum_coin_flipping)? Well, to put it simply, many-worlds says that this "randomness" is an illusion, and that actually, for each coin flip, the world branches into two worlds: one where you measure a "heads", and one where you measure a "tails".

This tool is a visual demonstration of that idea. The key takeaway is that, for almost every possible "you," the measured outcomes converge to 50% heads and 50% tails as you collect more samples. While this simulation only collects a limited number of samples, it's enough to see the trend.

### What am I looking at?

- Cells represent worlds
- Each world branches into two worlds just below it:
    - A green world, representing heads
    - A blue world, representing tails
- You are `𖨆`. (Your cursor.)
- The vertical line represents the sequence of coin flips you've measured
- "Your time" shows how many coin flips you've measured
- "Your measurements" shows the counts and averages of the coin flips you've measured

### Advanced controls

| Press...               | To...                                  |
|------------------------|----------------------------------------|
| **Click and drag**     | Constrain yourself to one timeline     |
| **Drag the red line**  | Adjust the branch ratio                |
| **↑**                  | See more time shown on-screen          |
| **↓**                  | See less time shown on-screen          |
| **→**                  | Add a new branch                       |
| **←**                  | Remove a branch                        |