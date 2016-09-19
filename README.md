# Documentation LPFP

**Envoyer une modification facile par Github**

* Aller dans le repertoire `source/includes`
* modifier le fichier `_exemple.md`
* ou modifier directement le `fichier.md` si vous etes sur de ce que vous faites
* envoyer les modifications soit avec
  - une pull request
  - à un fabmanager au lab ou sur Slack.

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

vous pouvez modifier dans votre editeur préférer les `fichiers.md` et voir en live dans votre navigateur les modifications, ou apres un refresh `F5`.
