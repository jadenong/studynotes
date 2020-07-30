# 'O' Level Statistics
Statistics is taught at 'O' level on some level, usually with very little mathematical rigor or thought involved. What students learn is a definition of a formula (such as the formula to compute standard deviation) and how to use it. Students, however, are not exposed to the reasoning behind why such a formula works, what it produces, and why the product is useful. In this set of notes, I aim to shed light on the statistics that is taught at 'O' level, and to give a mathematical and practical basis behind it.

## Average

## Perfectly Reasonable Deviations
![](http://mathurl.com/render.cgi?%5Ctext%7BStandard%20Deviation%7D%20%3D%20%5Csqrt%7B%5Cfrac%7B%5Csum%20fx%7D%7Bf%7D%5E2%20-%20%5Cleft%28%20%5Cfrac%7B%5Csum%20fx%7D%7Bf%7D%20%5Cright%29%5E2%20%7D%5Cnocache)

Above is the formula given in the 'O' level formula sheet to calculate the standard deviation of a given data set. Such a formula is complicated, and teachers often fail to explain what the formula actually says. Furthermore, this particular formula, although useful in computing deviations by hand, is not the formula typically used to describe a standard deviation. The typical formula, as shown below, is much easier to understand.

![](http://mathurl.com/render.cgi?sd%20%3D%20%5Csqrt%7B%5Cfrac%7B%5Csum%20%28x-%5Cbar%7Bx%7D%29%5E2%7D%7Bn%7D%7D%5Cnocache)

Unfortunately, teachers do not make an attempt to teach this formula, despite its easiness to understand. The formula is made easier when each term is annotated, as shown below.

![](http://mathurl.com/render.cgi?sd%20%3D%20%5Csqrt%7B%5Cfrac%7B%5Csum_%7Bi%7D%5E%7B%5Ctext%7Bn%7D%7D%20%28x_%7Bi%7D-%5Cbar%7Bx%7D_%5Ctext%7Bmean%7D%29%5E2%7D%7B%5Ctext%7Bn%7D%7D%5Cnocache)

For those unfamiliar with the sigma notation, I have included an explanation of what it means in this context, as shown below.

![](http://mathurl.com/render.cgi?%5Csum_%7Bi%7D%5E%7B%5Ctext%7Bn%7D%7D%20%28x_%7Bi%7D-%5Cbar%7Bx%7D_%5Ctext%7Bmean%7D%29%5E2%20%3D%20%28x_1%20-%20%5Cbar%7Bx%7D_%5Ctext%7Bmean%7D%29%5E2%20+%20%28x_2%20-%20%5Cbar%7Bx%7D_%5Ctext%7Bmean%7D%29%5E2%20+%20...%20+%20%28x_n%20-%20%5Cbar%7Bx%7D_%5Ctext%7Bmean%7D%29%5E2%5Cnocache)

So, what does all of this mean? Let's start off with the concept of variance. 

![](http://mathurl.com/render.cgi?%5Ctext%7Bvariance%7D%20%3D%20sd%5E2%5Cnocache)

The standard deviation equation is actually derived from another equation, the equation of variance. A standard deviation is the square root of its corresponding variance, which explains why there is a square root in the formula.

![](http://mathurl.com/render.cgi?%5Ctext%7Bvariance%7D%20%3D%20%5Cfrac%7B%5Csum_%7Bi%7D%5E%7B%5Ctext%7Bn%7D%7D%20%28x_%7Bi%7D-%5Cbar%7Bx%7D_%5Ctext%7Bmean%7D%29%5E2%7D%7B%5Ctext%7Bn%7D%7D%5Cnocache)

In the above equation, we can see that the numerator of variance is the sum of the differences between each data value and the mean value, squared. Some values are ostensibly lower than the mean value, resulting in their differences with the mean being negative. Negative deviations will 'cancel out' the positive deviations and will not allow us to find the average deviation from the mean. So, we must square the numerator in order to obtain a valid sum.

The denominator is the number of data values we have, and we divide the numerator by the denominator to obtain the average variance. However, as we had squared the numerator earlier, we must take the square root of the variance in order to obtain the standard deviation, the measure of how far off, on average, each value is from the mean. 

From the descriptive standard deviation formula we had examined earlier, we can derive the computational formula, which allows us to calculate the standard deviation easily by hand. The derivation is shown below.

![](http://dsearls.org/courses/M120Concepts/ClassNotes/Statistics/Derivation.gif)
Source: http://dsearls.org/courses/M120Concepts/ClassNotes/Statistics/510B2_derivation.htm

(To obtain the version in the 'O' level formula sheet, take the square root of and divide each expression by n.)
