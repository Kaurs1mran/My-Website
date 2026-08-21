# My-Website 

Simran's Website is my personal website exploring who I am, where I'm from, and the history behind it.

**Live site:** https://kaurs1mran.github.io/My-Website/

## About

It started as a work in progress that I built over the course of several assignments.
The whole site is visually themed around Phulkari, a traditional style of Punjabi embroidery, bright, geometric, and made up of repeating diamond and floral patterns. I used it as the base for the color palette (pink, teal, blue, gold, deep red) and the diagonal striped borders you'll see across the site, since it felt like a more meaningful way to tie the design back to where I'm from, rather than just picking colors that looked nice.

The site includes a homepage with some of my current favorites, a full page on Punjab culture (food, dance, music, traditional clothing, festivals), and two history pages, one covering Sikhi's origins and early history, and another covering the Sikh Empire through independence and its more recent, heavier chapters.

I made the history pages especially in-depth because Sikh history genuinely isn't something a lot of people know much about, even though it's full of stories about courage, sacrifice, and resistance that deserve more attention. This was my attempt to make that information more accessible, well researched, and properly sourced, while still keeping it personal.

## Pages

- `index.html` – Homepage
- `culture.html` – Punjab Culture
- `history.html` – Sikh History
- `empire.html` – Empire to Independence

---
## Built With

- HTML
- CSS

---

## CSS & Section Styling Challenge Reflection

### What section did you focus on styling and why?
I styled the "Where I'm From" section since it was new, and I wanted it to
stand out a bit with its own background and rounded edges.

### How did Flexbox change the layout of your content?
The three items used to just stack on top of each other. After adding
flexbox, they lined up in a row instead, spaced out evenly.

### One CSS rule you feel confident about
Padding and border-radius, they were easy to get the hang of and the
effect was obvious right away.

### One CSS rule that was confusing at first
The gap property inside the flexbox container confused me a bit at
first, I wasn't sure how it was different from just adding margin to
each item, but once I saw it in action it made more sense.

---

## Advanced Selectors Challenge Reflection

### Which section did you focus on for advanced selectors?
I used my "Where I'm From" section since it already had a heading, paragraphs,
a list, and a link, which gave me enough content to style in different ways.

### Why are nested selectors more useful than global styling?
Global styles apply to every matching element on the page, even ones I didn't
intend to change. Nested selectors let me target elements based on where they
appear, so the same tag can look different depending on which section it's in.

### One selector that felt especially powerful?
The direct child selector, .roots-section > p, stood out to me. It let me
style the top-level paragraphs in my section while skipping a paragraph nested
inside a div, even though both elements were the same tag.

### One selector that took time to understand?
The difference between .roots-section p and .roots-section > p took some time
to fully understand. Once I saw that my nested paragraph only responded to one
of the two rules, the distinction made a lot more sense.

---

## Grid Layout Reflection

**When would you use grid instead of flexbox?**
I'd use grid when I need a two-dimensional layout, rows and columns
together, like a card layout. Flexbox feels more natural for things
in a single row or column, like a navigation bar.

**What was the hardest part of building your grid layout?**
Getting the breakpoints to feel right, figuring out at what screen
width the layout should actually switch from 3 to 2 to 1 column
without it looking cramped or too spaced out.

**How did media queries change your layout?**
Without them, the 3-column grid would stay squished together on
smaller screens. The media queries let the grid respond to the
screen size, dropping columns as things got narrower so each card
still has enough room to breathe.

---

## Peer Feedback & Self-Assessment 

I submitted my Module 8 post late, so I didn't get peer reviews in time. Per the assignment's fallback option, I self-assessed my site instead using what we covered in Ch 16.

I spent most of my time on content and research, especially for the history pages, and with more time I could have put more polish into the visual side of things too. I'm still working on cleaning things up and adding more documentation as I go.

**Issue #1: Inconsistent nav labels**
The nav linked to the same page but said "More" on some pages and "Sikh History" on others.
*Fix:* Updated the nav so it says "Sikh History" consistently across every page.

**Issue #2: Homepage felt cluttered**
The homepage had a lot stacked together (intro, dog photos, favorites grid, roots section) with no clear separation between them.
*Fix:* Added a divider line to break up the sections visually.

---

## Peer Feedback & What I Fixed

Ethan Prior reviewed my site and gave three suggestions, all tied to specific rubric items:

**1. Indentation inconsistency**
He noticed my HTML wasn't consistently indented across all 4 pages, and suggested running the formatter shortcut (Shift-Alt-F).
*Fix:* Ran the formatter on every HTML file to standardize indentation.

**2. File naming**
He pointed out that 3 of my pages were named generically (`index`, `page3`, `page4`) and suggested renaming them to something more descriptive.
*Fix:* Renamed `page3.html` and `page4.html` to `history.html` and `empire.html`, and updated every nav link to match.

**3. Image folder organization**
He suggested moving some of my extra images out of the flat `images` folder into subfolders.
*Fix:* Reorganized images into `images/homepage`, `images/culture`, and `images/history`, and updated every image path in the HTML to match.

---

## Credits

Favicon: Dagger emoji favicon by favicon.io, based on Twemoji, licensed under CC-BY 4.0.
https://favicon.io/emoji-favicons/dagger/

Festival photos on the Punjab Culture page are credited individually next to each image, sourced from Unsplash.

Sources for the history pages are linked throughout, with a dedicated Sources section on the Empire to Independence page for more recent history.
