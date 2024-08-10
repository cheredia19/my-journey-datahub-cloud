---
title: 'My journey with DataHub Cloud'
description: 'A personal narrative of my evolution in publishing data stories on this innovative platform'
---

*By [César Heredia](https://x.com/cahered), data journalist*


My journey with DataHub Cloud began in April 2024 when Rufus Pollock contacted me through Upwork. My profile there says I'm a data journalist, so I think it clicked on him. At the time, I didn't know who Pollock was. When I Googled his name, I found out. 

I couldn't believe such an important person in the data world would contact this humble Venezuelan who uses data for journalistic purposes. Also, considering that Venezuela is not exactly known for its open data policies. *Au contraire*. It's hard to work with data in my country because of the lack of open and updated datasets. So, data people have to either build their data or look for datasets on foreign websites and NGOs.

But that's an issue we can assess in another opportunity.

When Rufus contacted me, I was honored but also intrigued. Then came the interview, and I learned about the DataHub platform. What I understood (at the time) was that a lot of the things I do with data could have been done within DataHub.

But then I discovered, with practice, that it wasn't as automatic a process as I initially thought. I still had to process data sets outside of the platform. So, I still relied on Excel/Google Spreadsheets and, if necessary, Python or R.

Then, something became a frustrating topic in my particular learning curve. My charts didn't show on the DataHub platform, even though I was doing everything right. It took around two weeks and a couple of video calls with a DataHub developer to figure it out.

Since then, my journey with DataHub has been *easy peasy*. 

I've done journalistic articles focused on several topics, such as [the 50 most followed YouTube channels](https://datahub.io/@cheredia19/50-yt-channels-most-subscribers), the [100 worst movies according to Rotten Tomatoes](https://datahub.io/@cheredia19/100-worst-movies-all-time-by-rt), [data analysis of the Paris Olympic Games](https://datahub.io/@cheredia19/paris-2024-osg-athletes), or [the state of press freedom in the world by 2024](https://datahub.io/@cheredia19/press-freedom-2024), among others.

I hope to keep having the opportunity to publish many more things on DataHub since it's a platform I enjoy using.

Two things I find great about DataHub, and I always like to emphasize, are the ease of use and version control through GitHub.

It is as easy as uploading all the datasets you need to a previously defined GitHub repository. In the same repository, there will be a README.md file in which you will be able to write the data story and put the components (charts) that will help illustrate your work, using markdown language.

The graphics can be found on the [PortalJS components guide website](https://storybook.portaljs.org/?path=/docs/components-introduction--docs). The available charts are:
 
- Catalog (with and without facets)
- Tabular
- IFrame
- PDF Viewer
- Line
- Bar (vertical)
- Vega
- Map

If you make a mistake, you can navigate through the GitHub version control and solve any issue. Also, you can edit any dataset or the README file and commit (save) the changes. It's *that* easy.

Although using DataHub is awesome for data purposes, I encountered some challenges I had to overcome while working with the platform. However, I understand this is perfectly normal when working on dynamic and incremental platforms.

For example, the FlatUITable component, ideal for tables, is designed to take the first column as the index column, which means the component will sort the data by the first column.

The detail is that sometimes we want to sort the data referencing to another column and not in ascending order as it is preset.

In this scenario, I discovered that you have two alternatives: set a first index column in your dataset or put as the first column the field you would like to sort the data with.

Another issue I found is that Spanish speakers like me usually separate decimals with a comma. If you work with comma-separated values in your dataset, it will corrupt the file. That's why it's so important to **use a dot instead of a comma** when working with numbers like English speakers naturally do. Besides, the system interprets the dot as the separator between integers and decimals, not the comma.


