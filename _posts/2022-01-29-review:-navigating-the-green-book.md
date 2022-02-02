## Project Details
Project:
_Navigating the Green Book_\
Project Director(s):
Brian Foo\
Project URL:
[https://publicdomain.nypl.org/greenbook-map/index.html](https://publicdomain.nypl.org/greenbook-map/index.html)

![Navigating the Green Book about page](https://toddmahood.com/images/ngb-about.jpeg)

## Summary
&nbsp;&nbsp;&nbsp;&nbsp;_Navigating the Green Book_ (NGB) is a digital humanities project that aids in the visualization of racial segregation, descrimination, and eventually the civil rights movement. The _Green Book_ series was created by Victor Green in a bid to protect black Americans as they traveled across the United States. It acted as a directory of locations where black men were safe and welcome to travel. NGB utilizes Mapbox, Scribe, Leaflet, and Open Street Map to analyze and plot the data contained in the _Green Books_. The result is an explorable map with routing functionality that allows the user to see geographically where black travelers could go and allows the user to plan a trip accordingly. By offering a new lens through which racial inequity can be viewed, Foo hopes users will critically examine their own lives and how they would be different if they were of another race.

## Map Exploration 
&nbsp;&nbsp;&nbsp;&nbsp;Upon first viewing the map, I noticed the lack of a legend and key. While the colors and icons present in the cluster map are fairly self explanatory, a key and legend would certainly enhance the usability of the map. I do, however, appreciate the numerical data included within the clusters. I think it helps the user to visualize where black Americans were more likely to travel. Admittedly, I was distracted by the individual location icons when the map was zoomed out. Instead I would reserve the rendering of icons for when the user begins to zoom in on a specific location. After further inspection, it also appears the icons (hotel, tavern, restaurant) lack alt text. This is crucial for those with visual impairments, so it is important that this is added in the future.

![Map of extracted data when first loaded](https://toddmahood.com/images/ngb-first-view.png)

&nbsp;&nbsp;&nbsp;&nbsp;I was also confused by the outlines that enwrap the clusters. Some of the outlines overlap other clusters and none of the outlines are similar in shape or size. Ultimately, I don't feel like they are necessary or important to the map exploration experience. I understand this could be a limitation of the map’s implementation, although I would definitely advise that it be removed if possible. 

![Outline covering two clusers on the map](https://toddmahood.com/images/ngb-outline.png)

&nbsp;&nbsp;&nbsp;&nbsp;I found it nice that clicking on some icons allowed the viewer to see the supporting documentation directly. I commend NGB for this, as it is important that you are able to do your own research as a user. As far as I could tell, NGB did an excellent job removing any locations that were mistakenly generated due to OCR mishaps. As I examined the website, I was unable to find a location that I couldn’t find reference to in the digitized versions of the _Green Book_.

![Mouse hovering over icon brings up corresponding green book page](https://toddmahood.com/images/ngb-supporting-doc.png)

&nbsp;&nbsp;&nbsp;&nbsp;Unfortunately, the website does not share the same appearance across all devices. On the majority of mobile devices, the top banner appears cut off and the bottom block of text describing the map is off center. The developer might solve this by implementing a mobile friendly framework.

![Image of map on an iPhone XR; the top banner is cut off and the bottom text box is off center](https://toddmahood.com/images/ngb-mobile.png)

Nonetheless, it does allow the viewer to clearly see the increase in locations that welcomed black travelers from the 1940’s to 1950’s. 

## Trip Planning 


## Conclusion
![Website map a trip button becomes unclickable after mistyped address and "x" button does not work](https://toddmahood.com/images/ngb-incorrect-address-x.gif)

![Plot of trip for an out of country address shows a jumbled up set of lines](https://toddmahood.com/images/ngb-out-of-us.png)




