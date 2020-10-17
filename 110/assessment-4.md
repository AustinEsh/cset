When creating platform specific UIs, there are many different aspects that you have to take into consideration. Technology is changing, and to keep up we must be able to adapt to, and accomodate, those changes.

The media feature that we've used the most is `width`. The `width` media feature represents the width of the viewport. You can also set a `min-width` or `max-width` to represent a range of screen-widths. For example:
```
@media (min-width: 650px) {
    /*styles for large screens*/
    ...
}
```
This would apply the styles for large screens when the viewport is 650px wide or wider. This is great for writing different styles for different screen sizes, and you can write different styles for any number of screen sizes.
Another media feature that I think is really cool, is `prefers-color-scheme`. This media feature is used to detect whether the user has specified on their system preferences to use `light` or `dark` mode. For example:
```
@media (prefer-color-scheme: dark) {
    /*styles for dark theme*/
}
```
This would apply the styles for the dark theme if the user has specified on their system preferences to use dark mode.

Is it better to define breakpoints using standard device sizes or using the specific content on my site? I think it is better to use specific content on the site, because device sizes vary so much that it's hard to determine the size range for each of the different types of devices. For example, a small tablet might even be smaller than a large phone. If you use specific content on your site to define the breakpoints, you're defining it by the screen-size that would best display your content instead of the type of device. I think this is a better method because it allows you to focus on what makes your site look the best possible, instead of focusing on making your site fit certain screen sizes.