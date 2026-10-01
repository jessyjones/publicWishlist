---
{"dg-publish":true,"permalink":"/ongoing-wishlist/","tags":["gardenEntry"],"dg-note-properties":{}}
---




# Bienvenue sur ma wishlist 🎁

Comme on ne sait pas toujours quoi m’offrir (et que j’ai parfois des idées assez arrêtées sur ce que j’aime… et surtout sur ce que je n’aime pas 😅), j’ai créé cette petite wishlist pour vous donner quelques pistes !

J’y ai rassemblé des choses qui me feraient vraiment plaisir, classées par tranche de prix pour que chacun puisse trouver facilement quelque chose qui lui correspond. 

Évidemment, aucune obligation : quelque soit l'occasion qui vous mène ici, votre présence me fait sûrement déjà très plaisir

> [!abstract]- 💕 Petits coups de cœur : jusqu’à 10 €
> 
> ```base
> views:
>   - type: cards
>     name: Gallery view
>     filters:
>       and:
>         - "!URL.isEmpty()"
>         - Price < 10
>         - note["dg-publish"] == true
>     order:
>       - file.name
>       - Price
>       - tags
>     sort:
>       - property: Price
>         direction: ASC
>     image: note.image
>     cardSize: 220
>     imageFit: contain
> 
> ```

> [!success]- 🥰 Pour le kiff : 10€ à 20€
> ```base
> views:
>   - type: cards
>     name: Gallery view
>     filters:
>       and:
>         - "!URL.isEmpty()"
>         - Price >= 10
>         - Price < 20
>         - note["dg-publish"] == true
>     order:
>       - file.name
>       - Price
>       - tags
>     sort:
>       - property: Price
>         direction: ASC
>     image: note.image
>     cardSize: 220
>     imageFit: contain
> 
> ```

> [!tip]-  ✨ Gros coups de cœur : 20€ à 50€
> ```base
> views:
>   - type: cards
>     name: Gallery view
>     filters:
>       and:
>         - "!URL.isEmpty()"
>         - Price >= 20
>         - Price < 50
>         - note["dg-publish"] == true
>     order:
>       - file.name
>       - Price
>       - notes
>       - tags
>     sort:
>       - property: Price
>         direction: ASC
>     image: note.image
>     cardSize: 220
>     imageFit: contain
> 
> ```
> 

> [!example]-  🎀 Grandes envies : 50€ à 100 €
> ```base
> views:
>   - type: cards
>     name: Gallery view
>     filters:
>       and:
>         - "!URL.isEmpty()"
>         - Price >= 50
>         - Price < 100
>         - note["dg-publish"] == true
>     order:
>       - file.name
>       - Price
>       - notes
>       - tags
>     sort:
>       - property: Price
>         direction: ASC
>     image: note.image
>     cardSize: 220
>     imageFit: contain
> 
> ```
> 

> [!bug]- 💎 Grosses folies : 100€ et plus
> ```base
> views:
>   - type: cards
>     name: Gallery view
>     filters:
>       and:
>         - "!URL.isEmpty()"
>         - Price >= 100
>         - note["dg-publish"] == true
>     order:
>       - file.name
>       - Price
>       - notes
>       - tags
>     sort:
>       - property: Price
>         direction: ASC
>     image: note.image
>     cardSize: 220
>     imageFit: contain
> 
> ```
> 

> [!faq]- Option joker
> 
> Si vous avez trouvé un cadeau dans la liste qui me ferait vraiment plaisir mais qui est un peu trop cher pour une seule personne, vous pouvez aussi participer à la [cagnotte](https://www.onparticipe.fr/c/MUlKrYnJ) 🎁