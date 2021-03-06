---
# Metadata Sample
# required metadata

title: Meeting queries in Workplace Analytics
description: When to use a meeting query and the type of data available for analysis in Workplace Analytics.  
author: madehmer
ms.author: rodonahu
ms.date: 07/16/2018
ms.topic: get-started-article
localization_priority: normal 
ms.prod: wpa
---

# Meeting queries

The Meeting query in Workplace Analytics gives you a list of all meetings that occurred during a specific period, along with their attributes.

## How to choose between a Meeting or Person query

Certain questions can be answered with either a meeting or person query.

 ![Meeting or Person query](../Images/WpA/Tutorials/person-or-meeting-query.png)

But for most questions you want to answer, the lines are more clear cut.

![Meeting query and Person query](../Images/WpA/Tutorials/meeting-or-person-query-2.png)

Use a meeting query when you want to understand the relationship between different meeting attributes.

Use a person query when you want to understand the relationship between a person’s organizational attributes – like their team, level, or location – and how they use their time, or when you want to know how one aspect of a person’s time use might influence another aspect of their time use.

## Create a meeting query

Setting up a meeting query is simple. Select whether you want the metrics for each meeting summarized by day, week, or month, and the time period you’d like to analyze.

If you want to exclude meetings from the calculations by using custom criteria, you can select your custom rule set or simply use the default.

 ![Create meeting query](../Images/WpA/Tutorials/create-meeting-query1.png)

By running this query with no exclusions, you will get an output file that can help you determine the right criteria to separate work-related activities from other calendar items.

 ![Meeting query no exclusions](../Images/WpA/Tutorials/meeting-no-exclusions.png)

## Add filters

You can add a filter to limit the list of meetings included in the output file. For example, the Meeting filter limits the query based on the size, duration, or other attributes related to meetings.

You can also limit the query based on organizer, attendee, and invitee attributes for meetings.

![Meeting query filter](../Images/WpA/Tutorials/meeting-filter.png)

## Add metrics

You can add base metrics to customize your meeting data. For example, select the Attendees metric to include the total number of people that attended meetings. You can add a metric filter to further customize the data. For example, the following metric filter will only show meetings that included attendees from the engineering group.

![Meeting query metric](../Images/WpA/Tutorials/meeting-metric.png)

To get more details on adding metric filters, see [Customize a metric](../Tutorials/customize-a-metric.md).
