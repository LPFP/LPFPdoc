# Jekyll

>Repertoire  
><a href="#">#</a>



## metre à jour avec GitHub

>Repertoire  
><a href="https://github.com/RobyRemzy/fabateliers/issues">https://github.com/RobyRemzy/fabateliers/issuses</a>

créer une issue sur GiHub,  
indiquer quelle fichier il faudrait modifier avec le code à rajouter.
<aside class="warning">
éviter de clicker sur l'icon `edit this file` et de modifier le fichier.
</aside>

### créer/modifier un fichier

>Exemple d'un objet en JSON

```json
{
	"name": "Android",
	"image": "350x350.png",
	"url": "https://github.com/LPFP/",
	"date": "30 Oct 2016",
	"tags": ["Android", "API","java"]
}
```

Section `data`
<aside class="notice">
Tous les champs doient être remplis.  
respecter le format `.json` avec chaque objet séparer par une virgule.  
ne pas metre de virgule à la fin du dernier élément.
</aside>

Pour editer un **Atellier**  
Aller dans le repertoire `data/projects.json`

Pour editer un **Materiel**  
Aller dans le repertoire `data/harware.json`

Pour editer une **Historique**  
Aller dans le repertoire `data/timeline.json`

>Aide aux commandes Git  
><a href="http://rogerdudler.github.io/git-guide/index.fr.html">http://rogerdudler.github.io/git-guide/index.fr.html</a>

## installer l'environement de developpement

```shell
# install ruby
sudo apt-get install ruby-full rubygems
```

```ruby
# metre à jour si besoin
gem update --system
# verifier que bundler est bien installer
gem install bundler
```

Ci-contre installer un environement de developpement `Ruby` sous Ubuntu  

* Pour installer Ruby sur Windows rdv sur la page    
[rubyinstaller](http://rubyinstaller.org/)  

* Pour installer Ruby sur OSX utiliser la commande  
[homebrew](https://www.ruby-lang.org/fr/documentation/installation/#homebrew)

Vérifier que `bundler` est bien présent et fonctionnel ainsi que `gem`

### installer les sources du projets avec la commande `bundler`.

```shell
# Forker le repertoire dans votre Github
git clone https://github.com/YOURUSERNAME/repo.git
cd repo
# installer le repertoire
bundler install
```

* Faire une copie local du repertoire.  

```ruby
# lancer le server local
bundle exec jekyll serve
```
>ouvrir votre navigateur à l'adresse  
><a href="http://127.0.0.1:4000">http://127.0.0.1:4000</a>

* lancer le server  
* éditer des fichiers et vérifier les modifications dans votre navigateur.

 Une fois votre édition complette vous pouvez la partager et faire une `Pull Requests`.
