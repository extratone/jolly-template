# Jolly Template

A template for [Blot](https://blot.im), **minimal**, **light** and **fast**, made to display **easy-to-read** blog posts.

These are the files of the template that I called Jolly, after my own website **[The Jolly Teapot](https://thejollyteapot.com)**, on which this template is based. If you are a Blot user, you can directly access it using [this link](https://blot.im/settings/template/share/2b97e53f-3809-42f2-bd68-28c6d2294c4d).

### Good things about this template:
- **small footprint**: the CSS file is around 500b (uncompressed), and the uncompressed size of the homepage should be less than 5kb. (for 10 entries)
- it uses system fonts, no script, no nonsense.
- it has an **automatic dark mode**
- it should work just fine "out of the box.," except for the Header and Head part that needs to be updated (I indicated where via comments)

### Bad things about this template:
- it may not be the easiest to manage, so if you plan to tweak around and customise it a lot, you might discover that some things are not really "best practice."
- you will need to know your way around CSS and HTML if you plan to adapt the design to your likings (like the main font, the highlight colour, the spacing, etc.), or add things like comments, [webmentions](https://www.w3.org/TR/webmention/), or analytics.
- it is very minimal, so be warned: maybe try [other feature-rich templates](https://blot.im/templates).
- **Most of Blot optional services will not work with this template**: again, it will require direct HTML/CSS modifications to make some options works: this includes zoom on images, TeX support, etc.

### Notes:
- For the summary on the homepage, you will need to add a _summary_ metadata reference on your Blot entry.
- The mobile view is not set up in the CSS file: I find that it looks good enough as it is, but now you know.
- The _head_ metadata is not complete when it comes to [Open Graph](https://ogp.me), so you may want to check that on your side once it's installed. Same for the favicon parts, maybe good to double check on your end.
- On this template, the _search_, _tagged_, and _archive_ pages use the same code: if you want to remove the _tagged_ part, be sure to check the three pages.

Finally, if you see anything wrong with this template or one of its files, well, you know what to do.
