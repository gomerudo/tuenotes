# Characteristics

Characteristcs are the functions we compute out from the population. The most popular are:

* Mean (Mu)
* Median (m)
* Standard deviation (σ)
* Variance (σ^2)

The first two are for location, since they refer to an specific point of the population. The latter are for variation of the data, since they are a mesure of how sparse the data is. For instance, a low standard deviation indicates that the data points tend to be close to the mean (also called the expected value) of the set, while a high standard deviation indicates that the data points are spread out over a wider range of values.


In this course we introduce:
* Skewness (y1): Measure of assymetry 
* Kurtosis (y2): Measure of peakdeness

These describe the shape of the distribution.

## Skewness

 - Negative: Thicker tail to left (data concentrated at the right)
 - Postive: Thicker tail to right (data concentrated at the left)
 - Zero: symmetric

So, skewness tell us in which side is our data is more concentrated.

## Kurtosis

More than peakdeness, it describes the tails. [Wikipedia](https://en.wikipedia.org/wiki/Kurtosis)

- Negative: Light or short tails  (not a dramatic jump from tails to peak).
- Postive: Long heavy tails and peacked (dramatic jump from tails to peak).
- Zero: as Normal Distribution.

## Relative standard deviation

It is also referred as the coefficient of variation. It says how much a population differs from the mean. It is sometimes prefered over the normal standard deviation.

RSD = StandardDeviation / Mean

It is believed that the relative standard deviation is constant over the range of values.

## Percentiles

The k-th percentile  is the value that divedes the sample in k% lower values and (100 -k)% higher values. This means, the percentile has values from k% or greater in one side and lower in th other side. An example of percentiles is the median: 50% percentile

The population percentile is denoteded as: F(p_k) = k / 100


Note that this assumes and ordered sample data. 

# Extra
## Brief recall of moments of a distribution

The 0th moment is the total probability (i.e. 1), the 1st moment is the mean, the 2nd central moment is the variance, the 3rd central moment is the skewness, and the 4th central moment (with normalization and shift) is the kurtosis.

For more details, click [here](http://www.statisticshowto.com/what-is-a-moment/)

## Notation
 - Hats(^) indicate estimated values from data. Example: û is the mean of the sample set. 





