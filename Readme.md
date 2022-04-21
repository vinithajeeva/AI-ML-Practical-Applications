![](media/image1.jpeg){width="7.4875in"
height="9.9875in"}

**Module 5 -- Practical Application 1**

![](media/image2.png){width="3.783333333333333in"
height="0.481839457567804in"}

![](media/image3.png){width="2.3in"
height="0.4699518810148731in"}

# Table of Contents {#table-of-contents .TOC-Heading}

[**1.** **Import Libraries** 3](#import-libraries)

[**2.** **Data Loading and Validation** 3](#data-loading-and-validation)

[**3.** **Data Analysis and Visualization - Coupons**
6](#data-analysis-and-visualization---coupons)

[**4.** **Data Analysis and Visualization - Bar Coupon Acceptance**
7](#data-analysis-and-visualization---bar-coupon-acceptance)

[**5.** **Independent Analysis -- Coffee House Coupon Acceptance**
8](#independent-analysis-coffee-house-coupon-acceptance)

[**6.** **Correlation Analysis of Coffee House Data Frame**
11](#correlation-analysis-of-coffee-house-data-frame)

## **Import Libraries**

> The following python libraries are used in this practical application,
>
> ![](media/image4.png){width="6.5in"
> height="0.6833333333333333in"}

## **Data Loading and Validation**

-   Load the data from coupon.csv

> ![](media/image5.png){width="6.5in"
> height="0.24166666666666667in"}

-   Analyzed the data with head(), info(), and describe() to understand
    the data frame, data type, stats, and missing data.

> ![](media/image6.png){width="6.5in"
> height="1.8833333333333333in"}
>
> ![](media/image7.png){width="6.5in"
> height="3.7in"}
>
> ![](media/image8.png){width="6.5in"
> height="1.7166666666666666in"}

-   Converting data frame datatypes,

> ![](media/image9.png){width="6.5in"
> height="3.0833333333333335in"}

-   Since age is mostly numeric and shows as a string, the following
    logic is applied to convert to int64

> ![](media/image10.png){width="6.5in"
> height="0.425in"}

-   Checking for Null or NaN values

> ![](media/image11.png){width="6.5in"
> height="3.033333333333333in"}

-   Checking for any special characters

> ![](media/image12.png){width="6.5in"
> height="0.4666666666666667in"}

-   Renaming columns

![](media/image13.png){width="6.5in"
height="0.325in"}

-   Dropping column(s) and 'NaN' values

![](media/image14.png){width="6.5in"
height="1.1666666666666667in"}

## **Data Analysis and Visualization - Coupons**

> ![](media/image15.png){width="3.341666666666667in"
> height="2.5984962817147856in"}

In the entire data set, the coupon acceptance rate is higher than the
coupon not accepted.***\
\
***![](media/image16.png){width="6.5in"
height="3.439583333333333in"}

Coffee house coupons are more popular than other coupon categories.

## **Data Analysis and Visualization - Bar Coupon Acceptance**

> Here are some summary statistics of the acceptance rate of bar coupons
> among a few data points,

-   40.9% of drivers accepted a bar coupon

-   Drivers who go to bar 1-3 times accept more bar coupons than those
    who go to bar frequently

-   35.5% of drivers over age 25 who goes to a bar at least once a month
    will accept a bar coupon.

-   The probability of bar coupon acceptance among this group is higher
    than the younger counterparts (age less than 25)

-   Acceptance of bar coupons among those who frequent the bar by age,

> ![](media/image17.png){width="5.825in"
> height="2.944861111111111in"}
>
> The above chart confirms that younger drivers (under 25) go to bars
> more often than the other groups. But, when it comes to the bar coupon
> acceptance rate, driver of age over 25 tends to accept more bar
> coupons than their younger counterparts. Though the chart trend goes
> down between ages 30 and under 50, the trend picks back up with older
> people (over age 50) as they frequent bars and accept more bar
> coupons.

-   Though younger drivers tend to go to bars more often, only those who
    are between 26 and 27 ages tend to accept more bar coupons than all
    other groups. The bar-goers accept only about 18.9% of cheap
    restaurant coupons and an income below \$50K doesn't influence the
    acceptance of the cheap restaurant coupons.

## **Independent Analysis -- Coffee House Coupon Acceptance**

> Since Coffeehouse has the highest coupon count, I am choosing this
> group to understand the coupon acceptance rate.
>
> Here are the summary statistics of the coffee house coupon acceptance
> analysis,

-   There is a 49.8% likelihood that coffee house coupons will be
    accepted by drivers

-   Drivers who go to coffee houses 1-3 times accept more coffee house
    coupons than those who go to coffee houses frequently

-   Drivers who are above age 25 tend to accept more coffee house
    coupons than younger drivers

-   Analysis of coffee house coupon acceptance rate for those visited at
    least once a month and over age 25

> ![](media/image18.png){width="5.5441951006124235in"
> height="2.908333333333333in"}
>
> The above chart confirms that younger people (under 25 age) go to bars
> more often than people of age over 25. But the chart also sheds the
> light that the younger drivers accept more coffee house coupons than
> others. Though the coupon acceptance trend goes down as the population
> gets older, it trends back up with older people (over age 50) who
> frequent coffee houses and accepts more coffee house coupons.

-   Histogram charts to show coffee house coupon acceptance by Marital
    Status, Income, Education, and Gender

> ![](media/image19.png){width="5.308333333333334in"
> height="2.840184820647419in"}
>
> Single drivers accept more coffee house coupons followed by married
> partner drivers. Drivers with widowed marital status drivers visit and
> accept fewer coffee houses and coupons.
>
> ![](media/image20.png){width="5.551093613298337in"
> height="2.925in"}
>
> Drivers making income between less than \$12.5K and \$50K tend to
> accept more coffee house coupons. Those making income between \$51K
> and \$99K tend to accept fewer coffee house coupons. But, the trend
> switches back for those who make an income of \$100K or more to accept
> more coffee house coupons.
>
> ![](media/image21.png){width="5.316666666666666in"
> height="2.946887576552931in"}
>
> Drivers with no college degree accepted more coffee house coupons than
> others. People in high school tend to visit and accept fewer coffee
> houses and coupons.
>
> ![](media/image22.png){width="5.491404199475066in"
> height="2.9in"}
>
> Female drivers tend to go to coffee houses more than male drivers.
> Though the female drivers tend to reject more coffee house coupons,
> they still have a high coupon acceptance rate when compared to their
> male counterparts.

## **Correlation Analysis of Coffee House Data Frame**

> ![](media/image23.png){width="6.5in"
> height="2.2527777777777778in"}

![](media/image24.png){width="4.566666666666666in"
height="3.3728094925634298in"}

> There is a medium correlation between drivers\' age and children when
> it comes to the correlation analysis of the coffee house data.
