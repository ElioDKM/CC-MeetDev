# CC MeetDev

## Le besoin et les choix
Le public visé est essentiellement des développeurs web. L'objectif est de donnée des informations sur des conférences. L'user doit pouvoir comprendre et retrouver facilement et rapidement les info importante et necessaire à ces conférence, tel que l'heure, le contenue, etc.

Les différentes section sont assez espacé afin de garder de la lisibilité, ça facilite aussi la navigation dans le site.

## La démarche

J'ai commencé par la structure html, pour les élément qui se répétait j'en faisais qu'un seul que je dupliquer une fois finis.
J'ai ensuite choisi les couleurs que j'ai ajouté dans un thème.
Pour l'application du style, je l'ai fais section par section, en commançant par le header jusqu'en bas de la page.

J'ai eu un peu du mal avec le responsive des cartes des conférences, pour trouver un affichage qui me convenait. J'ai tester differents utilisations de flex-box jusqu'a avoir la version actuel.

## Le lancement et les fichiers
**Commandes :**
```bash
npm install      # installer les dépendances
npm run build    # compiler le CSS
npm run dev      # ou : compiler automatiquement à chaque modification
```

## Les explications techniques
Expliquez la structure HTML et les ancres, l’emploi de Flexbox ou Grid, les points de rupture choisis et les changements entre téléphone et ordinateur. Choisissez deux courts extraits de votre propre code : indiquez leur fichier, expliquez les principales classes Tailwind et le résultat obtenu. Évitez les définitions génériques sans lien avec votre page.

Comme le contenu n'était pas énorme donc le breackpoint est assez bas, avec `sm:` surtout appliqué sur des taille de texte, ou pour le grid.

J'ai principalement utilisé du flex, de la gestion d'espacement (padding marging)
