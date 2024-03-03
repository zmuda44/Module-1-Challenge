Changed all divs to semantic elements for sections of the site.
Added comments to further separate code into sections for future coders.
The hero div was originally empty with no image, so I added the image.


If you insert an image into the hero class instead of using the background image with css the floats below will overlap it. Why is that?
I understand that images are inline elements.
I also understand that a div can sometimes take on different height and width than it's children elements

I consolidated code by making universal classes for similarly styled items and kept the original class as an id. I could've also used a space and gave each div 2 classes but figured id was preferrable.

The search-engine-optimization, online-reputation-management and social-media-marketing classes were below the benefits class in the css folder but above them in the HTML. I moved these to what seems like their proper spot and consolidated more classes. Instead of adding classes, I could've used .content div as a selector but chose to use classes.