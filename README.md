terrarium
=========

**experimental extensible gis [early development]**

This is a very early stage idea I am fleshing out so take everything with a grain of salt. The basic concept is to build a lightweight GIS application that uses geojson as its primary vector format (but should also support imports from other formats, plus rendering of WMS/WFS).

##Main Features

- manage maps of geojson layers
- style layers based on the simplestyle-spec
- support for basic spatial transformations
- support for basic data processing (mostly aggregations of various types)
- community-oriented plugin system


##Dev

###Run

```sh
npm start
```

###Test

```sh
npm test
```