# Documentation LPFP

Aller dans le repertoire `source/includes` et copier coller le contenu en syntax Markdown.
envoyer les modifications soit avec une pull request ou à un fabmanager au lab ou sur Slack.



**installation en local**

* installation de [Ruby RubyGems](http://rubygems.org/pages/download)

```shell
sudo apt-get install ruby-full rubygems
```

```ruby
gem update --system
gem install bundler
```

* Télécharger l'archive [içi](https://github.com/LPFP/LPFPdoc/archive/master.zip)

ou en ligne de commande depuis votre dossier:

```bash
git clone https://github.com/LPFP/LPFPdoc.git

cd LPFPdoc
```

```ruby
bundle install
bundle exec middleman server
```

ouvrir votre navigateur:

>http://localhost:4567
