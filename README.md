# UFOs
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, I will add table filters for the city, state, country, and shape.


## Goal :

Dana's goal is to create an interactive webpage that allows readers to parse the data around UFO sightings. So, she essentially needs to build two things: the webpage that will allow users to view the data (HTML) and a dynamic table that will present it (JavaScript). Dana wants to storyboard her website to have an idea of what her readers will see when they view the final product. Storyboarding is incredibly useful in determining the layout of a webpage.

## Tools Used :
  1. VS Code
  2. 
## Procedure :

### 1. Storyboarding :

A storyboard serves as a kind of blueprint for your site and helps with the transition from idea to finished product. Think of it as a map of the webpage.

An unordered components of a webpage:

![data-11-2-4-1-unordered-components-of-a-webpage](https://user-images.githubusercontent.com/23488019/148822033-f6348ed4-df0d-410f-be7d-bfecfc6d85ed.png)



A storyboard of the website with components neatly organized:

![data-11-2-4-2-storyboard-of-the-website-with-components-neatly-organized](https://user-images.githubusercontent.com/23488019/148822037-c8378b65-2191-4561-bf11-8e8675db2c67.png)


This step is key for a couple of reasons. First, knowing how we want the webpage to look before building it will save us time later. Second, it helps us make sure we've captured everything we want displayed. Sometimes, seeing the map of the website helps us ensure that all the elements we want displayed are included.


### 2. Aligning the Code:

When we align our code, we're putting our plans into action, such as when we start transitioning our storyboard into a webpage. We'll start by building our components. The first one will be the table we generate with JavaScript. In VS Code, the first thing we're going to do is import the data. Then, declare a variable, tableData, using const. Next, we need to point our data to our HTML page. Specifically, we need to tell JavaScript what type of element the data will be displayed in. We already know that the data will be displayed in a table, so in our code editor we'll reference the tbody HTML tag using D3. D3 is a JavaScript library that produces sophisticated and highly dynamic graphics in an HTML webpage. It is often used by data professionals to create dashboards, or a collection of visual data (such as graphs and maps), for presentation.
