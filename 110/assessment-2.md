What is my favorite CSS property so far, and why? My favorite property so far is probably the `background` property. The reason I like the `background` property, is that the
background can really change the style of a webpage. You can set it to a color or an image. If it is an image, you can have it scroll down with all the other content on the page
or stay fixed. You can also set different backgrounds to different sections of the page, which is why I think it can basically set the style for a webpage.

If I was making a website for a restaurant and needed to style the meny options to show if they are spicy, vegetarian, or gluten-free, what CSS selector(s) could I use? I would
definitely use the `class` selector. If you need to organize multiple items into a certain group, the best way is to classify them, and then edit everything in that class. If
it were specified on the menu whether items were spicy, vegetarian, or gluten-free, you would be able to use the `attribute` selector to figure out whether an item belongs to a
certain group or class without adding it to the class manually.
If you were using a class, you would write in the HTML code:
```
<tag class='spicy'>menu item</tag>
```
Then you would write in the CSS code:
```
.spicy {
  properties
}
```
If you were able to use an attribute instead of a class, you could write in the HTML code:
```
<tag>menu item that is spicy</tag>
```
Then you could write in the CSS code:
```
[tag=*'spicy']
```

What is the difference between cascade, inheritance, and specificity, and how con you use these concepts to organize your CSS? In CSS, if two style rules conflict with each
other, the rule with the highest specificity is the one that is applied. For example, ID selectors are more specific than class selectors, and class selectors are more specific
than element selectors. If two style rules conflict and they have the same selector specificity, the rule that is written lower in the code is applied. Inheritence is when a
child element inherits an attribute from its parent element. An inherited attribute is basically just the default attribute for the child element, and can be overwritten by any
selector.
