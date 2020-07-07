---
description: The coach marketplace is a frontend project made with NuxtJS
---

# Marketplace


## Geolocation

### Map

We're using leaflet to display the map and interact with it. As we're using vue and nuxt, we need to use nuxt-leaflet which is using vue2-leaflet.

Useful links:
- [leaflet website](https://leafletjs.com/index.html)
- [vue2-leaflet](https://vue2-leaflet.netlify.com/)
- [nuxt-leaflet](https://github.com/schlunsen/nuxt-leaflet)

### Reverse geoloc

We're using [Nominatim](https://nominatim.org/release-docs/latest/api/Overview/) to get the coordinates from an address

### Autocomplete address search

TODO. Here are some ideas to (re)use for our autocomplete feature:

- https://github.com/CanalTP/mimirsbrunn
- https://photon.komoot.de/ => /!\ limitations for extensive usage. + CHeck if the Apache license is not contaminating.
- https://pelias.io/
- https://github.com/klokantech/osmnames-sphinxsearch
- https://github.com/addok/addok

==> Check licenses before making a definitive choice.
