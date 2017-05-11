# Changelog

> v1.1.1
 - Diverged from [fuegowlf](https://github.com/fuegowolf/cocoa-eh-hugo-theme)
 - Allow private folder in content to not be published.
 - Add 'projects' folder section to allow project posts to be organized and presented in dropdown.
 - Add coverimage in frontmatter for posts and sections
 - Included customCSS and customJS in config.toml
> v1.1.0

- Add more speed and asynchronous loading, of fonts especially
- Add more languages to `highlightjs` that are nowadays really used, like Rust, Go, Docker, Clojure, etc. ...
- Some fixes with some Pull Requests (thx to @davidskeck, @mtn and @maiki)

 - Add page/post ignore in config.toml to allow page to be rendered and not added to navigation bar
 - Theme migrate to use Bootstrap, allow better mobile view of navigation bar
 - Add googleAnalytics, value is set in config.toml
 - Add 'updates' to frontmatter. When a list is given in a post, the updates would show at the top of post.

> v1.0.0

- Change the set of fonts to **Nexa Bold, Raleway and Merriweather**.
- Add an optional navigation at the bottom of posts.
- Add the tags in the metadatas and add a template for tags pages.
- Add Google Analytics (thx @mtn)
- Add author informations on posts (thx @seemethere)
- Replace ionicons with svgs

> v0.9.0

- **Change the folder of high res images, now it's the root of the image folder.**
- Add a version to CSS to prevent bad caching
- Fix the images so absoluts paths are working even if the blog is in a subfolder

> v0.8.0

- Add a licensing page and a copyright in the footer if wanted (thx to [Hjdskes](https://github.com/Hjdskes))
- Fix footnotes
- Other small fixes

> v0.7.0

- Speed up a bit the theme
- Add twitter cards support
- Simplify the README
- Change the homepage to display latest and bests posts

> v0.6.0

- Add progressive loading of images
- Redesign image display
- Clean up a bit the example website

> v0.5.0

- Add an automatic way to add sections
- Add the possibility to add a header to a section list page
- Add an automatic way to add single pages
- Group blog articles by month and year
- Add a homepage with the possibility of adding a small text and few articles
- Update hightlightjs to v9.9.0
- Few deletions of obsolete lines

> v0.4.0

- Add logo and a title in header instead of only the author name
- Change pages from the navigation
- Delete useless icons from the bottom
- Change fonts and style the text (font size, justify ...)
- Improve mobile design by adding dates, removing grey background and adapt font

And more.

> v0.3.0

- Change color from orange to blue; improve colors elsewhere
- Change `div.section` to `section`
- Rename  `posts` directory to `blog`
- Add ability to specify extra CSS files in `config.toml`
- Removed `WebFontsFile` feature from `config.toml`
- Remove the initials displayed on top right of single post pages
- Update example site

> v0.2.0

* Added Disqus support. To enable Disqus, add `disqusshortname = "XYZ"` to `config.toml`. More details: <http://gohugo.io/extras/comments/>.
* In the posts list, replaced date with bullets at smaller screen widths.

> v0.1.0

* Initial release
