---
{"dg-publish":true,"permalink":"/ongoing-wishlist/","tags":["gardenEntry"],"dg-note-properties":{}}
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
        - note["dg-publish"] == true
    order:
      - file.name
      - Price
    sort:
      - property: Price
        direction: ASC
    image: note.image
    cardSize: 220
    imageFit: contain
  - type: table
    name: Table view
    order:
      - file.name
      - tags
      - Price
    sort:
      - property: Price
        direction: DESC
    rowHeight: medium

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
        - note["dg-publish"] == true
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
        - note["dg-publish"] == true
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
        - note["dg-publish"] == true
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
        - note["dg-publish"] == true
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

