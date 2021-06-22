### Changes to PhocaMapsPlugin v3.0.10 for proposed v3.0.11

Objective - to allow gpx and kml files to be loaded onto OSM maps

- enable new features from PhocaMaps v3.0.12.proposed
- maintain backward compatibility
- match existing coding style and naming conventions

#### Changes

**Modified files:**

- phocamaps.xml -update all version references to 3.0.11
- manifest.xml - update all version references to 3.0.11
- phocamaps.php 
  - add lines to read and prepare track infos at 537-567
  - add lines to render tracks at 670-676


**Added files**

- changes3.0.11.md - this file

#### Other changes


#### Testing

I have only tested this as a vanilla install, and as an update to 3.0.10, on Joomla 3.9.27 working with PhocaMaps v3.0.12.proposed

I have not checked any functions/files that I have not modified (eg google maps, routing services, and markers), so there may be unexpected side effects



#### Suggested future changes

