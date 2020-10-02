Pick your favorite CSS property so far. Explain what it's used for and all the potential values or units it can take. Why do you like it?


My favorite property has to be color! You can do so much with it and it just adds so much life to every web-page. It accepts colors in a few different values, such as RGB, Hexadecimal and keywords. With it, I can style different sections of a web-page with different colors. This allows you to create a visual sectioning for the reader and can have a great impact if colors are chosen properly. Also, with how many different colors CSS supports (16,777,216), there are so many possibilities. The keywords also make it really easy to pick a color sometimes, without looking up a specific hexadecimal for the shade you want.


Imagine you are making a website for a restaurant and you need to style the menu options to show that some are spicy or vegetarian or gluten-free. If all the menu options are using the same HTML elements, what CSS selector(s) could you use and why? Show an example.


One way to style an HTML menu with CSS could be to use ID and class selectors. If say, you have a section labeled "spicy" for the spicy menu. You could give the spicy section a class of "spicy". Then, you can specify the elements within this section regarding the class children. So for example,
```
#spicy > p {
    color: red;
}
```
would allow us to set any paragraph text within the spicy section of the menu to red!

We can also use basic font-size/font-weight properties to change the sizes and boldness of text for headings and the like. This can allow us to place emphasis on specific labels for entrees.

Style rules sometimes conflict with each other, especially in large projects. Explain the difference between cascade, inheritance, and specificity and how you can use these concepts to organize your CSS.


Cascade style rules are defined essentially by the order that they appear. CSS takes these rules and applies them from top to bottom, unless told otherwise. For example, if there is a specificity rule stating that <p> should have a color value of green, and this <p> tag is inside of a <section> element, then it is now specified as "Green" instead of whatever the section element was. Now, if that was not specified, then something else would be inherited. Say, the section element had a color value of black. If the p element within this section element has no other specifications regarding color, then it will Inherit the section's property value.
