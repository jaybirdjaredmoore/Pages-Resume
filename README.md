# Resume for Github Pages

## Design:
My intention was to use the include functionality to break out the site into descrete sections, rather than being their own pages. It makes the most sense to me to have everything all on one page, making the site feel close to an actual resume.

The nice benefit of this method is that the main page feels very "plug-n-play". All I need to do is include or remove the sections that aren't working and everything is self-contained.

## Takeaways
I'll be the first to admit that I'm not really utilizing Jekyll to it's fullest. A static site like this seems almost antithetical to the template format that it's built for. But this has been a nice experiment, and it's a good library to keep in mind for quickly getting a blog up and running.

It has also been nice to learn more about responsive web design. Flexbox and Grid are fantastic technologies that take out a lot of the headache and "magic numbering" in maintaining a layout that might be seen across variable screen sizes.

## Improvements:
### More Dynamic
There are two big improvements that could be made here. The first is to make the page more dynamic. It doesn't use much logic in how it displays elements.

### More Markdown
The second improvement is moving more of the content into external markdown pages. A lot of the text is embedded in the HTML and as a result it's not very extentable if I wanted to add more to any of my existing sections (or if I want to add any new sections).

### More Responsiveness (and less "Magic Numbering")
There's a lot that could still be added to make the pages more responsive. I'm not clamping anything, adapting the layout at specific window thresholds, and still using specific pixel values in (probably) too many places. That's a compromise I'm willing to make though in order to get the MPV out the door, especially for aspects that can be improved upon later.