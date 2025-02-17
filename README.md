# condoamanti.github.io
## Local Development
### Standard Serve
1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Beacuse Ruby 3.0+ does not contain webrick by default you will need to run `gem install webrick`
3. Clone down your fork `git clone https://github.com/yourusername/yourusername.github.io.git`
4. Serve the site and watch for markup/sass changes `jekyll serve`
5. View your website at http://127.0.0.1:4000/
6. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.
### Live Reload
1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Beacuse Ruby 3.0+ does not contain webrick by default you will need to run `gem install webrick`
3. Uninstall standard eventmachine gem with `gem uninstall eventmachine`
4. Install eventmachine gem with platform ruby with `gem install eventmachine --platform ruby`
5. Clone down your fork `git clone https://github.com/yourusername/yourusername.github.io.git`
6. Serve the site and watch for markup/sass changes `jekyll serve --livereload`

## Reference Documentation
I've created a more detailed walkthrough, [**Build A Blog With Jekyll And GitHub Pages**](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/) over at the Smashing Magazine website. Check it out if you'd like a more detailed walkthrough and some background on Jekyll. :metal:

It covers:

- A more detailed walkthrough of setting up your Jekyll blog
- Common issues that you might encounter while using Jekyll
- Importing from Wordpress, using your own domain name, and blogging in your favorite editor
- Theming in Jekyll, with Liquid templating examples
- A quick look at Jekyll 2.0’s new features, including Sass/Coffeescript support and Collections
