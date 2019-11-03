#google-homepage

Practicing my HTML/CSS skills
Practicing developer tools

From The Odin Project's [curriculum]
(http://www.theodinproject.com/courses/web-development-101/lessons/html-css)

Challenges faced:

Apps icon in the top left would not turn from grey to black upon hover
    Instead of relying on CSS, I used onmouseover and offmouseover in the img element's properties

Logo would not center upon changing to 'better' logo
    The solution was to nest the img in a figure container to protect it from outside font sizing (which threw it off in dev tools)
    
Lining up left and right items on header and footer
    The solution was to turn the left items on header and footer to inline-block. Then float:right worked as expected
    
Icons within searchbox
    Instead of rounding corners of the input="text", it was nested within a container which then had a solid border. Then nested
    icons within that.
