---
title: Integrate Analytics with Commerce tutorial
description: Learn how to integrate Analytics with Commerce. 
solution: Analytics, Commerce 
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: yes
hidefromtoc: true
kt:
thumbnail:
last-substantial-update: 2023-04-11
badgeIntegration: label="Integration" type="positive"
---

# Integrate Analytics with Commerce

*   Verify that the account has access to Adobe Analytics.  

*   Create a project in Adobe Analytics.

*   Create a schema.  
    *   You need this to select from the options in later steps. To create a schema, Look in the left column under "Data Management" and find Schemas. Now on the top left, click "Create schema". Select XDM ExperienceEvent.
    *   On the left find Field groups, click Add
        * In the search, you can filter by entering `ExperienceEvent Commerce`
        * Look for `Adobe Analytics ExperienceEvent Commerce` and check the box
        * Be sure to click the `Add field groups` on the top right to save and continue
*   Create a dataset, you need this when your setup the "DataStream" next.
    * Dataset is found under the left column "Data Management" and looking for "Datasets".  
    * Then click "Create Dataset" found in the top right. You create the dataset from the schema.  
    * search and use the schema that you created earlier
*   Create Datastream. You can get to it by using the "Data Collection in the left column" and looking for "Datastreams".
*   Create tables with panels and segments. This is way to be complicated for this tutorial, you need an experienced Analytics person to assist.


Finally to view your report, you navigate to experience.adobe.com find your workspace project, click the link of the project you wish to view and you should see something like this image

![Analytics Screenshot of some commerce data](./assets/analytics-commerce/analytics-screenshot-commerce-items.png)