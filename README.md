# Observations & Measurements JSON encoding

This repository contains some provisional JSON schema for encoding observations & measurements in JSON. Heavily work in progress. 

Main observation schema: [Observation](https://stash.csiro.au/projects/WML/repos/om-json/browse/Observation.json)

## Tools

  * Very handy online validation of instances against schema: http://jsonschemalint.com/ (although lacks good errors for linked schemas)
  * [JSONLint](http://jsonlint.com)
  * Guide to authoring JSON schema: http://spacetelescope.github.io/understanding-json-schema/, specifically http://spacetelescope.github.io/understanding-json-schema/structuring.html#structuring

## TODOs

  * GeoJSON validation is not yet working. Need this for GeometryObservations
  * Timseries support (i.e. timeseriesML)
  * Gregorian time instants (gYearMonth etc.)
  * Improve partitioning of schema (currently in one schema file)
  * Online validator 
