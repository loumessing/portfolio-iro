---
layout: post
title: BlocJams
feature-img: "img/blocjams-2.png"
thumbnail-path: "https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/2030966/blocjams_1x.png"
short-description: BlocJams for iOS is awesome!

---
{:.center}
![]({{ site.baseurl }}/img/blocjams-1.png)

{:.center}
##  Bloc-Jams - VanillaJS

{:.center}
### Summary

Bloc Jams is a digital music player project application built during the Bloc Front-End Web Developer course. It is made up of HTML, CSS, JavaScript and jQuery. For learning purposes, the first version of Bloc Jams was written with vanilla JavaScript and then re-factored into jQuery for the final version of the application.


### Objective

The main function of the Bloc Jams application is to display an album view and play music files. The project began with creating the landing page and a link to an album ‘collection’ view.

The album cover and title information were created dynamically by creating an album template using JavaScript in a function called `buildCollectionItemTemplate`

### Results

The final project would display the selected album and display song titles drawn from a small, local dataset. A toggle feature, that allowed users to toggle between three albums instead of just playing the default album was added. This resulted in a bit more depth and functionality.


{% highlight javascript %}

for (var i=0; i<12; i++){
var $newThumbnail = buildCollectionItemTemplate();
$collectionContainer.append($newThumbnail);
}

{% endhighlight %}
