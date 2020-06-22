OSM Gravel Layer
================

This is an attempt at creating a map layer showing roads suitable for "gravel" riding
(whatever that means, but people usually talk about wide tired drop bar bikes).
that can be rendered on top of any base map.

To do that, we forked [CyclOSM](https://github.com/cyclosm/cyclosm-cartocss-style) and
kept removing and changing styles until we arrived at something that suited our needs.
Kudos to them for the clean code structure and open sourcing their work!

## Licenses

This style is based on the [CyclOSM](https://github.com/cyclosm/cyclosm-cartocss-style),
which is licensed under BSD-3-Clause license. Everything (be it icons
or code) not listed explicitly below should be consider as available under
this license.

The contours and elevation lines render is based on the very good work and
code available from [OpenTopoMap](https://github.com/der-stefan/OpenTopoMap).

The colors used in the `palette.mss` file are based on the
[Hydda](https://github.com/karlwettin/tilemill-style-hydda/tree/bb27f0a9cad1920e19ae8febd39f6f9328369e6f)
style, licensed under Apache License 2.0.

The icons in `symbols/osm-bright-gl-style` are taken from the [OSM Bright GL
style](https://github.com/openmaptiles/osm-bright-gl-style/tree/327e1b41987893b958e3aae06abc2cc7363dc5aa/icons)
and are licensed under Creative Commons BY 4.0.

The icons in `symbols/openstreetmap-carto` are taken from the
[OpenStreetMap-carto](https://github.com/gravitystorm/openstreetmap-carto)
style and are licensed under CC0 public domain.

The icons in `symbols/osmandapp` are taken from the
[OsmAnd app resources](https://github.com/osmandapp/OsmAnd-resources).

The inner tube bicycle icon is based on
https://www.flaticon.com/free-icon/inner-tube_1575936.
