# Understanding Benford's Law
Benford's Law is an observation about the frequency distribution of leading digits in many real-life sets of numerical data. The law states that in many naturally occurring collections of numbers, the leading significant digit is likely to be small. It follows the distribution according to the formula:

P(d) = log<sub>10</sub>(d+1) - log<sub>10</sub>(d) where d is a digit (0-9)

In [Experimenting with Benford's Law](https://github.com/vineettanna/Benfords-Law/blob/master/Experimenting%20with%20Benford's%20Law.ipynb), I write a function which tests if a series follows Benford's distribution using KS Statistics. Then I use this function to test if randomly generated numbers, their products or their products having a value > 0.1 follow Benford's Law

In [Testing Benford's Law on Financial Data](https://github.com/vineettanna/Benfords-Law/blob/master/Testing%20Benford's%20Law%20on%20Financial%20Data.ipynb), I write a function which tests if a series follows Benford's distribution using Chi Square Distribution. Then I use this function to test if financial numbers such as Total Assests, Total Revenue, Total Income and Net Operating Cash Outflow of US firms between 1995 and 2007 follow Benford's Distribution.
