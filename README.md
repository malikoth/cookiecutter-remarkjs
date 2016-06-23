# Cookiecutter remark.js
Cookiecutter template for remark.js presentations

See the [official remark.js website](http://remarkjs.com) for what's so cool about remark!

# Features
* Simple `index.html` file
* Separate `slides.css` and `slides.md` files for ease of editing
* Default styling in `slides.css` taken from the remark.js sample presentation
* Presentation configuration in cookiecutter setup

# Quickstart
1. Install the latest Cookiecutter
  * `pip install -U cookiecutter`
2. Create a presentation from _this_ Cookiecutter
  * `cookiecutter gh:malikoth/cookiecutter-remarkjs`
3. Edit content into `slides.md`.  See [the remark.js wiki](https://github.com/gnab/remark/wiki/Markdown) for help setting up your slides
4. Customize any css in `slides.css`
5. Serve your presentation over HTTP using one of the following methods (or others)
  1. Commit your presentation to the `gh-pages` branch of a Git repository and push it to GitHub
  2. Serve the presentation from your local harddrive with Python
    * `python -m SimpleHTTPServer` or
    * `python3 -m http.server`
6. Enjoy the applause after presenting your amazing talk

# Options
Option name | Description | Default
----------- | ----------- | -------
presentation_name | The name of your presentation.  This will also appear on the title slide | My Presentation
project_slug | The folder to store your presentation in | my-presentation
mermaid | Whether to link in Mermaid.js for pretty graphs or not | true
highlight_language | Default language for syntax highlighting | python
highlight_style | Default style for syntax highlighting | monokai
highlight_lines | Whether or not to highlight lines that start with an asterisk in code blocks | true
aspect_ratio | Aspect ratio for the presentation | 4:3
