*The tools and techniques for web development have changed a lot over the years. How will you personally try to keep up with those changes* *and where can you look to find them?*

Personally, I think one of the best ways to keep on top of changes like this is to find a reliable source. Then you can follow this source for all of your primary information pertaining to the field. For further enrichment, guide videos on YouTube are plentiful, along with forums Q/A. To stay on top means avoiding complacency. I believe that so long as I can manage that, through discipline and experience, then I should be okay. To stay ahead of the curve though, I can make sure to periodically check for experimental features and hot-topics. This way, when a new feature or technique is revealed, it won't be entirely new to me.

*The lecture and readings discussed the limitations of using floats for layout. What are some of these limitations? Provide an example.*

Floats were primarily used for layout prior to flexbox. Now that flexbox exists, floats are irrelevant in most scenarios. However, they do still have their uses. For example, creating a layout that has text-wrap around the float. With flex, this isn't possible, because the container has its own rules.So, if you'd like to place say, an image, within a large content of text; a float will most likely function better, especially on an offset. Floats because of this, can be very convenient to essentially nest within content, like a business card or the like.

*Flexbox is built to be language agnostic, so it uses generic terminology like the "Main" or "Cross" axis. Choose a flex property that* *affects one of these axes on a flex container and explain how it is used. Show how the result can change based on different flex* *directions and different writing modes.*

One property that is perfect for changing directions and writing modes, is ```flex-direction```. With it, you can change the direction of content on both axis via four different values.

These values are;
```
row (default)
row-reverse
column
column-reverse
```

So for example, Arabic is a left-right language. So, in order to change how the text is displayed from it's default, we can use the ```flex-direction``` property. Likewise, with some Asian languages such as Chinese, Japanese and Korean, they are traditionally written vertically. We can achieve vertical text for both top-bottom and bottom-top, by changing the ```flex-direction``` value. For traditional Japanese writing for example, we could use ```flex-direction: column``` for top-bottom text. If for some reason you need to display content bottom-top though, this is also available with ```flex-direction: column-reverse```.
