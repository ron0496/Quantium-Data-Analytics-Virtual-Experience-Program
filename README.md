# Quantium-Data-Analytics-Virtual-Experience-Program

This repository contains results of the completed tasks for the Quantium Data Analytics Virtual Experience Program by [Forage](https://www.theforage.com/simulations/quantium/data-analytics-rqkb), designed to replicate life in the Retail Analytics and Strategy team at Quantium, using R or Python.

[Certificate of Completion](https://github.com/ron0496/Quantium-Data-Analytics-Virtual-Experience-Program/blob/main/certificate.pdf)

## Introduction:
Quantium is leading data science and AI Firm, founded in Australia in 2002 and offers a 17-year track record of innovation in data science. Quantium combines the best of human and artificial intelligence to power possibilities for individuals, organisations, and society.

Quantium has maintained a data collaboration with a prominent supermarket chain over the past several years, during which this supermarket has been providing transactional and customer data. Our team of employees work together to harness the power of data to drive revolutionary change that benefits us all and deliver the best results for our clients. As a data analyst at Quantium, your role involves delivering valuable data analytics and insights to assist the company in making strategic decisions.

Supermarkets routinely alter their store layouts, product offerings, pricing, and promotional strategies. They do this in order to meet the evolving needs and preferences of their customers, stay competitive in a dynamic market, or take advantage of emerging opportunities. The Quantium analytics team actively participates in these processes, assessing and analyzing the outcomes of these changes and offering recommendations regarding their success.

In this program you will learn key analytics skills such as:

* Data wrangling

* Data visualization

* Programming skills

* Statistics

* Critical thinking

* Commercial thinking

## Task 1

### [Data preparation and customer analytics](https://github.com/ron0496/Quantium-Data-Analytics-Virtual-Experience-Program/blob/main/Task1.pdf)

Conduct analysis on your client's transaction dataset and identify customer purchasing behaviours to generate insights and provide commercial recommendations.

#### Here is the background information on your task

You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region.

The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.

#### Here is your task

We need to present a strategic recommendation to Julia that is supported by data which she can then use for the upcoming category review however to do so we need to analyse the data to understand the current purchasing trends and behaviours. The client is particularly interested in customer segments and their chip purchasing behaviour. Consider what metrics would help describe the customers’ purchasing behaviour.

To get started, download the resource csv data files below and begin performing high level data checks such as:

* Creating and interpreting high level summaries of the data

* Finding outliers and removing these (if applicable)

* Checking data formats and correcting (if applicable)

You will also want to derive extra features such as pack size and brand name from the data and define metrics of interest to enable you to draw insights on who spends on chips and what drives spends for each customer segment. Remember our end goal is to form a strategy based on the findings to provide a clear recommendation to Julia the Category Manager so make sure your insights can have a commercial application.

LIFESTAGE: Customer attribute that identifies whether a customer has a family or not and what point in life they are at e.g. are their children in pre-school/primary/secondary school.

PREMIUM_CUSTOMER: Customer segmentation used to differentiate shoppers by the price point of products they buy and the types of products they buy. It is used to identify whether customers may spend more for quality or brand or whether they will purchase the cheapest options.

### Observations and Recommendations

* Sales have mainly been due to Budget - older families, Mainstream - young singles/couples, and Main-
stream - retirees shoppers. We found that the high spend in chips for mainstream young singles/couples
and retirees is due to there being more of them than other buyers.

* Mainstream, midage and young singles and couples are also more likely to pay more per packet of
chips. This is indicative of impulse buying behaviour.

* We’ve also found that Mainstream young singles and couples are 28% more likely to purchase KETTLE
chips compared to the rest of the population. The Category Manager may want to increase the
category’s performance by off-locating some KETTLE and smaller packs of chips in discretionary
space near segments where young singles and couples frequent more often to increase visibilty and
impulse behaviour.

## Task 2

### [Experimentation and uplift testing](https://github.com/ron0496/Quantium-Data-Analytics-Virtual-Experience-Program/blob/main/Task2.pdf)
Extend your analysis from Task 1 to help you identify benchmark stores that allow you to test the impact of the trial store layouts on customer sales.

#### Here is the background information on your task

You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, has asked us to test the impact of the new trial layouts with a data driven recommendation to whether or not the trial layout should be rolled out to all their stores.

#### Here is your task

Julia has asked us to evaluate the performance of a store trial which was performed in stores 77, 86 and 88.

To get started use the QVI_data dataset below or your output from task 1 and consider the monthly sales experience of each store.

This can be broken down by:

* total sales revenue

* total number of customers

* average number of transactions per customer

Create a measure to compare different control stores to each of the trial stores to do this write a function to reduce having to re-do the analysis for each trial store. Consider using Pearson correlations or a metric such as a magnitude distance e.g. 1- (Observed distance – minimum distance)/(Maximum distance – minimum distance) as a measure.

Once you have selected your control stores, compare each trial and control pair during the trial period. You want to test if total sales are significantly different in the trial period and if so, check if the driver of change is more purchasing customers or more purchases per customers etc.

### Observations and Recommendations

* Control stores 233, 155, and 237 were selected for trial stores 77, 86, and 88, respectively.

* Trial stores 77 and 88 showed significant differences in at least two out of three trial months, indicating a measurable impact.

* Trial store 86, however, did not show a significant increase in sales despite a noticeable rise in customer numbers.

* It’s recommended to consult the Category Manager to determine if any special promotions or discounts in trial store 86 may have affected sales figures by lowering prices.


## Task 3

### [Analytics and commercial application](https://github.com/ron0496/Quantium-Data-Analytics-Virtual-Experience-Program/blob/main/Report.pdf)

Use your analytics and insights from Task 1 and 2 to prepare a report for your client, the Category Manager.

#### Here is the background information on your task

Task 3 is targeted specifically at building your ability to recognise commercial, actionable insights from your analysis and displaying it in a clear and concise way for your client, with minimal jargon. At Quantium, our analyst graduates sometimes work as what we like to call "hybrids" (a mix of analyst and consultant duties) so developing your presentation skills early is a huge win!

As both technical tasks 1 and 2 were open ended in terms of insights, this model answer will focus on the layout and the order of your inclusions, including where to include graphs, taglines, written insights and recommendations.

As part of Quantium’s retail analytics team, you have been conducting a range of analysis on transaction and purchase behaviour data to provide key recommendations to your client, the Category Manager of chips, who is putting together their strategic plan.

#### Here is your task

With our project coming to an end its time for us to send a report to Julia, based on our analytics from the previous tasks. We want to provide her with insights and recommendations that she can use when developing the strategic plan for the next half year.

As best practice at Quantium, we like to use the "Pyramid Principles" framework when putting together a report for our clients. If you are not already familiar with this framework you can find quick introductions on by searching form them on the internet.

For this report, we need to include data visualisations, key callouts, insights as well as recommendations and/or next steps.

Keep in mind the key considerations for a presentation:

* Data literacy level of your audience

* Table of contents / agenda

* Problem statement / purpose

* Overview and context

* Content balance

* Layout and content display

* Summary / next steps
















