# Processing Penguins

Just a simple walk-thru using p5.js to explain why objects are useful.

p5.js is a Javascript implementation of Processing.

To see all the cool functionality (the API), go here: https://p5js.org/reference/

To see some really interesting examples, try: https://p5js.org/examples/

## Set up
1. You'll need a simple text editor. You do have a simple text editor don't you?
1. You'll need a browser. I KNOW you have a browser. I happen to like Chrome.
1. Create a working directory (folder) somewhere convenient. Call it "penguins"
1. Create a blank file with your text editor and save it into the /penguins directory as "penguins.html" (no quotes)
1. Create another blank file and save it to the same place as "penguins.js" (no quotes)
1. Copy the contents of [penguins.html](https://github.com/cgorton1313/penguins/blob/master/penguins.html) into your html file and save it.
1. Copy the contents of [penguins-01.js](https://github.com/cgorton1313/penguins/blob/master/penguins-01.js) into your js file and save it.
1. Go to your /penguins directory, open the penguins.html file.

You should have an extraordinary rectangle in your browser! (Trust me, it gets better...)

## What's going on?
Your browser is showing (rendering) the penguins.html. There's almost nothing in that file, but notice that we're including two scripts (Javascript files). The first is p5.js, which is the framework we're using. The second is penguins.js, which is the source code we'll be playing with.

You can close the html file in your text editor. Let's look at the js file. You can see just two functions, setup() and draw(). In Processing, setup() runs once at the start of execution, and draw continually loops at a default rate of 60 frames/second.

Guess what setup() is doing. Yup, it just creates your "canvas" which is your visual sandbox. For now, we'll specify the size in pixels, width then height.

How about draw()? It's setting the background color of the canvas. What are the three parameters we passed in? Now is a good time to become familiar with the API reference. Go to [this page](https://p5js.org/reference/), find background() and click on it to get to a page describing this function.

You can do a web search for "rgb color picker" and choose one you like. That might be helpful.

## What's next?
From here, your handy dandy instructor will guide you. Enjoy!
