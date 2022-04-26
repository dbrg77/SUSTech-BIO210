# Week 11, Friday


## Friday, 2022-Apr-29
In our real life, there are many situations where we need to compare the means from many groups ($\geqslant 3$), representing many different populations. How do we do this? Intuitively, we just perform ___t___-test for every pair of them. This is actually not a bad idea when the number of groups ($k$) is small. However, when $k$ becomes large, we have to perform many tests. If you remember the content from the previous lecture, you should understand that this actually increases our chances of making type I errors.

Therefore, we should avoid doing ___t___-test for all possible pairs. Instead, we investigate where the variation in our data comes from. We will see that the variation in the whole data has two origins: variation within the same group and the variation ammong different groups. If the variation in the whole data mainly comes from the latter, we say their means are different. This is why we call this procedure __Analysis of Variance (ANOVA)__, but it is actually used to compare means.

#### Lecture slides
- [Lecture 31 Analysis of Variance (ANOVA)](/lecture_slides/Lecture_31_Analysis_of_Variance_ANOVA_handout.pdf)
- [Lecture 32 _Post hoc_ Multiple Comparisons](/lecture_slides/Lecture_32_Post_hoc_multiple_comparisons_handout.pdf)

#### Extra reading material
- [Using the F-test for two-sample comparisons](/lecture_slides/Lecture_32_F_test_and_t_test.pdf)

#### Homework assignment
- None

#### Interesting links
- [When does the F-test reduce to a t-test](https://canovasjm.netlify.app/2018/10/29/when-does-the-f-test-reduce-to-t-test/)

