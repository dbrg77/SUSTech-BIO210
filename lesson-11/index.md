# Week 8, Friday


## Friday, 2022-Apr-08
What we have been dealing with so far are all absolute quantities, such as the number of emails we received per day and the the expression level of a specific gene. In some other situations, the relative quantities are more meaningful. Let's use the correct answer of __multiple choices__ questions as an example.

__Multiple choices__ question is a common type of question in many exams. Typically, four choices (__A__, __B__, __C__ and __D__) are provided and only one of them is true. We are told that the test makers make sure that the correct answers have a uniform distribution among __A__, __B__, __C__ and __D__. In this case, the population is an abstract concept of all multiple choices questions in the world. Let's say we are interested in those questions whose correct answer is __A__. We will talk about how to deal with __A__, __B__, __C__ and __D__ altogether in the later section of the course, but for now, we only focus on __A__. We are interested in "how many" questions there are in the whole population whose correct answer is __A__. I think you can appreicate that the absolute number here is not really useful if you take it out from the context. It is only meaningful when you compare the number to all other numbers, that is, the number of quesitions whose correct answers is __B__, __C__ or __D__. Therefore, when we say "how many", what we really meant is the fraction or __proportion__ of the questions in the population whose correct answer is __A__. This __population proportion__ is a population parameter. As always, we use a Greek letter to denote a population parameter. In this case, it is $\boldsymbol \pi$.

As usual, $\pi$ is unknown. What we can do is to draw a sample and use the data from the sample to estimate $\pi$. Let's say, we take a random sample of size $n$, and it turns out that $x$ questions whose correct answer is __A__. You guessed it, the point estimate for $\pi$ is basically the __sample proportion__ ($\boldsymbol p$):

$$p=\cfrac{x}{n}$$

How do we make an interval estimation? This is what we are going to talk about on Friday's lectures. We wil introcuce a new type of random variable called the __indicator variable__. We will talk about the sum and the mean of $n$ `i.i.d` indicator variables, and how we could use them to figure out the sampling distribution and the confidence interval of a proportion.

#### Lecture slides
- [Lecture 21 Sampling Distribution of Sample Proportion](/lecture_slides/Lecture_21_Sampling_Distribution_of_Sample_Proportion_handout.pdf)
- [Lecture 22 Confidence Interval For The Proportion](/lecture_slides/Lecture_22_Confidence_Interval_For_The_Proportion_handout.pdf)

#### Extra reading material
- None

#### Homework assignment
- None

#### Interesting links
- [Five Confidence Intervals for Proportions That You Should Know About](https://towardsdatascience.com/five-confidence-intervals-for-proportions-that-you-should-know-about-7ff5484c024f)
