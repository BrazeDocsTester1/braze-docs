---
nav_title: Understanding Your App Usage Data
page_order: 3
---
# Understanding Your App Usage Data

## Overview

The App Usage page on the dashboard provides key mobile metrics for you to track and understand the performance of your app and gives you an at-a-glance high level understanding of your app's userbase. Below are the definitions of these statistics, how we calculate them, and why they should be important to you.

![Dashboard Screenshot][1]

>  You can click "Show Breakdown" located on the right side of all of the rows of the dashboard statistics to view each statistic's value per day for the time period specified under the "Display Data For:" section.

![Expand][2]

## Lifetime Users

This is simply the total number of users that we have recorded using your app at any point in time. Below this number is the percentage of how many of your lifetime users are represented as Monthly Active Users which is useful for seeing user retention over a long period of time. A low MAU/Lifetime User ratio may indicate that you need to diversify your messaging channels or increase your efforts in reaching out to lapsing users. See our [Quick Win on capturing lapsing users][3] for more info. In general, the MAU to lifetime ratio will inevitably decrease over time due to user churn, but Braze's tools can help you minimize this effect by keeping users engaged longer.

## Lifetime Sessions

This is the total count of sessions that Braze has recorded since integration. Simply put, a session is each time a user uses the app. For a more precise definition on how sessions are defined by platform, please see [this page][4].

## Monthly Active Users

Monthly Active Users (or MAU) is the number of users that have recorded a session in your app in the last 30 days. MAU are calculated nightly with a rolling 30-day window. The percentage next to the MAU count will give you a comparison of today's MAU count to the MAU count recorded 31 days ago. MAU provides you with a good understanding of an app's health over an extended period of time as it smooths out the inconsistencies between days of varying usage intensity.

## Daily Active Users

Daily Active Users (or DAU) displays the number of unique users who record at least one session in your app on a given day. DAU can be a useful statistic for examining the day-to-day variability of usage of your app and tailoring your messaging campaigns to be as effective as possible. For example, your app's usage may see an appreciable spike on weekends - this would inform you that you could reach more users with in-app messages on these days as opposed to weekdays.

## New Users

New Users tells you how many users who have previously never recorded a session have started using your app. This number is a total of new users over the given time period. This statistic can be very valuable for tracking the effectiveness of your advertising efforts.

>  When you initially release your app with Braze, all users will look like new users since Braze has never recorded a session for them before.

## Stickiness

Your app's "Stickiness" value is a ratio of a given day's DAU to MAU. In essence, stickiness measures the percentage of your MAU that come back on a daily basis. For example, a ratio of 50% indicates that on average an active user is using the app for 15 out of 30 days or that about half of your active users come back on a daily basis. Stickiness is an important metric for app success because most users don't quit using an app because they actively hate it, but rather because it doesn't become a part of their daily routine. Therefore, you can use stickiness as a proxy for measuring how well you're engaging your users. Note that the MAU value is still calculated nightly and will not update until the next day.

## Daily Sessions

Daily Sessions is the number of sessions recorded on a given day. Comparing this value to your DAU count can inform you of how many times your users open the app on days where they record at least one session.

## Daily Sessions per MAU

Daily Sessions per MAU is the ratio of Daily Sessions to MAU on a given day. What this statistic can tell you is how many sessions per day you can expect to have logged per MAU. On aggregate, this can give you an idea of the relative frequency of when your users use your app. That is, if your Daily Sessions per MAU were on average 0.5, then you could expect each MAU to record a session about every 2 days.  

[1]: {% image_buster /assets/img_archive/Usage_Page.png %}
[2]: {% image_buster /assets/img_archive/Breakdown.png %}
[3]: {{ site.baseurl }}/user_guide/engagement_tools/campaigns/ideas_and_strategies/capturing_lapsing_users/#capturing-lapsing-users
[4]: {{ site.baseurl }}/help/faqs/
[5]: {% image_buster /assets/img_archive/retention_heatmap.png %}
