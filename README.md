# LSU DMAE Website

### Software Used
* Node
* next 15
* tailwind 4
* react 19
* react-dom 19
* react-share
* react-icons
* embla-carousel-react
* sharp (next js image doesn't style images statically)
* next mdx (and related plugins)
* gray-matter (to parse frontmatter from mdx and md posts)
* react-player (videos)
* image-size (dynamically figure out height and width)
* next-sitemap
* chokidar (json cache of all pages)


### Launch
* Develop on react server using `npm run dev`
* Render static site using `npm run build` and build to `out` folder  
* Run server to test site using`npm run start`.
* If images are added, removed or changed run `npm run build-images` before running build

### \<head\>
* Head of page is in `components | shared | seo.js`

### Social Media
* [LinkedIn Business: LSU DMAE | XR | Digital Twins](https://www.linkedin.com/company/lsu-dmae-xr-digital-twins)
* [LinkedIn Group: LSU DMAE | XR Studio | Digital Twin Studio](https://www.linkedin.com/groups/14687155/)
* LinkedIn Business & Group Admin Marc Aubanel, Jason Jamerson, Derick Ostrenko
* Do we want a shared LinkedIn | Facebook | Instagram account | X Account for the three groups?
* Do we want a landing page that directs to all three pages?
* Do we want to make a logo for all three?
* Do we want a tik tok site mirroring the youtube?
* Google YouTube at  @ dmaelsu@gmail.com pass: `lsu55555`
* Google Name: LSU DMAE - XR - Digital Twins

### To Do
* Add icon and favicon
* Add meta data description
* Add meta author
* Address code in main dmae site for dmc & lsu address?

### Size
* Max width of interior of page 1024px
* Padding left and right 10px
* 1200 × 675 for social image sizes in meta links

* ### Utilities
* [Tailwind Color Shades](https://javisperez.github.io/tailwindcolorshades/?supernova=FDD023&honey-flower=582C83&version=v3)
* [RGB to oklch](https://oklch.com/)
* [Hex to RGB Converter](https://www.rapidtables.com/convert/color/hex-to-rgb.html)
* [Unicode Symbols](https://symbl.cc)

### Validators
* [HTML](https://validator.w3.org)

### Tailwind Tips
#### Colors Number	Meaning
* 50	Lightest shade (very subtle)
* 100	Very light
* 200	Light
* 300	Soft
* 400	Base light
* 500	Base (default) color
* 600	Slightly darkened
* 700	Darker
* 800	Very dark
* 900	Darkest shade

#### Colors
* [Full Color Palette](https://tailwindcss.com/docs/customizing-colors#default-color-palette)

### HTML Tips

#### \<figure\>

Use \<figure\> when:
* You're displaying an image, illustration, video, chart, or diagram that relates to the surrounding content but is self-contained.
* You want to provide a caption for that media with \<figcaption\>.
* The content can be moved, referenced, or reused independently of the surrounding text.

#### \<header\> and \<nav\>
* Best practice to use a \<header\> tag with a \<nav\> inside
* Add an aria-label to \<nav\> of `<nav aria-label = "primary-navigation">...</nav>` especially if there are multiple nav menus (top, side footer ect...) for screen readers

#### \<main\>
* Add \<main\> around all \<sections\> tags

#### \<article\> \<section\>
>  Use \<article\> when the content:
* Can stand alone on its own.
* Could be syndicated or reused elsewhere (e.g., in RSS feeds).
* Has its own independent title, metadata (author, date), or byline.

> Use \<section\> when:
* You’re dividing a thematic part of a page or document.
*  The content is grouped logically, but not necessarily reusable outside the current context.
*  You’d give the section a heading, like a subsection of a page.

#### \<aside\>

> Use \<aside\> for a secondary portion in a web page
* Sidebars with links, bios, or widgets
* Callout boxes, tips, or related resources
* Pull quotes or highlighted info
* Contextual ads or promotional content
# EpicUnrealUprojectAssociations
