# Week 6, Tuesday


## Tuesday, 2022-Mar-22
On Tuesday, we are going to introduce the most important two concepts in this entire course: __the sampling distribution__ and __the central limit theorem__. We will see how they help us make inferences about the population based on just one sample with limited size ($n$).

To start, let's say we are interested in the __population mean $\mu$__, and we used the __sample mean $\bar{x}$__ as the estimate. To get the sampling distribution, we first draw a random sample with size $n$ from the population, and we observe the sample mean of this sample. Then we independently draw another sample with the same size ($n$) from the population, we get another sample mean. We keep repeating those sampling procedures for many times, we will get a lot of sample means. The distribution of those values are called the __sampling distribution of the sample mean__. In practice, we don't really need to draw a lot of samples. We only need one sample. Why? Because we can find the sampling distribution theoretically. We don't really need to do repeated sampling to figure out the sampling distribution in practice.

__The central limit theorem__, developed by the French mathematician [Pierre-Simon Laplace](https://en.wikipedia.org/wiki/Pierre-Simon_Laplace), tells us that provided that the sample size ($n$) is large enough, the sampling distribution of the sample mean follows a normal distribution, even if the population distribution is not normal. This is a very powerful theorem that allows us making inferences about the population mean using only one sample.

Why is this helpful? Well, as you will see during the lectures, they allow us to analyse the following situation. Imagine we are interested in the body weights of all undergraduate students. We draw a random sample, and observe the sample mean is 60 kg. Since the sample mean is an estimate of the population mean, it is reasonable to guess that the population mean (mean body weight of all undergraduate) is 60 kg. However, how confident are we about this guess? Well, with the help of the central limit theorem, we can calculate __if__ the population mean is indeed 60 kg, what is the probability of observing our sample with a mean 60 kg or more extreme. We will elaborate this later on.

Another question you might ask is about the sample size $n$: how large is large enough? Well, we will investigate this in the later section of the course, but in general, $n \geqslant 30$ is large enough.

#### Lecture slides
- [Lecture 15 The Sampling Distribution And The CLT (Part I)](/lecture_slides/Lecture_15_Sampling_distribution_and_CLT_I_handout.pdf)
- [Lecture 16 The Sampling Distribution And The CLT (Part II)](/lecture_slides/Lecture_16_Sampling_distribution_and_CLT_II_handout.pdf)

#### Extra reading material
- None

#### Homework assignment
- None

#### Interesting links
- [Sampling distribution simulation](https://onlinestatbook.com/stat_sim/sampling_dist/)
- [The Central Limit Theorem](http://en.wikipedia.org/wiki/Central_limit_theorem)
- [Pierre-Simon Laplace](https://en.wikipedia.org/wiki/Pierre-Simon_Laplace)

