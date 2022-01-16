# UFOs
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, I will add table filters for the city, state, country, and shape.

## Overview of the Analysis

## Background:

Data is a data journalist who ois at a point in her career whwere she has the freedom to choose the topic she wants to write about. when she is given the opportunity to write 
about her hometown McMinnvillem Oregon, she jumps on the opportunity for a couple of reasons. First, its an opportunity to visit the memories and people back home, secondly its the fun part, is the topic, UFOs. McMinnville is famous for UFO sightings and even has an annual gathering for UFO enthusiasts. its a topic that DAna has been interested in since childhood, when she first heard about Farmer Trent's sighting in 1950. For this assignment the only thing she needs to go on so far is a JAvascript file filled with sighting information. Dana is aware of Javascript's visual functionality, its a tried and tested language after all.


![Capture](https://user-images.githubusercontent.com/23488019/149443901-05a27517-1e23-4b20-90fe-2037e9c344ab.PNG)


### Purpose
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape. Her plan is to first use JS to display the datas of the table. Because there is so much data, sifting through without any adjustments would be a big challenge. JS provides a way to manipulate data by adding filters. Its tricky to add more than 1 filter but Dana is upto the challenge. Additionally, since I will be posting her article online, Dana wants to put everything together in a tidy HTML page. Her article, the table of data to support the findings and easy to use filters to fine tune the results. Dana is looking forward to see her ideas come alive. Hence I will be helping her with her goals.
 
The final webpage can be accessed at the following link :
[UFO sightings](index.html)

### Goal :

Dana's goal is to create an interactive webpage that allows readers to parse the data around UFO sightings. So, she essentially needs to build two things: the webpage that will allow users to view the data (HTML) and a dynamic table that will present it (JavaScript). Dana wants to storyboard her website to have an idea of what her readers will see when they view the final product. Storyboarding is incredibly useful in determining the layout of a webpage.

### What I am Creating:

This new assignment consists of one technical analysis deliverable and a written report. 

- Deliverable 1: Filter UFO sightings on multiple criteria
- Deliverable 2: A written report on the UFO analysis (README.md)

### Tools Used :
  1. JavaScript - It is a well-established coding language that was designed to enhance HTML. It's the backbone of many popular visualization libraries, such as Plotly, and is often used to create custom dashboards. JavaScript also provides a high level of customization: the dashboards built to deliver visual data, such as maps or graphs, can be as simple or complex as needed.

2. HTML - 

3. Bootstrap - 


4. VS Code -


5. Data Driven Documents(D3) - Data-Driven Documents (D3 for short) is a JavaScript library that adds interactive functionality, such as when users click a button to filter a table. It works by "listening" for events, such as a button click, then reacts according to the code we've created. Dana thinks that she would like to filter by date, so she'll add code to create a date filter. We'll use a popular library, D3.js, to equip our website to "listen" for events, such as a user clicking a button. In our code, we're going to use D3 to handle an action from a user, such as a button click. This means that we'll add an actual button to our HTML page to filter the table. When the button is clicked, D3 will detect the click and react accordingly. Building out user-driven data visualizations is an essential part of the data visualization job.


## Procedure :

### 1. Storyboarding :

Dana also has a solid idea of how she wants her webpage to look, but it's easy to get lost in the details of building a webpage without a visual reference. A visual reference such as a storyboard will help Dana outline all of the elements she wants included, such as the article title, a summary, and the table itself. Then, when she begins creating JavaScript code to include the table, she'll know exactly which HTML components she'll be connecting to her table. A storyboard serves as a kind of blueprint for your site and helps with the transition from idea to finished product. It is like  a map of the webpage.

#### An unordered components of a webpage:

![data-11-2-4-1-unordered-components-of-a-webpage](https://user-images.githubusercontent.com/23488019/148822033-f6348ed4-df0d-410f-be7d-bfecfc6d85ed.png)



#### A storyboard of the website with components neatly organized:

![data-11-2-4-2-storyboard-of-the-website-with-components-neatly-organized](https://user-images.githubusercontent.com/23488019/148822037-c8378b65-2191-4561-bf11-8e8675db2c67.png)


This step is key for a couple of reasons. First, knowing how we want the webpage to look before building it will save us time later. Second, it helps us make sure we've captured everything we want displayed. Sometimes, seeing the map of the website helps us ensure that all the elements we want displayed are included.


### 2. Aligning the Code:

When we align our code, we're putting our plans into action, such as when we start transitioning our storyboard into a webpage. We'll start by building our components. The first one will be the table we generate with JavaScript. In VS Code, the first thing we're going to do is import the data. Then, declare a variable, tableData, using const. Next, we need to point our data to our HTML page. Specifically, we need to tell JavaScript what type of element the data will be displayed in. We already know that the data will be displayed in a table, so in our code editor we'll reference the tbody HTML tag using D3. D3 is a JavaScript library that produces sophisticated and highly dynamic graphics in an HTML webpage. It is often used by data professionals to create dashboards, or a collection of visual data (such as graphs and maps), for presentation.



### 3. File Structure :

Building a page that contains JavaScript will require Dana to link additional JavaScript files to the index.html file that she'll be working on later. This means keeping track of multiple things at once: an HTML file, JavaScript files, images (for customizing the webpage) and a CSS style sheet. Therefore, it's a good idea for Dana to establish a solid folder structure now instead of when she's elbow deep in creating her JavaScript functions.
Before we get too far along with our coding, we need to set up a file organization system for our repo. The end result of this project will be an HTML page or application, so we need to establish the proper folder structure accordingly. At a high level, here's what we'll do:

- 1. Create the index.html file.
- 2. Create a subfolder to hold the CSS file (style.css).
- 3. Create a subfolder for images.
- 4. Create a subfolder to hold JavaScript.

First, in the repo folder we established earlier ("UFOs"), create the index.html file. This file is the window to our work: the table and Dana's article summary (along with titles and filters) will all be displayed through this file. 

Next, create a subfolder in the repo folder named "static." This static folder will hold our static CSS file; this only means that it isn't being moved or altered externally. In VS code, right-click the menu and select "New Folder," and then name it "static."

Inside the static folder, create another subfolder named "css" to hold the style.css file. We'll customize our webpage using the style.css sheet.

The next subfolder we'll create is our "static" folder to hold whatever images we want to add to our website when it's time to customize it. Create the folder now and name it "images." But for now, move on to the next step—we'll add images later.

The third and final subfolder we'll create is one to hold our JavaScript. Name the folder "js" and move the data.js and app.jsfiles into it.
Establishing this folder structure is a best practice when creating webpages with JavaScript. It's important to keep things organized when creating a webpage using JavaScript components, as there are even more moving pieces than a static website. We'll be linking to images and a style sheet as well as JavaScript scripts. The organization presented here provides clearly designated spots to store the code we'll be working on, making it easier to locate them as we go.


## Results : 


### How to perform a Search - 



## Summary :

This website does a good job at providing useful information regarding UFOs. It is a great platform for people to get an indepth analysis of the UFO sightings, as well as filter their search results with multiple criterias.  

#### - Drawback -
However, there is scope for improvement like any other project. One of the major drawbacks of this website is the use of lowercase for city as well as state. The user is forced to enter a city or a state name in lower case only. Since using uppercase is the general norm for writing state names, the website shoul dprovide that flexibility. For example, if a user inputs 'OR' instead of 'or', the search filter will not display any results.

#### - Recommendations - 

1. One of the recommendations to further improve the website will be to provide a user the flexibility to choose any case, upper or lower to input the names of city or state or both. This can be achieved by applying the lower case function on the search value entered. 

2. Another recommendation can be the addition of a Filter button at the bottom of all the search fields. User can enter multiple search criteria values and click on the filter button to get the desired search results, in contrast to individually pressing enter after entering each criteria value. This will provide a more aesthetically sound webpage too.

3. A sorting feature can be a great addition to the website. When dealing with a large database, it is always a good practice to have sorting capability. The user will then get the flexibility to sort the desired results in ascending or descending order of occurence. The list can show the latest occurences on the top and the previous occurences in that order of preference.
