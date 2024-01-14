# En ce moment

**Répertoire francophone de “now pages”, ou pages “En ce moment”**

<https://encemoment.site/>

## Ajouter ma page “En ce moment”

L’ajout de ta page “En ce moment” dans la liste peut se faire via GitHub, ou par message à <a href="https://boitam.eu/@joachim">@joachim@boitam.eu</a> sur le web social ouvert (sur Mastodon, quoi).

### GitHub

Pour contribuer une nouvelle adresse, il faut créer un fichier dans `site/links`, par exemple <a href="https://github.com/joachimesque/en-ce-moment/new/main/site/links" rel="nofollow noopener noreferer">en suivant ce lien</a>. Ce fichier doit avoir un nom unique, je recommande le domaine ou sous-domaine du lien, et avoir pour extension `.md`.

Le contenu du fichier suivre la structure suivante :

```
---
emoji: <un emoji au choix>
couleur: <une nuance de couleur (1)>
adresse: <url de la page En ce moment>
titre: <titre de la page>
---
```

Par exemple :

```
---
emoji: 🪴
couleur: 200
adresse: https://blog.professeurjoachim.com/en-ce-moment
titre: En ce moment — le carnet de Joachim
---
```

Une fois ce fichier édité, il faut ouvrir une Pull Request, que je vérifierai puis mergerai. Évidemment, il n’est pas permis de modifier sans permission les fichiers d’autres sites que le sien.

#### Notes

1. La nuance de couleur se note en degrés, de `0` à `360`, en fonction de sa position sur la roue des couleurs. Pour trouver une nuance, l’outil <https://paletton.com> peut être utile (voir la valeur de `hue`).
