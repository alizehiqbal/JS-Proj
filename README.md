# Health Tech Bubbles (Working Title)

## Background 

Health Tech Bubbles is a tool for visualizing trends in healthcare venture capital investment, whose growth has risen markedly since 2013 (with 2017 being a landmark year), with data abstracted from the Mattermark and Crunchbase APIs.  

Users will be able to see and click on bubbles that appear on the screen, commensurate in size to the magnitude of the deal. Lines between bubbles will indicate which companies have been funded by the same investor/group of investors. The color of the bubble will indicate, as per legend, the investment's relevant sub-field (e.g. genomics, synthetic biology, EHR, medical device, immunotherapies, etc.)

## Functionality and MVP

-Users will be able to click a bubble with the company's name and read a modal which holds information relating to the company's product, its most recent investment round, and the lead investor(s) of that round. 

-There will be a legend to the left of the screen which will indicate to users which segments (or sub-fields) of healthtech have garnered the greatest attention from investors. The color association will also help users inference which investors tend to invest in similar veins of research. Upon clicking each color in the legend, users will access a brief modal with a paragraph summarizing general trends for the respective segment/sub-field.

## Wireframe

This app will consist of a single page containing the visualization as well as a footer linking back to my github and a brief About section. The legend, as mentioned, will be toward the left.

## Architecture and Technologies 

This project will be implemented with the following technologies: 
-Vanilla Javascript for structure/logic
-D3.js for data abstraction and manipulation/design across the browser
-Mattermark API for data
-Crunchbase API for data
-Webpack to bundle up and serve my scripts 

## Implementation and Timeline 

### Over the Weekend 
  -Do Udemy course on D3.js
  -Review vanilla dom/jquery material (just for general re-familiarization with logic)
  -review logic of games like Asteroids 
  -review relevant MozillaDN documentation 
  -Determine APIs and relevant cross-sections 
 
### Day One 
  -Get webpack serving files, including index.html
  -Render a data point from my CrunchBase API to the canvas
  -Manipulate/style said data point 
  
### Day Two 
  -Garner relevant data objects and practice organizing it on the canvas
  
### Day Three 
  -Build out graphical representations of investments 
  -Determine relevant information for modals, and design modals 

### Day Four 
  -Style canvas according to color legend
  -Add modals for legend
  -Add lines linking bubbles by similar investors 


