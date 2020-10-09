What are some of the limitations of using floats for layout? One of the limitations of using float for layout, is that it is much harder to control that kind of layout.
For example, if you want to center a float so that it goes in the middle of a page, you have to add a margin on each side, and calculate what those margins should be. If you
to have multiple floats that are evenly spaced in a row, it becomes much more complicated to space those floats out correctly. For example, if you want three floats to be spaced
evenly in a row, you need to check what percentage of the page each of those floats will take up, and then calculate what the margins should be for each of the floats. You have
to do a ton of manual work to create the right layout using floats, and you might need to make major changes in code for minor changes on the site.

`Justify-content` is the property that affects the `main` axis of a `flex-box`. It is used to determine the layout of the `flex-container`, and place the `flex-items`
accordingly. The main axis of the `flex-items` is determined by both the language that is being used on the site, and the `flex-direction`. The default `flex-direction` is
determined by the language being used. For example, if a site is using the English language, the default `flex-direction` would be left to right, and the rows would go top to
bottom, just like this text. In other languages, they might read left to right; in this case, the `flex-direction` would also be right to left. The same logic would be applied
to languages that read top to bottom. However, that is just the default `flex-direction`. You can also manually change the `flex-direction` using `row`, `column`, `row-reverse`,
and `column-reverse`. If the language used reads top to bottom, or the `flex-direction` is set to `column` or `reverse-column`, the main axis of the `flex-box` is vertical.
Otherwise, the main axis of the `flex-box` is horizontal.
