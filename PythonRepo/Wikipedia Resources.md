# Wikipedia and Wikidata Resources
Brief introduction and collection of Wikipedia and wikidata resources.

## Wikidata
[Wikidata](https://github.com/dahlia/wikidata) client library for Python
This package provides easy APIs to use Wikidata for Python.

```python
>>> from wikidata.client import Client
>>> client = Client()  # doctest: +SKIP
>>> entity = client.get('Q20145', load=True)
>>> entity
<wikidata.entity.Entity Q20145 'IU'>
>>> entity.description
m'South Korean singer and actress'
>>> image_prop = client.get('P18')
>>> image = entity[image_prop]
>>> image
<wikidata.commonsmedia.File 'File:KBS "The Producers" press conference, 11 May 2015 10.jpg'>
>>> image.image_resolution
(820, 1122)
>>> image.image_url
'https://upload.wikimedia.org/wikipedia/commons/6/60/KBS_%22The_Producers%22_press_conference%2C_11_May_2015_10.jpg'
```

## Wikipedia Tools (for Humans)
Python and command-line MediaWiki access for Humans. 
[wptools](https://github.com/siznax/wptools)

- get page extracts, image, Infobox data, Wikidata, and more
- get a random page, category, or site
- get page statistics
- get category members
- get site info and stats
- get data in any language

This package is intended to make it as easy as possible to get data from MediaWiki instances, expose more Wikidata, and extend Wikimedia APIs just for kicks. 
