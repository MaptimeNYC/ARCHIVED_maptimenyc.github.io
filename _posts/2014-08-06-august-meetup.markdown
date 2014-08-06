---
layout: post
title: "August 5th Meetup"
date: 2014-08-6 13:00:00
categories: maptime nyc events
---
## Return of the Creature from Null Island
Hi! We didn't really document a lot of things this summer. Which is too bad since those were the Maptimes where we learned a bunch about time travel and stuff. ¯\_(ツ)_/¯ Sorry. 

We've been trying this cool new thing with our Maptime structure where we start the evening with a short introductory tutorial through a specific tool, followed by breakouts to work on other projects or continue with the tutorial.( Last week Andrew from CartoDB did one, and it was great). This week we were lucky to have [Derek Watkins](http://dwtkns.com/) doing a talk on [D3](http://d3js.org). Given how easily D3 lends itself to complexity, this talk was mostly going over how D3 works in general and how it handles geospatial data (with an aside into the difference between topoJSON and geoJSON). 

Some other projects that were discussed included: 

- Making a better subway shapefile. Basically, all New York GIS nerds seem to end up using the same subway shapefile made by Steve "Basically The Greatest Person In the NYC Open Data Community" Romulewski. In the shapefile, the subway lines tend to overlap in places where train lines run the same route. While that's spatially accurate, it's not great at showing all the different lines at once (which you probably want to know when you're, say, trying go get transit directions). So there's a group of people who want to work on this problem so we're not all re-rendering the same shapefile by hand. More soon, we hope!

- We had a problem that seems like it should be easy to solve but somehow totally blew our minds. Martin is an artist working on a project where he walks the perimeters of islands. He wants to also walk the longest and widest distances of islands. Figuring out the longest distance between two points in Manhattan shouldn't be complicated, right? How ahs this not already been StackExchanged? It hasn't. Toward the end of the evening we realized that a routing tool rather than weird PostGIS calculations, might be the easiest way to do this. 

## Resources

- Will add Derek's talk materials once they're online. 
- In the meantime here's a [really great D3 tutorial book](http://alignedleft.com/tutorials/d3) that Derek and JD recommended. 
- Also it's always useful to look at Mike "The Guy Who Created D3" Bostock's [example blocks](http://bl.ocks.org/mbostock).

**Even Moar D3 Tutorial Stuff**
And here are some resources from a July MaptimeSF that might be helpful. 

- [presentation](http://enjalot.github.io/intro-d3/maptime/)
- [d3 geo api tutorial](http://enjalot.github.io/intro-d3/maptime/geo/) (view source to see complete code)
- [sample data in topojson format](http://enjalot.github.io/intro-d3/maptime/data/)
- [general d3 stuff](http://enjalot.github.io/intro-d3/)