---
summary: "Create a card interface with a toolbar of actions using <img srcset> and SVG icons."
time: "1.5 hours"
deliverables: "1 HTML file, 4 CSS files, images"
download: "https://assets.learntheweb.courses/web-dev-3/action-hero-card-with-actions-download.zip"
---

# Action hero card with actions

## Overview

- _Fork this repository._
- Export the icons from the Illustrator file as SVGs and use Spritebot to create a sprite sheet.
- Export the image from Photoshop twice, once for retina (`975px` wide) & once for non-retina images (`480px` wide).
- Create the responsive action card as shown in the screenshots.
- Use the `<img>` tag with the `srcset` & `sizes` attributes—for when it’s exactly the same image presented in different resolutions.
- Some of the HTML is already started, just a basic grid wrapper.
- Text can be found inside the `content.txt` file.
- _Run it through Markbot and make sure it passes all the checks._

---

## Details

- _Typefaces:_ `Mukta Mahee` (normal, bold) — **Already in the HTML**
- _Colours:_ `#fff`, `#000`, `#333`, `#555`, `#e2e2e2`
- _Button padding:_ `.3em`
- _SVG icon sizes:_ `.i-1` ([Sized based on type, not pixels](https://learntheweb.courses/topics/typografier-cheat-sheet/#icons))
- _Expected class names:_ `.action-card`, `.action-btn`, `.action-tools-top`, `.action-tools-bottom`
- _Expected image filenames:_ `icons.svg`, `blue-bolt-480.jpg`, `blue-bolt-975.jpg`

### Tags you haven’t used: `<menu>`

There’s an HTML tag that’s expected in this assignment that you’ve likely never used before: `<menu>`—it denotes a grouping of `<li>` tags that represent a toolbar of actions. It’s kinda like HTML’s fourth list type specifically for application toolbars.

_Use 2 `<menu>` tags: 1 to represent the top toolbar & 1 for the bottom toolbar._

---

## Goal

Visually match the images in the “screenshots” folder and create the interaction shown in the linked video.

- Final screenshots in the “screenshots” folder.
- [**Watch this video to see how it interacts.**](https://video-assets.learntheweb.courses/web-dev-3/action-hero-card-with-actions.mp4)

---

## Hand in

Drop this folder into your Markbot application. Make sure to fix all the errors. And submit for grades using Markbot.
