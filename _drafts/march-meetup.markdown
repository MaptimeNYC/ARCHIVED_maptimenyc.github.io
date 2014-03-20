---
layout: post
title: "March Meetup"
date: 2014-03-18 11:46:00
categories: maptime nyc events
---

Greet turn out for the March meetup at We Work!

###Things we talked about:

* [Pelias](https://github.com/mapzen/pelias)
* [Open Refine / Google Refine](http://is.gd/refine)

###Summary:

#### Presentation on Samsung's new geocoder Pelias
##### by John Crepezzi [@seejohnrun](https://twitter.com/seejohnrun)
* the name is Pelias: "The Search Based Reverse-Geocoder"
* it's open source & built on open data
* built autonomously from Samsung
* nice quote: "value is moving up the stack" by Ev Williams. As technology moves up the stack (becomes open-source) value becomes more important
* Pelias is built on open data: Quattroshapes (boundaries), Geonames (indexes with alternative names, including informal names), WOE (where on earth, yahoo, similar to genomes), OSM (poi data)
* technology: ElasticSearch, Redis, PostGIS
* communities: GitHub and GeoNYC
* 440 GB geo-index for the whole planetGeocoding (where's a thing?)
* reverse geocoding: what's at this location?
* address search
* POI search
* Feature search
* works really well in NYC! (because data is open and imported into OSM)
* Returns GeoJSON

####Google / Open Refine Demo
* see [Open Refine / Google Refine](http://is.gd/refine)
* we used NYC collision data from [NYPD.OpenScrape.com](http://nypd.openscrape.com/#/) and bike route data from [NYC DOT](http://www.nyc.gov/html/dot/html/about/datafeeds.shtml)
* crash data can be downloaded [here](http://nypd.openscrape.com/#/collisions.csv.gz)
* bike route data can be downloaded [here](http://www.nyc.gov/html/dot/downloads/misc/2013-nyc-bike-routes.zip)


####For Next Time
Let's find out how many cyclists were killed or injured in bike lanes using CartoDB (or some other way if you choose). Then you can riff on that data any way you'd like.