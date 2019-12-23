# Forty - Jekyll Theme

A Jekyll version of the "Forty" theme by [HTML5 UP](https://html5up.net/).  

![Forty Theme](assets/images/forty.jpg "Forty Theme")

# How to Use

For those unfamiliar with how Jekyll works, check out [jekyllrb.com](https://jekyllrb.com/) for all the details, 
or read up on just the basics of [front matter](https://jekyllrb.com/docs/frontmatter/), [writing posts](https://jekyllrb.com/docs/posts/), 
and [creating pages](https://jekyllrb.com/docs/pages/).

- **GitLab**: Simply fork this repository and start editing the `_config.yml` file!  
- **GitHub**: Fork this repository and create a branch named `gh-pages`, then start editing the `_config.yml` file.

# Added Features

* **[Formspree.io](https://formspree.io/) contact form integration** - just add your email to the `_config.yml` and it works!
* Use `_config.yml` to **set whether the homepage tiles should pull pages or posts**, as well as how many to display.
* Add your **social profiles** easily in `_config.yml`. Only social profiles buttons you enter in `config.yml` show up on the site footer!
* Set **featured images** in front matter.

# Issues

If you would like to report a bug, ask a question, request a feature, feel free to do so on [the GitLab repository](https://gitlab.com/andrewbanchich/forty-jekyll-theme) and I will be more than happy to help!

Alternatively, you can open an issue via email by emailing [incoming+andrewbanchich/forty-jekyll-theme@incoming.gitlab.com](mailto:incoming+andrewbanchich/forty-jekyll-theme@incoming.gitlab.com).

The GitHub repository is simply a mirror of the GitLab repository.

# Credits

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

# For Nathan Bacon ;)

* clone repo
* cd into forty-jekyll-theme
* bundle install
* bundle exec jekyll serve
* navigate to localhost:4000

* edit anything you'd like really. jekyll will generate a static version of whatever you're writing and compile it rather quickly. It compiles these files into the _SITE directory, so there's no reason to edit that directly. 

* You will have to manually refresh your browser to see what's going on and if you make changes to filenames, add files, or if you make changes to the _config.yml you will need to restart the server via 'ctrl-c' and bundle exec jekyll serve. It seems likely that bundle exec jekyll restart would work. I'm not 100 percent confiden in that.

* Anyway, you can edit the css in the main.scss found in the top-level /assets/css/main.scss

* The js will be found just under that /assets/js/custom.js

* The html files are a bit bizarre and I don't completely understand it myself, but you'll find that .md files are where you can edit most aspects of these html files and then their layout will be found in, of course, the _layouts.

* The most pertninet files for you will probably be 

* /_includes/header.html
* /_includes/footer.html
* /_includes/tiles.html
* /_layouts/aboutUs.html
* /_layouts/home.html
* /_layouts/testimonials.html
* /_layouts/aboutUs.html

* 0whatWeDo.md
* 1testimonials.md
* 2aboutUs.md
* 404.md

* and there's a lot of styles in elements.md that's already done.
You can see the results if you navigate to localhost:4000/elements.html


