# Passenger

A narrative website for **Passenger** — the PRS Colonial Placement Division and its one-way voyages aboard the *Hermes* to Proxima Centauri. Built on a heavily customized fork of the ["Forty"](https://html5up.net/forty) Jekyll theme by [HTML5 UP](https://html5up.net/).

![Jekyll](assets/images/jekyll-logo.png "Jekyll")

## Pages

* **Home** (`index.html`) — landing page, mission teaser, and FAQs
* **Our Mission** (`mission.html`)
* **Our Crew** (`crew.html`)
* **Open Enrollment** (`player-guide.html`)

## Development

This is a standard Jekyll site. If you're new to Jekyll, see [jekyllrb.com](https://jekyllrb.com/) for the basics, or dig into [front matter](https://jekyllrb.com/docs/frontmatter/), [writing posts](https://jekyllrb.com/docs/posts/), and [creating pages](https://jekyllrb.com/docs/pages/).

```bash
bundle install
bundle exec jekyll serve
```

Site configuration (title, description, social links, homepage tile behavior) lives in `_config.yml`.

> NOTE: GitHub Actions is required to deploy to GitHub Pages, since GitHub [refuses to update their version of Jekyll](https://github.com/github/pages-gem/issues/651).

## Theme Features

Inherited from the underlying Forty Jekyll theme:

* **[Formspree.io](https://formspree.io/) contact form integration** — add your email to `_config.yml` and it works.
* `_config.yml` controls whether homepage tiles pull from pages or posts, and how many to display.
* Social profile links configurable in `_config.yml` — only the ones you fill in show up in the footer.
* Featured images settable via front matter.

## Credits

Jekyll port and "Forty" theme originally by [andrewbanchich](https://github.com/andrewbanchich/forty-jekyll-theme).

Original README from HTML5 UP:

```
Forty by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Forty, my latest and greatest addition to HTML5 UP and, per its incredibly
creative name, my 40th (woohoo)! It's built around a grid of "image tiles" that are
set up to smoothly transition to secondary landing pages (for which a separate page
template is provided), and includes a number of neat effects (check out the menu!),
extra features, and all the usual stuff you'd expect. Hope you dig it!

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		background-size polyfill (github.com/louisremi)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
```

Repository [Jekyll logo](https://github.com/jekyll/brand) icon licensed under a [Creative Commons Attribution 4.0 International License](http://choosealicense.com/licenses/cc-by-4.0/).
