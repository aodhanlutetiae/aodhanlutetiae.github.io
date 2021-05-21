---
title: 'Google Sheets walkthrough'
date: 2021-05-01
permalink: /posts/2021/05/blog-post-17/
tags:
  - spreadsheets
  - csv
  - getting started
---

How to get a CSV (comma separated values) file into a spreadsheet using Google Sheets and get working with it.

---

Download the following file to your computer: [bags_2years.csv](https://drive.google.com/file/d/15vDqg-u6W4tHouC42uvhMOdy21oTl3ov/view?usp=sharing)

Once the file is on your computer, right-click on it and under **Open With** choose **Text Edit (Mac)** or **WHAT(Windows)** to look at what's actually in the file. All the values are separated by commas:

> Year, Company name, Number of single use plastic bags issued, Gross proceeds of charge (£)

> 2018-19, A F Blakemore & Son Ltd,"5,114,183","255,709.15"

> 2018-19, Age UK Trading CIC,"563,644","28,182.20"

In your own Google Drive, open a new Sheet by clicking **+ New**, then **Google Sheets**, then **Blank Spreadsheet**

In the new Sheet, click on the name **Untitled Spreadsheet** on the top left and give your Sheet a name

Under File select **Import**, then **Upload**

Choose your **bags_2years.csv** file from your computer

If asked in a dialogue box about **Import Location**, select **Insert New Sheet** and for **Separator Type**, choose **Comma** or **Detect Automatically**

You should now have the CSV file in your Sheet:

<img src="/images/walkthroughs/wt1.png" alt="drawing" width="200"/>

**Organising your Sheet**

In the bottom left, there is a tab called **bags_2years**. Right click on the tab and select **Duplicate**. This will generate a new Sheet with a tab called **Copy of bags_2years**. Double click on this tab and rename it as **data**.

<img src="/images/walkthroughs/wt2.png" alt="drawing" width="200"/>

Add a new empty Sheet by using the **+** button just to the left of the tabs. Give this the name **Source** and somewhere in the sheet paste the following url, which is the where the data in your file was taken:

> https://data.gov.uk/dataset/682843a8-168c-4056-b6fe-741161a39f60/single-use-plastic-carrier-bags-charge-data-for-england
