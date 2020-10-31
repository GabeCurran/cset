In the next few weeks, we'll be learning how professional developers work on larger projects. What are you most looking forward to in this section?

I'm most looking forward to honing my skills and learning more skills of the trade. I still struggle a lot with the basics and am really hoping this will help me look for what I need to focus on. I'm also interested to see what kind of larger projects we'll learn about and what tools a professional developer would use on them, including more about frameworks hopefully. It's been a lot of fun so far and I can't wait to test myself with larger projects. Also, I'm hoping that I may actually perform better with more time. I get very stressed and anxious with time limits, so perhaps if the limit is longer, I won't be so tense.



Briefly explain event propagation and bubbling using an example of two nested HTML elements.

Event bubbling is essentially when you have an event occur within an element that is also inside of another element. Then, both of those elements will be reacting to the same event. For example, if I have a paragraph element with an event in it. And, this paragraph also happens to be located within a div element. Now, if say, an event goes off within paragraph element and the div is also looking for that event, like say an alert after a click. Then, the paragraph's event will alert us first and THEN the div's event will also alert us, propagating up the line.



You learned to use addEventListener on a DOM node to listen for a type of event and create a function to handle that event. When the event happens, that function is called with an Event Object that gives you more information about the event. Choose two different event types and explain two properties of each that are unique to that event. Use your MDN reference for help.

The keyboard events have three different types of attributes. It can look for "onkeydown", "onkeypress" and "onkeyup". "onkeypress" can be used to activate an event when a user hits a specified key or keys. "onkeyup" can be used when a user releases a key to activate an event. Both of these can be easily used with a switch in an event listener.
The mouse events have a lot of different attributes. Two big ones would be "onclick" and "onmousemove". We can use "onclick" to determine when a user clicks a specified element to activate an event. This is very useful and can be used with buttons, windows, etc. "onmousemove" is also very useful as we can use it to track a user's cursor. This can be used for many applications such as drawing applications.