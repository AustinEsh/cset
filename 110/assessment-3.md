How will I try to keep up with the changes of tools and techniques for web development, and where can I look to find those changes? One website that I could use is caniuse.com.
On this website, you can check if any feature is out-dated or unsupported by certain browsers.

What are some of the limitations of using floats for layout? One of the limitations of using float for layout, is that you kind of have to manually control that kind of layout
For example, if a float is larger that the block containing it, the float will simply overflow out of the parent block, and then you would have to manually change the size of the parent block. This would create a lot of extra work in a large site, because you would have to change the size of each parent block so that it contains the float.

`Justify-content` is the property that affects the `main` axis of a `flex-box`. It is used to determine the layout of the `flex-container`, and place the `flex-items`
accordingly. The main axis of the `flex-items` is determined by both the language that is being used on the site, and the `flex-direction`. The default `flex-direction` is
determined by the language being used. For example, if a site is using the English language, the default `flex-direction` would be left to right, and the rows would go top to
bottom, just like this text. In other languages, they might read left to right; in this case, the `flex-direction` would also be right to left. The same logic would be applied
to languages that read top to bottom. However, that is just the default `flex-direction`. You can also manually change the `flex-direction` using `row`, `column`, `row-reverse`,
and `column-reverse`. If the language used reads top to bottom, or the `flex-direction` is set to `column` or `reverse-column`, the main axis of the `flex-box` is vertical.
Otherwise, the main axis of the `flex-box` is horizontal.
