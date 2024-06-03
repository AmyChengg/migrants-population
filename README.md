# Migration Hotspots: Where Filipinos, Chinese, Japanese and Vietnamese Settle in the United States
Data visualization on migration hotspots of where Filipinos, Chinese, Japanese and Vietnamese settled in the United States

**Team members:**
- Betty C.
- Amy C.
- Aaleah M.
- Ha Vi D.

**Observable Notebook**

[Click here to see our visualization!](https://observablehq.com/d/2822e82adfa94aba)

**Write-up**

**A rationale for our design decisions**

There were a few designs that were brought up such as spike plot and hexagon but we decided to choose a choropleth map. A spike plot won’t be the best visual representation in showing the number of immigrants per state because there would be too many clusters to differentiate. A hexagon plot won’t be able to help viewers to see the states and it would be difficult to understand the numbers based on colors. So, we chose to create a choropleth map, which is something that we were familiar with as it is an easy way for us to visualize states that immigrants tend to migrate to the most. 

The interaction technique we included is a tooltip which makes the map interactive. Viewers can intuitively navigate without instructions or confusion. Moreover, we implemented the mouse hover so that data for each state will appear. We ultimately chose mouse hover because we didn’t want all of the data to be shown which will make the map have too many numbers. This technique is useful and convenient for users because they can hover over each state to easily see the number of immigrants.

**An overview of our development process.**

Since there were 4 of us, we each chose a country to focus on (Japan, China, Philippines, Vietnam). Once we chose our countries, we found data on the population of immigrants of our country in each state. Then, we combined the number of immigrants from all 4 countries for each state and stored the data in a Google Sheet. However, importing the data sheet to Observable proved to be difficult. We tried different file types including csv and JSON, and figuring out the right JavaScript code to be able to display the data on the map. 


In total, we spent 7 hours developing our application. In the initial meeting, it took us time to plan out what we wanted to create and what type of data we wanted to focus on. In the beginning, we had difficulty in creating an interactive map that can show data when a mouse hover over each state. The mouse hover effect was not responsive and we reached out for help in office hours. It took us around 2 hours to figure out how to write the correct code to make the map interactive. The aspect that took the most time was using the numbers from the imported data sheet. The file parsing did not accurately capture the population numbers, but we figured out how to solve the issue after working 3 hours. What we realized was that we can implement a way to convert numbers to have commas! It was an eye opening milestone for us. There were bugs when coding the map at first because the data we imported was not connected to the map we created. Together, we debugged the code and were able to have the imported data be shown in the states. We figured out how to colorize the state maps because at first, it was just two specific colors. Then, we discussed the use of color on the map and tried out various colors that are conventional for viewers to understand the visualization. After some testing, we settled on using shades of purple for the states.
