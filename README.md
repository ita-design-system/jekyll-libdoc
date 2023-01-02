# jekyll-libdoc
Thème remote Jekyll, générateur de documentation et compilateur SASS

# Installation

It is possible to only write your content without complete LibDoc installation, just use LibDoc as remote theme. You only need to use locally [Jekyll remote theme plugin](https://github.com/benbalter/jekyll-remote-theme)

1. Install Jekyll on your machine following the steps described [here](https://jekyllrb.com/docs/)
2. Add a Gemfile with the following line

  ```ruby
  gem "jekyll-remote-theme"
  ```
  and run `bundle install` to install the plugin

3. Add the following to your LibDoc's local config file `_config-local.yml`

  ```yml
  remote_theme: ita-design-system/jekyll-libdoc
  plugins:
    - jekyll-remote-theme
  ```

4. Run `jekyll build` or with any custom config file `jekyll build -c _your-own-config.yml`

