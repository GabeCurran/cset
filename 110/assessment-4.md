We learned Web Development because it is a standard way to create user interfaces across platforms, but then we learned all of the non-standard aspects that we have to look out for. What does that tell you about building other platform specific user interfaces?

The truth is that, nothing is ever going to be 100% platform compatible. What I meant by that is, nothing will ever work pefectly on every single device. So, we have to know the ins and outs of non-stanard aspects so we can build websites with that in mind. The web-platform makes the content we create available to almost everyone, however, formatting it is a different story. We have to design the content to be scalable to viewports and different resolutions. We require multiple raster images for one icon or an svg to do so. Also, the website has to be optimized properly in order to run efficiently on all devices. If there is too much processing or bandwith requirement, not everyone will be able to load the page.



Show two examples of CSS Media Queries that use different Media Features. Explain how the user agent will decide to use those rulesets or not.

One example of a media query is the screen media query. This is used to determine how a device will interact with a webpage, based on its resolution/viewport. We can use this to set different CSS rules depending on the size of the screen, which lets us give entirely new layouts depending on the device while keeping the content the same. You can also specify it multiple times with different resolutions to match a variety of different screen sizes.

A second example is the print query. This allows us to display exactly, or almost exactly, what a page will look like once it has been printed. It's very useful because it gives the printer a ruleset to follow in order to not only avoid wasting copious amounts of ink, but also it can simplify the page and only prints what we need.



Do you think it is better to define Breakpoints using standard device sizes or using the specific content on your site? Why?

In this case, I would say a balance of both. We want our content to be made in a way that allows us to scale it based on different device layouts. However, most of this will still be actually done through CSS media queries. We can aim for a rough estimate for content, based on popular aspect ratios and potentially even a few popular resolutions, such as 1920 x 1080. However, we still need to be inclusive.