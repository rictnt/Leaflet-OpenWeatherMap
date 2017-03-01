# Leaflet-OpenWeatherMap

Leaflet plugin to show weather from [Open Weather Map](http://openweathermap.org/) in main cities.

[Check the Demo!](http://scanex.github.io/Leaflet-OpenWeatherMap/OWMExample.html)

### Dependencies
  * jQuery
  * Handlebars

[GeoMixer server](http://geomixer.ru/index.php/en/) is used to get city local time shift in forecast popup.

### Usage
```
    var owm = new L.OWMLayer(options);
    map.addLayer(owm);
```

The following `options` of `L.OWMLayer` constructor are available:
  * `key`: [Open Weather Map APPID](http://openweathermap.org/appid)
  * `cityIDs`: array of city IDs, see [Open Weather Map API](http://openweathermap.org/api)
  
### License
[MIT](https://opensource.org/licenses/MIT)
