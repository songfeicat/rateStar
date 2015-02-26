# rateStar
Given five stars,rate something with these stars, while mouse is hovered on some star, stars before that one(included) will change color.

Main Knowledge:
	1. Difference between $(this) and e.target: $(this) refers to the element that is listening to the event, e.target is the actual(inner) element that event is working on.
	2. To convert e.target to jQuery object using $(e.target), then we can invoke all kinds of jQuery functions with this jQuery element.
