# percent-vs-fixed-width-height
Brief insight to static and responsive webpages. When we run the html and css, we see two sets of two boxes/rectangles. The upper most box is static: their widths and heights are set in pixels. The lower most box is responsive i.e. width and heights set to relative units such as %, rem or em. 

Notice how at full screen, the top box width (800px) is longer than the bottom box(80% screen width).
However, as the screen width shrinks, the bottom box will adjust its width to equal 80% of your viewport width.
Notice the box width change as you shrink your viewport width.
The top box with the fixed value of 800px clearly is not dynamic and will not adjust based upon viewport width.
By defult, block level elements (like div) have a width of 100% of their parent and adjust automaticly to vp width.
When we set a hard value width, such as pixle, that responsiveness is lost.
