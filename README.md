# Form-object-hilite
The demo database illustrates two ways you can add dynamic field higlighting to your databases. They are fast, lightweight and very easy because they work using 4D's On getting focus and On losing focus Form Events.  

### Version
<img src="https://user-images.githubusercontent.com/1725068/41266195-ddf767b2-6e30-11e8-9d6b-2adf6a9f57a5.png" width="32" height="32" />

## Background Object method
[![bg_object](http://img.youtube.com/vi/ZEekZqvzLBw/0.jpg)](http://www.youtube.com/watch?v=ZEekZqvzLBw "Background Object Demo")

This approach uses a single method. I use a rectangle object filled with white. The form fields are transparaent and the rectangle is moved behind the current object. 

## Background Picture method
[![hilite](http://img.youtube.com/vi/8ZSqCOsNCEE/0.jpg)](http://www.youtube.com/watch?v=8ZSqCOsNCEE "Hilite Demo")

This approach is only slightly more complicated. Imstead of a rectangle I use a picture variable. The variable is populated as it's moved using SVG. This offers a great deal of flexibility, as you can see. 

The demo requires v17 simply because I use dot notation in the methods. I provide the methods separately in the event you would like to back-grade them to work with an earlier version. 
