# OGC Features and Geometries JSON

This GitHub repository contains [OGC](https://www.ogc.org/)'s candidate standard for OGC Features and Geometries JSON.

OGC Features and Geometries JSON will build on the widely used [GeoJSON standard](https://geojson.org/) and extend it with minimal extensions to support additional concepts that are important for the wider geospatial community and the [OGC API standards](https://ogcapi.ogc.org/).

## Status

This is a new OGC working group and the work has started on June 1st, 2021. A first draft of the candidate standard, version 0.1.0, is available.

The editor's draft of the specification can be found at [docs.ogc.org/DRAFTS/21-045.html](https://docs.ogc.org/DRAFTS/21-045.html). A [PDF version](https://docs.ogc.org/DRAFTS/21-045.pdf) is available, too.

Next steps:

* The current draft version 0.1 will be the basis for testing JSON-FG by communities, in code sprints, etc.
* We currently target an updated draft version 0.2 in mid 2023 to have a stable version for testing.

## Overview

JSON is a popular encoding format for geospatial data. The light weight, simple syntax, and clear human and machine readability of JSON appeals to developers. GeoJSON has become a very popular encoding and is supported in most deployments of APIs implementing OGC API Features, but has limitations that prevent or limit its use in some cases.

OGC Features and Geometries JSON will

* include the ability to use Coordinate Reference Systems (CRSs) other than WGS84 
* follow the [OGC Axis Order Policy](https://portal.opengeospatial.org/files/?artifact_id=76024),
* allow the use of non-Euclidean metrics, in particular ellipsoidal metrics,
* support solids and multi-solids as geometry types, and
* provide guidance on how to represent feature properties, e.g., including temporal properties.

These capabilities will be supported by Part 1 (Core) or the OGC Features and Geometries JSON standard.

JSON Schema will be used to formally specify the syntax of OGC Features and Geometries JSON.

Given the popularity of GeoJSON, the working group will ensure that OGC Features and Geometries JSON will be specified as a superset of GeoJSON so that valid OGC Features and Geometries JSON instances are also valid GeoJSON instances.

If the first part of the standard sees good adoption by the market, OGC Features and Geometries JSON may in the future be extended to support additional capabilities needed by multiple communities, for example, include more complex geometries such as curves with non-linear interpolation, time-variant geometries, or geometries based on multiple coordinate reference systems.

## Communication

Most all work on the specification takes place in [GitHub issues](https://github.com/opengeospatial/ogc-feat-geo-json/issues),
so browse there to get a good idea of what is happening, as well as past decisions.

Join the [![chat at https://gitter.im/opengeospatial/OGC-feat-geo-json](https://badges.gitter.im/opengeospatial/OGC-feat-geo-json.svg)](https://gitter.im/opengeospatial/ogc-feat-geo-json?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Recordings of meetings can be found on the [OGC portal](https://portal.ogc.org/index.php?m=projects&a=view&project_id=660&tab=2&artifact_id=97658) (access for members of the OGC and the OGC Features and Geometries JSON Standards Working Group).

## Contributing

The contributor understands that any contributions, if accepted by the OGC Membership, shall be incorporated into OGC standards documents and that all copyright and intellectual property shall be vested to the OGC.

The OGC Features and Geometries JSON Standards Working Group (SWG) is the group at OGC responsible for the stewardship of the standard, but is working to do as much work in public as possible.

* [Open issues](https://github.com/opengeospatial/ogc-feat-geo-json/issues)
* [Copy of License Language](https://raw.githubusercontent.com/opengeospatial/ogc-feat-geo-json/master/LICENSE)

For more information, see [CONTRIBUTING.md](CONTRIBUTING.md).

Pull Requests from contributors are welcomed. However, please note that by sending a Pull Request or Commit to this GitHub repository, you are agreeing to the terms in the [SWG Charter](CHARTER.adoc).
