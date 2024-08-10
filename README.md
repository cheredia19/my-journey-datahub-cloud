---
title: 'My journey with DataHub Cloud'
description: 'A personal narrative of my evolution in publishing data stories on this innovative platform'
---

*By [César Heredia](https://x.com/cahered), data journalist*

My journey with DataHub Cloud began in April 2024 when **Rufus Pollock** contacted me through Upwork. My profile there says I'm a data journalist, so I think it clicked on him. At the time, I didn't know who Pollock was. When I Googled his name, I found out. 

I couldn't believe such an important person in the open data world would contact this humble Venezuelan who uses data for journalistic purposes. Also, considering that Venezuela is not exactly known for its open data policies. *Au contraire*. It's hard to work with data in my country because of the lack of open and updated datasets. So, data people have to either build their data or look for datasets on foreign websites and NGOs.

But that's an issue we can assess in another opportunity.

When Rufus contacted me, I was honored but also intrigued. Then came the interview, and I learned about the DataHub platform. What I understood (at the time) was that a lot of the things people usually do with data could have been done within DataHub.

But then I discovered, with practice, that it wasn't a process as automatic as I initially thought. I still had to **clean** and **analyze** datasets outside of the platform. So, I still had to rely on Excel/Google Spreadsheets and, if necessary, Python or R.

Then, something became a frustrating topic in my particular learning curve. My charts weren't shown on the DataHub platform, even though I was doing everything right. It took around two weeks and a couple of video calls with a DataHub developer to figure it out.

Since then, my journey with DataHub has been *easy peasy*. 

I've done articles with a journalistic approach focused on several topics, such as [the 50 most followed YouTube channels](https://datahub.io/@cheredia19/50-yt-channels-most-subscribers), the [100 worst movies according to Rotten Tomatoes](https://datahub.io/@cheredia19/100-worst-movies-all-time-by-rt), [data analysis of the Paris Olympic Games](https://datahub.io/@cheredia19/paris-2024-osg-athletes), or [the state of press freedom in the world by 2024](https://datahub.io/@cheredia19/press-freedom-2024), among others.

## What I love about DataHub

Two things I find great about DataHub are the **ease of use** and **version control through GitHub**.

It's as easy as uploading all the datasets you need to a previously defined GitHub repository. In the same repository, there is a README.md file in which you can write the data story and put the components (charts) that will help illustrate your work using markdown language.

The graphics can be found on the [PortalJS components guide website](https://storybook.portaljs.org/?path=/docs/components-introduction--docs). The available charts are:
 
- Catalog (with and without facets).
- Tabular.
- IFrame.
- PDF Viewer.
- Line.
- Bar (vertical).
- Vega.
- Map.

If you make a mistake, you can navigate through the GitHub version control and solve any issue. Also, you can edit any dataset or the README file and commit (save) the changes. It's *that* easy.

## What I'd improve

Although using DataHub is awesome for data purposes, I encountered some challenges I had to overcome while working with the platform. However, I understand this is perfectly normal when working on dynamic and incremental platforms.

For example, the **FlatUITable** component, ideal for tables, is designed to take the first column as the index column, which means the component will sort the data by the first column.

The detail is that sometimes we want to sort the data referencing to another column and not in ascending order as it is preset.

Faced with this scenario, I found that I had two alternatives: set a first index column in your dataset or put the field I would like to sort the data by in the first column.

Another issue I found is that **Spanish speakers (like me) usually separate decimals with a comma**. If you work with comma-separated values in your dataset, it will corrupt the file. That's why it's so important to **use a dot instead of a comma** when working with numbers like English speakers naturally do. Besides, the system interprets the dot as the default separator between integers and decimals.

A similar thing happens with dates. DataHub uses the **DD/MM/YYYY** format instead of the **MM/DD/YYYY** Americans use. The thing is that many datasets come with the American format. I'm aware of this every time a dataset includes a date field.

An issue not related to data formatting comes when you update a dataset. It turns out that the DataHub Cloud doesn't show the updated values. How do I overcome this? I update **and rename** the dataset and then replace, on the README.md file, the name of the old dataset with the new one where it corresponds.

A thing it would be nice to improve is related to SEO formatting. When someone clicks on a link, it takes you out of the DataHub page and loads the new page. **It should open in a new tab**.

A component I haven't explored yet and I'm sure it will improve the quality of my reports is the [GeoJSON points map](https://storybook.portaljs.org/?path=/story/components-geospatial-map--geo-json-points). I expect to use it shortly. I will tell you later how my learning curve was with this type of chart.

## What's missing on DataHub?

For future developments of DataHub, I would like to use components that are not currently available like **horizontal bar charts**, line charts with more than one field (line, or y-axis), or **scatter plots**, to mention just three specific examples. The latter is ideal for graphic relationships between two numeric variables, e.g. the correlation between gross domestic product and life expectancy.

It would also be interesting to be able to format chart components in terms of color (at the moment it only shows blue), the thickness of the bar or line, and the possibility of incorporating features like a legend, a summary beyond the title of the chart or mentioning the source of the data in the footer.

## Summary

I see a great potential in the usage of DataHub for data lovers (like me). I'm proud of being able to use this innovative platform and to contribute to its growth, mainly because it means I also grow up as a data professional. I hope to keep having the opportunity to publish many more things on DataHub since it's a platform I enjoy using.
