---
layout: post
title:  "You Peng Homework 8 for IS445"
date:   2024-03-31 14:10:54 -0500
---
Here is the `homework8` webpage.


<iframe src="https://youpeng0630.github.io/IS445/chart1.html" width="100%" height="600"></iframe>


`Write up for the first plot`

In this plot, I am trying to show the distribution of the lincense status. Y - axis is using quantitative to represent the number of licences. And the X-axis is using nominal encoding. This chart uses the default color scheme to represent the different bars, since the main focus is on the comparison of quantities. In this chart I have used the count() function to calculate the number of licenses under each "License Status". The results in this chart are essentially the same as in hw7. But the difference is that the previous left and right were using js, while this one is using altair in python. In this plot, I did not assgin an specfic color map, altair package will use it default color map. In this plot, the data tranform us mainly the count() function used to count the total number of same licence status. Data transform method is `to_datetime` and `dt.to_period('Y')` `dt.to_timestamp()` function. Then, I `used transform_filter` to create a interacitve dropdown menu to select the lincense status.




<iframe src="https://youpeng0630.github.io/IS445/chart2.html" width="120%" height="400"></iframe>


`Write up for the second plot`

This chart shows the trend in the number of licenses with "Not Renewed" status in the Fall 2022 license data by year.Y - axis is using quantitative to represent the number of licences. And the X-axis is using temporal encoding. The line graph method is used here to visualize this icon, and also compared to the previous assignment, I added drop-down menus to it that can be interacted with. The user can then choose to see how the corresponding license status is trending over the years.In this plot, I used the color='License Status:N' parameter in the encode function to assgin the colormap to it.

`Link for the first plot`
<a href="https://youpeng0630.github.io/IS445/chart1.html" class="btn">Plot1</a>

`Link for the second plot`
<a href="https://youpeng0630.github.io/IS445/chart2.html" class="btn">Plot2</a>

`Link for download ipynotebook analysis`
<a href="https://youpeng0630.github.io/IS445/IS445_Homework8.ipynb" class="btn">Download Notebook</a>

`Link for show ipynotebook analysis in git hub`
<a href="https://github.com/YouPeng0630/IS445/blob/main/IS445_Homework8.ipynb" class="btn">Analysis Notebook</a>

[jekyll-docs]: https://jekyllrb.com/docs/home


---
