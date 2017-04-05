# Project: My Responsive Blog #

## Problems with the Original Page ##

* The text is readable, but the images overflow the viewport.
* Page weight is massive: the images have been saved as JPEGs at low quality, but they're still too big.
* The headings, body text and images are not styled, making the post hard to read and dull to look at.
* The `<picture>` element allows browsers to decide which image to display based on media queries and device pixel ratios. Right now, the page is downloading images that are simply too big and waste too many bytes. How low can you get the page weight once the browser starts downloading images that are as small as possible?
* `alt` attributes make your sites accessible to the vision impaired and anyone surfing the web on a screen reader. Make sure to include them!
* The blog is visually simple. What can you do to make it look better?
* Getting text size right is hard. Is the body text too big or small on some devices and window sizes? Are the headings the right size relative to the body text?
* In GPRS emulation mode, this page still takes nearly a minute to load. Images load randomly – and the image captions load first and don't make sense without the images. How might image loading be accomplished more efficiently? Take a look at the [Resource Priorities](https://dvcs.w3.org/hg/webperf/raw-file/tip/specs/ResourcePriorities/Overview.html#attr-lazyload) editor's draft. What about JavaScript alternatives, such as the jQuery [Lazy Load Plugin](http://www.appelsiini.net/projects/lazyload)? Any potential problems?
* The markup is verbose! We've gone from around 7,000 characters to over 14,000. That's twice the download size – just to start displaying text. How could we improve this?
* Check the page with [Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fudacity.github.io%2Fresponsive-images%2Fproject%2Ffinal%2F&tab=mobile): the images are still unoptimized.


## The Goals and Features: ##

* Make the images fit in their containers in the viewport.
* Restrain the width of the blog.
* Drop the page weight.
* Replace all of the images with `<picture>` elements.
* Include `alt` attributes to be a better netizen.
* Add a custom font and try stying the text better.
* Use the picture element for art direction: different image crops are loaded, depending on viewport size.


## How to use it
* Make sure download all files in this project
* In Terminal:
	1. Make sure you switch to the directory `Project_Build_A_Portfolio/Responsive_Design_lessons_with_code/responsive_image_project` for this project
	2. Open index.html in your browser

## Author
[Yingtao Xu](https://github.com/MomokoXu)

## Copyright
This is a project for practicing skills in HTML/CSS course not for any business use. All pictures used are from internet and I do not own them. Please contact me if you think it violates your rights.




