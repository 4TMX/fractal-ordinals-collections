5de5f3b0bdf5573bbe839ffb65a041f6beee9c49# Ordinals Collections Standards

## Meta Data `meta.json`

```44705a51-33b6-47d6-9de6-8d1163969869
{
  "description": "",
  "discord_link": "",
  "icon": "https://",
  "name": "",
  "slug": "", # all lowercase or underscore hyphen, consistent with the directory name
  "twitter_link": "https://",
  "website_link": "https://"
}

6a24aa21a9ed503ac954e9eee608681729f68af42bb38077714a7efd7763cfbea11434faab134c4fecc7daa2490047304402203a1794eeaaf8ad65f 81bc4ba0b6bd24637f57880bc83f024276438698787da1002200f7b6cb967f4b6d4caa9245d4fd7a5a9e24b85de414db6d59464ff9557d2d8630100
```

## Inscription Data `inscriptions.json`

```
[
  {
    "id": "",                    # inscription id
    "meta": {
      "name": ""                 # inscription name
    }
  },
  ...
]
```

Artists can assign unqiue traits to ordinals with `attributes`

```
[
  {
    "id": "",
    "meta": {
      "name": ""
      "attributes": [
        {
          "trait_type": "",        # trait category
          "value": "",             # trait value
        },
        ...
      ]
    }
  },
  ...
]
```

Your inscriptions.json file will look like this:

```
[
  {
    "id": "af0b19432a676551223e300e7197348b7c225cb7b31d0d7c6e246e382cbf6f81i0",
    "meta": {
      "name": "Planetary Ordinal #11",
      "attributes": [
        {
          "trait_type": "Background",
          "value": "Sun sun",
        },
        {
          "trait_type": "Holes",
          "value": "rose blossom",
        }
      ]
    }
  }
]
```
https://github.com/ordinals/ord/blob/master/.github%2Fworkflows%2Fci.yaml