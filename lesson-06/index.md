# Week 4, Friday


## Friday, 2022-Mar-11
We introduced the concept of __random variables__ on Tuesday. It allows us to directly work on numbers without worrying about the __sample space__ that is sometimes difficult to come by. In these two lectures on Friday, we will introduce a few useful discrete random variables together with their __probability mass functions__. As you will see in the lectures, they are tightly related.

As I keep saying, when dealing with a new concept, always always start with something simple to get an intuition. The simplest discrete random variable is a __Bernoulli random variable__, a random variable with only two possible outcomes. Using the coin flipping experiment as an example, it is like flipping a coin exactly once.

Then, we look at performing $n$ independent Bernoulli trials, and check the number of a particular outocme (`success` or `failure`, `1` or `0`, `on` of `off` $etc.$). It is like flipping a coin $n$ times and check how many `Hs` or `Ts` are there. Again, do not think of this as $n$ distinct experiments. Instead, think of this as one single experiment with $n$ flips, and we only check the outcome at the end of the experiment when we finished all $n$ flips. This becomes the __binomial random variables__.

Going further, we let the number of trails $n$ becomes really really large ($n \rightarrow \infty$), and $np$ or $n(1-p)$ is small, it becomes the __Poisson random variables__. When $np$ and $n(1-p)$ are larege, the shape becomes the famous __normal random variable__, whic is the only continuous random variable we introduce in this course.

#### Lecture slides
- [Lecture 11 Discrete Probability Distribution](/lecture_slides/Lecture_11_Discrete_Probability_Distribution_handout.pdf)
- [Lecture 12 Continuous Probability Distribution](/lecture_slides/Lecture_12_Continuous_Probability_Distribution_handout.pdf)

#### Extra reading material
- [The Expectations And Variances of Binomial And Poisson Random Variables](/lecture_slides/Lecture_11_Expectations_variances_of_binom_and_pois_rv.pdf)

#### Homework assignment
- [Assignment 3](/assignments/Assignment_3.pdf)

#### Interesting links
- [The Waiting Time Paradox, or, Why Is My Bus Always Late?](http://jakevdp.github.io/blog/2018/09/13/waiting-time-paradox/)
- [Normal distribution](https://en.wikipedia.org/wiki/Normal_distribution)
- More on the history related to the normal distribution (in Chinese):
  - [Part 1](https://cosx.org/2013/01/story-of-normal-distribution-1)
  - [Part 2](https://cosx.org/2013/01/story-of-normal-distribution-2)
