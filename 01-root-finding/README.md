
# Root Finding

I started this section while learning numerical methods and trying to understand how mathematics can be turned into something a computer can actually work with.

The basic problem is simple:
f(x)=0
We want to find the value of \(x\) that makes the function zero, for some equations, we can find the answer directly. But many equations that appear in science and engineering don't have a convenient exact solution. In those cases, we need numerical methods to get a good approximation.
That's what I want to explore here.

--> What I am learning
   I am starting with a few different approaches to root finding:

   * Bisection Method
   * Newton-Raphson Method
   * Secant Method
   * Fixed-Point Iteration
   I don't want to just implement these methods from a textbook. I want to understand what is happening behind each one, why it works, how quickly it converges, and where it can fail.

--> My approach
    For each method, I will go through:

  1. The mathematical idea
  2. The derivation
  3. The algorithm
  4. My own implementation
  5. Some experiments
  6. Error and convergence
  7. Cases where the method doesn't behave as expected. For example, with the Bisection Method, I am interested in seeing how repeatedly cutting an interval in half can gradually lead us towards a root.

^^Why I am doing this?
I am interested in mathematics, and want this repository to be a place where I can learn that connection by actually building things and experimenting with them.
This is a learning project, so I will also keep track of mistakes, limitations and things I don't understand yet.

-^- Progress

* [ ] Bisection Method
* [ ] Newton-Raphson Method
* [ ] Secant Method
* [ ] Fixed-Point Iteration

More methods and experiments will be added as I learn them.
