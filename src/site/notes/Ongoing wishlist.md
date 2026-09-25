---
{"dg-publish":true,"permalink":"/Ongoing wishlist/","tags":["gardenEntry"],"dg-note-properties":{}}
---

# 0 - 10
```base
views:
  - type: cards
    name: Gallery view
    filters:
      and:
        - "!URL.isEmpty()"
        - Price < 10
    order:
      - file.name
      - Price
      - notes
      - tags
    sort:
      - property: Price
        direction: ASC
    image: note.image
    cardSize: 220
    imageFit: contain
```

# 10 - 20
```base
views:
  - type: cards
    name: Gallery view
    filters:
      and:
        - "!URL.isEmpty()"
        - Price >= 10
        - Price < 20
    order:
      - file.name
      - Price
      - notes
      - tags
    sort:
      - property: Price
        direction: ASC
    image: note.image
    cardSize: 220
    imageFit: contain

```

# 20 - 50
```base
views:
  - type: cards
    name: Gallery view
    filters:
      and:
        - "!URL.isEmpty()"
        - Price >= 20
        - Price < 50
    order:
      - file.name
      - Price
      - notes
      - tags
    sort:
      - property: Price
        direction: ASC
    image: note.image
    cardSize: 220
    imageFit: contain

```

# 50 - 100
```base
views:
  - type: cards
    name: Gallery view
    filters:
      and:
        - "!URL.isEmpty()"
        - Price >= 50
        - Price < 100
    order:
      - file.name
      - Price
      - notes
      - tags
    sort:
      - property: Price
        direction: ASC
    image: note.image
    cardSize: 220
    imageFit: contain

```


# 100+
```base
views:
  - type: cards
    name: Gallery view
    filters:
      and:
        - "!URL.isEmpty()"
        - Price >= 100
    order:
      - file.name
      - Price
      - notes
      - tags
    sort:
      - property: Price
        direction: ASC
    image: note.image
    cardSize: 220
    imageFit: contain

```

