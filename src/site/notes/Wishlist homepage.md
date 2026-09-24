---
{"dg-publish":true,"permalink":"/Wishlist homepage/","tags":["gardenEntry"],"dg-note-properties":{}}
---


```base
views:
  - type: cards
    name: Gallery view
    filters:
      and:
        - "!URL.isEmpty()"
    order:
      - file.name
      - Price
      - Notes
      - tags
    sort:
      - property: Price
        direction: DESC
    image: note.Image
    cardSize: 220
    imageFit: contain

```
