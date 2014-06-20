leaflet-map
===========

Uses Polymer to create a simple [Leaflet.js](http://leafletjs.com) map element.

##Usage##

Import Web Components polyfill:

```<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.3.2/platform.js"></script>```

```<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.3.2/polymer.js"></script>```

Import Custom Element:

```<link rel="import" href="src/leaflet-map.html">```

Include Leaflet.js stylesheet and script:

```<link rel="stylesheet" href="http://cdn.leafletjs.com/leaflet-0.7.3/leaflet.css" />```

```<script src="http://cdn.leafletjs.com/leaflet-0.7.3/leaflet.js"></script>```

##Attributes##

Attribute   | Options  | Default         | Description
---         | ---      | ---             | ---
`latitude`  | *string* | `51.500446`     | The latitude coordinate
`longitude` | *string* | `-0.125266`     | The longitude coordinate
`zoom`      | *int*    | `14`            | The zoom level of the panorama

##Credits##

Initial version by [Peter Gasston](http://broken-links.com). Based on [`google-maps-element` by Zeno Rocha](https://github.com/eduardolundgren/google-maps-element).

##License##

[MIT License](http://opensource.org/licenses/MIT)
