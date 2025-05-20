# New Zealand Coastal Elevation

[![STAC Browser Badge](https://img.shields.io/badge/Open_in_STAC_Browser-%2309B3AD?style=flat&label=New%20Zealand%20Elevation&labelColor=%23144E63)](https://radiantearth.github.io/stac-browser/#/external/nz-coastal.s3-ap-southeast-2.amazonaws.com/catalog.json?.language=en)
[![AWS Badge](https://img.shields.io/badge/Open_in_Registry_of_Open_Data_on_AWS-%23FF9900.svg?logo=amazon-web-services&logoColor=white&labelColor=%23232F3E)](https://registry.opendata.aws/nz-coastal/)

Toitū Te Whenua makes New Zealand's most up-to-date publicly owned coastal elevation data freely available to use under an open licence. You can access this through the [Registry of Open Data on AWS](https://registry.opendata.aws/nz-coastal/).

## Quickstart

Browse the archive with [STAC Browser](https://radiantearth.github.io/stac-browser/#/external/nz-coastal.s3-ap-southeast-2.amazonaws.com/catalog.json?.language=en) or access the catalog directly [https://nz-coastal.s3-ap-southeast-2.amazonaws.com/catalog.json](https://nz-coastal.s3-ap-southeast-2.amazonaws.com/catalog.json)

## Background

This repository contains STAC Collection metadata for each coastal elevation dataset.

The New Zealand Elevation repository guidance documentation covers information that also applies to coastal elevation:

- [Naming](https://github.com/linz/elevation/blob/master/docs/naming.md) covers the bucket naming structure
- [Usage](https://github.com/linz/elevation/blob/master/docs/usage.md) shows how TIFFs can be interacted with from S3 using GDAL, QGIS, etc
- [Elevation Compression](https://github.com/linz/elevation/blob/master/docs/tiff-compression/README.md) provides commentary and analysis on the compression options we explored.

## AWS Access

Toitū Te Whenua owns and maintains a public bucket which is sponsored and shared via the [Registry of Open Data on AWS](https://registry.opendata.aws/nz-coastal/) `s3://nz-coastal` in `ap-southeast-2`.

Using the [AWS CLI](https://aws.amazon.com/cli/) anyone can access all of the imagery specified in this repository.

```
aws s3 ls --no-sign-request s3://nz-coastal/
```

## Related

- For access to LINZ's elevation data see [linz/elevation](https://github.com/linz/elevation)
- For access to LINZ's aerial and satellite imagery see [linz/imagery](https://github.com/linz/imagery)

## License

Source code is licensed under [MIT](LICENSE).

All metadata and docs are licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).

Toitū Te Whenua Land Information New Zealand is the copyright owner for the data that is available in this bucket. Licensed for re-use under "[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)".

Attribution: Licensed by Toitū Te Whenua Land Information New Zealand for re-use under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).
