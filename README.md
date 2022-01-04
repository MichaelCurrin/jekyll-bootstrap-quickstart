# Jekyll Bootstrap Quickstart 🧪 🥾 🚀
> Starter template for using Jekyll 4 and the Bootstrap gem

<!-- Badges generated with https://github.com/MichaelCurrin/badge-generator -->

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/jekyll-gh-actions-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/jekyll-bootstrap-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Ruby](https://img.shields.io/badge/Ruby->=2.6-blue?logo=ruby&logoColor=white)](https://ruby-lang.org)
[![Made with Jekyll](https://img.shields.io/badge/Jekyll-4.2-blue?logo=jekyll&logoColor=white)](https://jekyllrb.com)


## Preview

<div align="center">
    <img src="/sample.png" alt="Sample screenshot" width="500" />
</div>


## About

This project includes the Bootstrap gem. So Bootstrap styling can be loaded as your CSS, without having to use NPM commands.

- [bootstrap](https://rubygems.org/gems/bootstrap) on RubyGems.
- [twbs/bootstrap-rubygem](https://github.com/twbs/bootstrap-rubygem) repo.


## How to use this template

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/jekyll-bootstrap-quickstart/generate)

</div>

If you want to deploy to GitHub Pages using GitHub Actions, see:

- [MichaelCurrin/jekyll-gh-actions-quickstart](https://github.com/MichaelCurrin/jekyll-gh-actions-quickstart)

Or, add a Netlify config and deploy to Netlify.


## Documentation

### Installation

Install Ruby and Bundler at the user level.

Clone the project or your copy of the template.

Install project dependencies:

```sh
$ make install
```

### Usage

Start dev server:

```sh
$ make serve
```

Open in the browser:

- http://localhost:4000/jekyll-bootstrap-quickstart/

Build:

```sh
$ make build
```


## How it works

- Bootstrap gem is installed using [Gemfile][/Gemfile].
- The [\_config.yml](/_config.yml) is set up to load SASS styling from gems. This extra work is because the gem was not made to be compatible with Jekyll.
- The [styles.scss](/assets/css/styles.scss) file is set up to load from the Bootstrap gem.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
