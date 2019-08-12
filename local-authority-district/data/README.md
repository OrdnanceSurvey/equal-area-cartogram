*Select the format of data that you need for your software package.*

## Data Formats

### CSV

Each layer of the cartogram is provided as a seperate CSV file. The geometry is encoded using a well known text (WKT) representation.


### GeoPackage

The layers of the cartogram are provided as individual tables / layers within a single SQLite database container.


### geofacet

The [geofacet](https://hafen.github.io/geofacet/) R package provides a ggplot2 faceting function based upon square equal area cartogram grids.

The R code and geofacet-specific CSV format for the cartogram is provided so that users can use the grid within the geofacet library and edit the grid via the ['Grid Designer App'](https://hafen.github.io/grid-designer/) if they want a different geofacet-grid representation. The R code and CSV files provide United Kingdom, Great Britain, country and regional grid coverage.


### SVG

The geometries of the cartogram are provided in a single SVG file.
