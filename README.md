# Introduction

Welcome to my personal website! My name is Luis Perez, and I'm a Technical Leader and Software Engineer/AI Researcher in the Bay Area, currently at Meta AI (previously at DeepMind and Google). These days, I'm teaching at North Carolina A&T, helping bring students from under-represented backgrounds into tech. I specialize in machine learning platforms, graph neural networks, and distributed systems. 

Credit to [academicpage](https://academicpages.github.io/) for the template used for this site.

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository setup for github pages.
2. Make sure you have ruby-dev, bundler, and nodejs installed. On linux, you can run
```sh
sudo apt install ruby-dev ruby-bundler nodejs
```
3. Run `bundle clean` to clean up the directory (no need to run `--force`)
4. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
5. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

### Tip: You should probably use `rbenv` or something similar to manage the dependencies required.

If on Mac, you can do this by first installing `rbenv` using Homebrew:

```sh
brew install rbenv ruby-build
```

Once installed, you can follow the steps to install `budler` (enables the `bundle` command seen above) to a project-specific version of Ruby.
```sh
# Ruby version to use.
rbenv install 3.1.2
rbenv rehash
# Only the first time, and follow output.
rbenv init

# Sets local version to 3.1.2 for project.
rbenv local 3.1.2

# Installs bundler to 3.1.2. 
gem install bundler
```

You can then follow the steps outlined above.

# Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch. 

To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.
