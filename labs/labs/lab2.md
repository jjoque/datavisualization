---
layout: default
title: Lab 2 - R and Tidyverse
parent: Labs
---
# Lab 2 - R and Tidyverse

In this lab we will start using R and Tidyverse to begin making data visualizations. We will quickly discover that most of the technical challenge of data visualization is not telling the software to make a graph but manipulating and cleaning our data. While each of the steps we are going to cover are relatively simple and straight forward, the challenge we face in working with ‘real world’ datasets is that knowing which steps to take and in which order is not so simple and requires we have a very good understanding of our data and what we want to do with it.

We will use Google Collab to work through the lab. [You can access the lab here.](https://colab.research.google.com/drive/1NoTDwOJi9g52YePIFBx6FYkbU_KTcA4M) In order to use it you will need to:

-	Go under File and select ‘save copy to drive’
-	Then go to your google drive and open your own copy
-	You can then run any of the cells by clicking the play button

We will complete this lab in two parts over two class sessions. The first session we will work through the examples together and then the second session will be time for you to work on the following ‘to do’ sections in the lab:

-	To do: Create a new graph where the x axis shows year instead of displacement
-	To do: make a bar chart showing the proportion of tested samples by poultry type
-	To do: make one more chart of your choosing with this data (perhaps graph the frequency of high risk serotypes, i.e. a line chart showing different serotypes over time after filtering for just high risk)
-	Technology track - to do: remake the bar chart by serotypes from above, but make the bars for high risk serotypes a different color than the others. Hint: remake the table so it includes the count by high_risk (they should all be the same for each serotype) and then set the color variable in the aesthetic to the high_risk column

To turn in your portion of the lab please create png files for each of the to do sections and then save your entire lab as a pdf (by selecting File -> Print and then saving as a pdf). To create the png files you use the png() and dev.off() commands as shown in the lab.

Additional Resources:
- Tidyverse book, which is very helpful: https://r4ds.had.co.nz/index.html
- Documentation for ggplot2 https://ggplot2.tidyverse.org/reference/

And, a few places for helping select nice colors:
- https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3
- https://ggplot2.tidyverse.org/reference/index.html
- https://sanzo-wada.dmbk.io/
