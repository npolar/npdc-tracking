# Tracking

The tracking app provides a uniform user interface for the Norwegian Polar Institute's animal movements data,
spanning over 30 years of animal positions, acquired via Argos, GPS, and GLS tracking technologies.

[The tracking data is published as GeoJSON in several RESTful data services](https://github.com/npolar/api.npolar.no/wiki/Tracking-APIs).

## Deployment
* Metadata for transmitter platform deployments (species, individual, technology, data provider, tracking technology, platform id and model, etc.)

## Seabird

[tracking/seabird/map](http://data.npolar.no/tracking/seabird/map)

* Seabird distribution maps (heatmap and kernel density estimates)
* Tracking data from SEATRACK/SEAPOP project (GLS loggers)
* Polar stereographic projection (switchable to web mercator)
* Delivers on-the-fly visualisations of seabird area use (optionally limited by time, colony, or any other parameter)
* Permanent/linkable URIs for all visualisation

![Uria aalge](screenshots/Uria_aalge-Langanes-winter-2016-02-08.png?raw=true "Uria aalge (Langanes, winter)")