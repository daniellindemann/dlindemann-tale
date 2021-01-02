# dlindemann-Tale

dlindemann-Tale is a minimal Jekyll theme curated for storytellers. It's based on and inspired by the original [Tale](https://chesterhow.github.io/tale/) theme by Chester How.

> For original configuration information check out the Tale repo: https://github.com/chesterhow/tale

## Features
- Easy installation
- Compatible with GitHub Pages
- Responsive design (looks just as good on mobile)
- Syntax highlighting, with the help of Pygments
- Markdown and HTML text formatting
- Pagination of posts
- [Disqus comments (can be enabled if needed)](#enabling-comments)

## Usage
Once you've installed the theme, you're ready to work on your Jekyll site. To start off, I would recommend updating `_config.yml` with your site's details.

To build and serve your site, run:

```bash
$ bundle exec jekyll serve
```

And you're all set! Head over to http://127.0.0.1:4000/ to see your site in action.

### Enabling Comments
Comments are disabled by default. To enable them, look for the following line in `_config.yml` and change `jekyll-tale` to your site's Disqus id.

```yml
disqus: jekyll-tale
```

Next, add `comments: true` to the YAML front matter of the posts which you would like to enable comments for.

## License
See [LICENSE](https://github.com/daniellindemann/dlindemann-tale/blob/master/LICENSE)
