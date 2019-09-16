# p8105_hw1_ys3298

1.1 Create a data frame comprised of:

a random sample of size 8 from a standard Normal distribution
a logical vector indicating whether elements of the sample are greater than 0
a character vector of length 8
a factor vector of length 8, with 3 different factor “levels”

1.2 In a second code chunk:

convert the logical vector to numeric, and multiply the random sample by the result
convert the logical vector to a factor, and multiply the random sample by the result
convert the logical vector to a factor and then convert the result to numeric, and multiply the random sample by the result

2.1 
Create a data frame comprised of:
x: a random sample of size 500 from a standard Normal distribution
y: a random sample of size 500 from a standard Normal distribution
A logical vector indicating whether x + y > 1
A numeric vector created by coercing the above logical vector
A factor vector created by coercing the above logical vector

2.2
Write a short description of your vector using inline R code, including: * the size of the dataset (using nrow and ncol) * the mean, median, and standard deviation of x * the proportion of cases for which x + y > 1

2.3
Make a scatterplot of y vs x; color points using the logical variable (adding color = ... inside of aes in your ggplot code should help). Make a second and third scatterplot that color points using the numeric and factor variables, respectively, and comment on the color scales.

2.4
Export your first scatterplot to your project directory using ggsave.
