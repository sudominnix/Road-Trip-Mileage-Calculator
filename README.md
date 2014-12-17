Road Trip Mileage Calculator
==========

This is a simple web app that takes a few user inputs (origin city, car fuel type, car mileage, vacation category interest) and returns a list of suggested destinations with driving distance, time and fuel cost. 

Distance and time is calculated via Google's Distance API. Fuel cost is calculated from this data and from  up-to-date national price averages (via a parsed government XML feed, cleaned up through Yahoo's YQL).  

For the time being, you can see the demo at my Github hosted account URL: http://sudominnix.github.com

This is a work-in-process intended as an exercise in learning Javascript, screen scraping and basic API function. I may add other features in the future as well as refine some of the code, depending on what I come up with. Perhaps you might have use for this as a rough basis for a similar application or maybe you just need a few pieces of code (such as the XML parsing or Google Distance API connection) for something else.
