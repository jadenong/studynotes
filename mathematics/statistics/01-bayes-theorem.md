# Bayes' Theorem
Bayes' Theorem asserts the following:

![](https://latex.codecogs.com/gif.latex?P%28A%7CB%29%3D%5Cfrac%7BP%28B%7CA%29P%28B%29%7D%7BP%28A%29%7D)

This equation can seem daunting and its applications can produce results that are counterintuitive. In this set of notes, I aim to explain Bayes' Theorem and run through a few applications of it. I will also explain joint and conditional probabilities, and the sum and product rule.  

# Independent and Dependent Events
In the 'O' level, you may have learned about the probability of two events happening and the probability of one of two events happening. Those equations only apply to events that are not independent of each other. When it comes to dependent events, new formulas and definitions must be learned to solve increasingly interesting and complex problems.

## Sum Rule
When dealing with probabilities, we might get a series of joint probabilities (i.e. probabilities of two independent events both occuring). Let's examine the following, somewhat contrived, data set as an example.

*Disease X is a deadly disease that affects people with different hair colors differently. The table below shows the relationship between survival and the hair color of a patient. Each cell represents the probability of a person having a certain hair color and surviving/dying. For instance, 0.5 represents the probability that a patient has blue hair and survives their disease.*
|         | Blue | Green | Yellow | Red  |
|---------|------|-------|--------|------|
| Survive | 0.5  | 0.2   | 0.1    | 0.01 |
| Die     | 0.1  | 0.3   | 0.1    | 0.4  |

With this data, we are able to tell the survival rate of patients with disease X, despite not being given the value. We can do this by adding the joint probabilities of surviving disease X with blue, green, yellow, and red hair colors. Therefore,

![](https://latex.codecogs.com/gif.latex?P%28%5Ctext%7Bsurvival%7D%29%3D0.5&plus;0.2&plus;0.1&plus;0.01%3D0.81)

Intuitively, this makes sense. The number of people who survive is the sum of the number of blue, green, yellow, and red-haired people who survived. Likewise, the probabilities of survival is simply the sum. We can express this relationship in something known as the sum rule, as shown below. 

![](https://latex.codecogs.com/gif.latex?P(\text{X})=P(x,y_1)&plus;P(x,y_2)&plus;...&plus;P(x,y_n))

Applying the sum rule to our problem yields the below which result, which is the same as what we did earlier.

![](https://latex.codecogs.com/gif.latex?P(\text{survival})=P(\text{s},\text{green})&plus;P(\text{s},\text{yellow})&plus;P(\text{s},\text{red})&plus;P(\text{s},\text{blue}))

Sometimes, P(X) is known as the marginal probability. You can think of it as being the probability that is on the margin of the table.

<details>
  <summary>Problems (click to expand)</summary>
  1. Using the above data set, find the probability of a patient with disease X having blue hair.  
  2. What is the sum of all the joint probabilities of a data set? Explain why.
</details>

## Product Rule

![](https://latex.codecogs.com/gif.latex?P(A|B)=&space;P(A)\kern0.3em&space;\text{given}\kern0.3em&space;B)

When we have a conditional probability, it is the probability of an event occuring, given that a second, non-independent event occurs as well. The bar in the above equation just means 'given that'.

![](https://latex.codecogs.com/gif.latex?P(A|B)=\frac{P(A,B)}{P(B)})

This is an equation describing the relationship between conditional, marginal, and joint probability.

## Bayes' Theorem

## Further Reading
AP Statistics Probability. Khan Academy. https://www.khanacademy.org/math/ap-statistics/probability-ap  
You Know I’m All About that Bayes. CrashCourse. https://www.youtube.com/watch?v=9TDjifpGj-k  
The Bayesian Trap. Veritasium. https://www.youtube.com/watch?v=R13BD8qKeTg
Bayes Theorem. 3Blue1Brown. https://www.youtube.com/watch?v=HZGCoVF3YvM  
The Quick Proof Of Bayes' Theorem. 3Blue1Brown. https://www.youtube.com/watch?v=U_85TaXbeIo  

What Is A Marginal Probability? Ox educ. https://www.youtube.com/watch?v=r27mouuyFQk
