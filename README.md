# SamuelSaunders.github.io

A simple Jekyll based blog forked from the [Indigo Theme](https://github.com/sergiokopplin/indigo)

## Setup for Local Development

1. Install [Jekyll](http://jekyllrb.com), [NodeJS](https://nodejs.org/) and [Bundler](http://bundler.io/).
2. Run `bundle install`
3. Run `bundle exec jekyll serve --config _config.yml,_config-dev.yml`
4. Navigate to: `http://localhost:4000`
5. Test your app with `bundle exec htmlproofer ./_site`
6. Do you want to use the [jekyll-admin](https://jekyll.github.io/jekyll-admin/) plugin to edit your posts? Go to the admin panel: `http://localhost:4000/admin`. The admin panel will not work on GitHub Pages, [only locally](https://github.com/jekyll/jekyll-admin/issues/341#issuecomment-292739469).

## Customisation

`_config.yml` contains the customisation settings. 

---

[MIT](http://kopplin.mit-license.org/) License © Sérgio Kopplin
