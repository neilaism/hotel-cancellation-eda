# Analysis of Cancellation Rate

## Introduction

Hi! Neila here. Before jumping into the long explanation, let me introduce myself a little bit. I'm currently transitioning into the data world — previously, I worked as an internal auditor. This project is part of my learning journey, and TL;DR: it’s definitely far from perfect.

So, why did I choose this dataset? Well, I’ve always had an interest in hotel-related things, and the Hotel Booking Demand dataset immediately caught my attention. I created a fictional business case around it and jumped in as a data analyst to try solving the problem.

## Repository Outline
This project's file consists:

    1. README.md - General overview
    2. analysis_project.ipynb - This notebook follows an analytical process using Python to identify and analyze the cancellation rate using the Kaggle Dataset (Hotel Booking Demand).


## Problem Background
A high cancellation rate in the hotel industry will affect their profit. To minimize it, we need to know its pattern and trend of this booking cancellation phenomenon, what is customer type that has highest cancellation rate, what is distribution channel that has highest/lowest cancellation rate, and the factors related to it. Once we understand all of these factors, we can choose the best approach to address it.

## Project Output
The output of this project is a dashboard that consists of charts and the result of statistic measurement.

## Data
Data used in this project is from Kaggle named Hotel Booking Demand dataset. This dataset has 119.390 rows and 32 columns. For this project, only 13 columns used for analytical process. They are `'hotel', 'is_canceled', 'customer_type', 'distribution_channel', 'is_repeated_guest', 'is_repeated_guest', 'lead_time', 'booking_changes', 'previous_cancellations', 'previous_bookings_not_canceled', 'adr', 'arrival_date_year', 'arrival_date_month', 'arrival_date_day_of_month'`. Those 13 columns don't have any missing values.

## Method
Statistic descriptive and statistic inferential are used in this project.

## Stacks

- Programming language: Python
- Tools: VSCode, Tableau, Canva
- Libraries: Pandas, Scipy, Matplotlib, Seaborn


## Reference
- Dashboard link:
    https://public.tableau.com/views/CancelRateAnalysisinCityHotelandResortHotel/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

- Presentation link:
    https://www.canva.com/design/DAGmxpQ8_XA/NJHpLqcv_DH2vtt7DcwKgw/edit?utm_content=DAGmxpQ8_XA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton


Disclaimer: Even though I mentioned it earlier in my intro, I'll say it again: this is my very first project since transitioning my career into Data Science, so there may be several imperfections. If you want to discuss or ask further information about the scripts/dashboard, you can contact me on email: neila.ismahunnisa@gmail.com or LinkedIn page: https://www.linkedin.com/in/neila-ismahunnisa/. Any suggestion and critics are welcome!