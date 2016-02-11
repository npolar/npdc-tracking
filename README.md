# Tracking

The NPDC tracking app provides a uniform user interface to the Norwegian Polar Institute's biological telemetry data.
The tracking data spans over 30 years of animal positions and sensor readings; acquired via Argos, GPS, and GLS tracking technologies.

[The data is published as GeoJSON in several REST-style data APIs](https://github.com/npolar/api.npolar.no/wiki/Tracking-APIs).

## Deployment
* Metadata for transmitter platform deployments (species, individual, technology, data provider, tracking technology, platform id and model, etc.)

## [Seabird](https://data.npolar.no/tracking/seabird)

* Seabird distribution maps (heatmap and kernel density estimates)
* Tracking data from SEATRACK/SEAPOP project (GLS loggers)
* Polar stereographic projection (switchable to web mercator)
* Delivers on-the-fly visualisations of seabird area use (optionally limited by time, colony, or any other parameter)
* Permanent/linkable URIs for all visualisations (see below)

![Uria aalge](screenshots/Uria_aalge-Langanes-winter-2016-02-08.png?raw=true "Uria aalge (Langanes, winter)")

To query the data to receive a map for a given combination of parameteres, use `&filter-field=value` syntax:

* [Common guillemot in January](https://data.npolar.no/tracking/seabird/map?filter-species=Uria+aalge&filter-month=1&filter-technology=gls)
* [Common eider in March](https://data.npolar.no/tracking/seabird/map?filter-species=Somateria+mollissima&filter-month=3&filter-technology=gls)

Use a `|` in the filter for `OR`:
* [Common guillemot in January, February and December](https://data.npolar.no/tracking/seabird/map?filter-species=Uria+aalge&filter-month=1|2|12&filter-technology=gls)