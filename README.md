# jekyll-libdoc

Thème distant Jekyll, générateur de documentation et compilateur SASS pour les composants ITADS.

# Usage local

1. Installer Jekyll sur votre machine en suivant les [instructions](https://jekyllrb.com/docs/)

2. Ajouter un Gemfile contenant la ligne suivante

  ```ruby
  gem "jekyll-remote-theme"
  ```
  et exécuter `bundle install` pour installer le plugin.

3. Ajouter les lignes suivantes dans votre fichier de configuration LibDoc `_<NOM DU FICHIER>.yml`

  ```yml
  remote_theme: ita-design-system/jekyll-libdoc
  plugins:
    - jekyll-remote-theme
  ```

4. Exécuter `jekyll build` ou `jekyll build -c _votre-fichier-config.yml`

