# CoderHouse Staff & Alumni analysis

![base structure](Captures/png-clipart-power-bi-business-intelligence-microsoft-corporation-data-visualization-data-analysis-power-bi-dashboard-templates-thumbnail.png)

So... this was originally part of a **workshop**, CoderHouse gave us a sample of their own database and asked us to analyze the data with a couple of prompts. More than limiting myself to what they asked for, I saw this as an opportuny to explore **PowerBI** as a tool and refine my **Storytelling** skills (I was pretty excited about it after reading *Storytelling With Data* from Cole Nussbaumer).

I've created far more Metrics and KPI's than what they asked for, and I even ended up crossing data from outer sources with the original database to make a pretty good looking **map**! 

I hope this give you an idea of what kind of visualizations you could expect from me :)

Warning! - The visuals are in Spanish

## General Structure
Brand colors and icons were used to represent a for-and-from CoderHouse report. A simple but effective distribution of four light colored visual graphs on the center-right alongside selection indicators on the left and dark filters on the same column was used for an aesthetically pleasing report with no visual clutter (seriously, it was too much bright until I came up with the idea of the dark filters). Navigation icons were selected according to the aesthetic and thematic of the project.

![base structure](Captures/base_screenshot.png)

## Students tab
We were asked to analyze the amount of students open by different segments - Area, resgister month, daytime, etc. Four slots weren't enough, so I've overlapped two similar graphs together and added a bookmark selector to switch between them.
The bottom-left one was an idea of mine. it shows the amount of new students over time and compared it to the previous year. It was inspired on a CHURN graphic, I know it isn't the same, but I didn't enough data to perform one.

![enter image description here](Captures/students_screenshot2.png)

## Staff
As you may notice now, since the very first page the report assigns the sea green color to the students, and a bland blue to the staff. This page is made out of three graphs and a detail table, I must say, I'm not a fan of detail tables in the middle of a report, but we were asked for it.

![enter image description here](Captures/staff_screenshot.png)

## Map
And here It's when the fun begins - I had data about the location of the students in the database, but they were ZIP codes. That gave me two problems: First, It turns out that ZIP codes aren't unique; they can be shared across countries (I didn't know that lol), so PowerBI takes the data and places It with some sort of random order priority, It was a mess! And as a second problem, even if the ZIP codes were unique to each country, that would give me a map with a bubble in each Zip code, insead of the whole country, I had to do something about It!
