# Resume for Github Pages

Hello and welcome to my web-based resume! The page is powered by the Jeykll Ruby gem and hosted directly on Githuhb Pages. The design is all custom-made by me (Jaybird icon, included).

## Design Philosophy:
My intention was to use the include functionality to break out the site into descrete sections, rather than being their own pages. It makes the most sense to me to have everything all on one page, making the site feel close to an actual resume.

The nice benefit of this method is that the main page feels very "plug-n-play". All I need to do is include or remove the sections that aren't working and everything is self-contained.

## Takeaways
I'll be the first to admit that I'm not really utilizing Jekyll to it's fullest. A single-page site like this seems almost antithetical to the template format that it's built for. But I think I still managed to get it working for what I need.

It has also been nice to learn more about responsive web design. Flexbox and Grid are fantastic technologies that take out a lot of the headache and "magic numbering" in maintaining a layout that might be seen across variable screen sizes.

I only wish I was able to take more advantage of it. A lot of my effort was spent on developing a working style for the page, rather than exploring unique ways to utilize Jekyll and SCSS. I would like to make improvements to this as time goes on. Speaking of improvements...

## Improvements:
### More Dynamic
The first major improvement is to make the page more dynamic. It doesn't use much logic in how it displays elements. The only unique syntax are the includes into the main page. There is a lot of untapped potential here.

### More Markdown
The second improvement is moving more of the content into external markdown pages. A lot of the text is embedded in the HTML and as a result it's not very extentable if I wanted to add more to any of my existing sections (or if I want to add any new sections). As a result, it kind of defeats the advantages of the segmented nature of the design.

### More Responsiveness (and less "Magic Numbering")
There's a lot that could still be adjusted in the CSS to make the pages more responsive. I'm not clamping anything, adapting the layout at specific window thresholds, and still using specific pixel values in (probably) too many places. That's a compromise I'm willing to make though in order to get the MPV out the door, especially for aspects that can be improved upon later.