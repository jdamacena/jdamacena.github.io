+++
title = "Mars Rovers Pictures (App)"
date = "2022-08-07"
author = "Junior Damacena"
description = "Why I built an Android app to display the incredible photos taken by NASA's rovers on Mars."
showFullContent = false
+++

I'm an Android Developer and I love it, but building apps is not my only passion, one of my other interests is **Space Exploration**. I love how, in the face of such insurmountable problems scientists, engineers, and so many other people can work together to extend humanity's knowledge of our universe. And with that in mind, I was so happy when I found out that NASA provides an open API that allows anyone to access all of the incredible data they collect, not only data but also pictures and videos.

To demonstrate the potential of these APIs, I decided to create an app to display the wonderful photos NASA's rovers have taken on the Planet Mars!

You can see the source code of the app on [github](https://github.com/jdamacena/mars_rovers_pictures).

## NASA APIs

From the official [NASA APIs](https://api.nasa.gov/) website, anyone can register for an API Key and have access to all of their available APIs, of which they have a great variety. The available APIs include:

* [**APOD, the Astronomy Picture of the Day**](https://apod.nasa.gov/apod/astropix.html), that every day features a different picture or video about our cosmos with a good description;
* **NASA Image and Video Library**, an API to access the images and videos available at [images.nasa.gov](https://images.nasa.gov/#/)
* [**Mars Rover Photos**](https://github.com/chrisccerami/mars-photo-api), API that contains image data gathered by NASA's Curiosity, Opportunity, and Spirit rovers on Mars and makes it more easily available to developers, educators, and citizen scientists.
* Many others...

### The App

The app consists of a simple screen displaying tabs for the rovers and, inside each tab, a list of all the photos available for each Rover. When you select a picture from the list, a second screen opens and the image is displayed. It's nothing too fancy but it does the trick.

It is built using modern Android Development tools and practices. The tech stack includes Kotlin, Retrofit for APIs calls, the MVVM pattern, ViewBinding and LiveData, and the use of Android Jetpack's Navigation component. It also implements Swipe to Refresh.

You can find the open source code of the app on [github](https://github.com/jdamacena/mars_rovers_pictures), feel free to fork and extend it, it's a great resource! It'll also be available for download on the PlayStore and when I do that, I'll update this post with the link.

#### Conclusion

This project has been a great opportunity for me to bring together two things I like: making apps, about space, and in the process, I learned a lot about both. It also highlights the fact that you can turn basically anything into a project and get some valuable experience out of it.

Also, these NASA APIs are a great resource to know about, they can not only be the core of your next app but you can perhaps incorporate them on other projects not directly related to space and have some fun with it.
