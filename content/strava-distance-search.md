Title: strava-distance-search
Date: 2020-01-28
Category: Projects
Authors: Alex Shovlin
Summary: Search for runs logged in Strava within a distance range.

[https://strava-distance-search.fly.dev/](https://strava-distance-search.fly.dev/)

[<i class="fa fa-github" aria-hidden="true"></i> Source on GitHub](https://github.com/ashovlin/strava-distance-search)

I use [Strava](http://strava.com) to track my running. Usually when I'm in the midst of a training plan I have a prescribed distance for each day. I have a few standbys from where I live for 3 mile, 5 mile, etc., distances but I tend to fall in a rut and repeat those over and over. 

Variety is nice but so is having some familiarity with the route (lest I risk running farther than what was intended, or not knowing where the nearest bathroom is).

I wanted to search for routes of the given distance that I've run before. I couldn't find a way to do this in Strava's UI short of sorting all activities by distance and scrolling through the list. 

Now you can specify a range of distances to view all your runs within that range:  
<img src="images/sds.gif" alt="Filtering runs" style="width:800px;"/>

*Built with Django, React, Bulma, and Leaflet (with [Stamen's free tiles](http://maps.stamen.com)), and hosted on Fly.io*