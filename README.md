# order-summary-component

The goal of this project was to replicate the order summary page as provided, including some hover states and responsive design elements. 

Problems I expected:

- Still not confident with how flex works
- Still spooked by media queries
- The less common positioning solutions need to be researched when I encounter them

Problems I didn't expect:

- Box shadows are pretty new for me so tinkering with those took some time to get a grasp of
- Some difficulty figuring out the requirements for general flex positioning with accuracy (e.g. parents needing height for vertical centering)
- Why did it take so long to figure out how to round the corners of that nested image?! /facepalm

So this project actually went pretty well! I'm getting used to inspecting my flex elements to figure out what is going wrong and where padding/margins are being applied. Getting used to when to look for a solution externally instead of smashing in random values/configurations. Getting much more used to how media queries work, which were so spoopy before. 

Some standout moments during this project:

- Initially had the header image as an html element within the parent div, but all attempts to round the corners were failing. It took me hours before I finally rabbit-holed my way to a solution via background-image. And once I remembered that was a thing it was pretty easy to figure out how to apply the correct attributes to get that working along with the border-radius to round the corners properly. 

- Figuring out that margin should be used within flex layouts instead of justify-item to move a single element to the left/right of the page. That one was tricky and made me realize how little I know about margin and how flex uses free space. 

Well, that went okay--onto the next project. Thanks for reading along!