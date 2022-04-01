# Awesome OpenStreetMap [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="osm-logo.svg" align="right" width="100">](https://www.openstreetmap.org/about)

> A curated list of awesome [OpenStreetMap](https://www.openstreetmap.org)-projects.

OpenStreetMap is an open map being used by millions of devices and users every day. It can both be edited and used by anyone free of charge.

This list contains projects using OpenStreetMap data for creative purposes, as well as projects dedicated to improving OpenStreetMap.

## Contents

* [Editors](#editors)
  * [Web Editors](#web-editors)
  * [Mobile Editors](#mobile-editors)
  * [Native Editors](#native-editors)
* [Tools](#tools)
  * [Web Tools](#web-tools)
  * [Mobile Tools](#mobile-tools)
  * [Native Tools](#native-tools)
* [Tasking Managers](#tasking-managers)
* [Maps](#maps)
  * [Web Maps](#web-maps)
  * [Mobile Maps](#mobile-maps)
  * [Generators](#generators)
  * [Map Styles](#map-styles)
  * [Map Games](#map-games)
* [Libraries](#libraries)
  * [C/C++](#cc)
  * [JavaScript](#javascript)
  * [Python](#python)
  * [Java](#java)
* [Public APIs](#public-apis)
* [Miscellaneous](#miscellaneous)
* [Video](#video)
  * [Global](#global)
  * [Regional](#regional)
* [Additional Resources](#additional-resources)
  * [Websites](#websites)
  * [Wiki-Pages](#wiki-pages)
* [Articles](#articles)
* [Communities](#communities)
  * [Global Communities](#global-communities)
* [Related lists](#related-lists)

## Editors

### Web Editors

* [iD](http://www.openstreetmap.org/edit?editor=id) - JavaScript based editor for the web browser with a wide array of presets. ([Source Code](https://github.com/openstreetmap/iD) / [Wiki](https://wiki.openstreetmap.org/wiki/ID))
* [Level0](http://level0.osmz.ru/) - Text based editor that's useful in specific corner cases. ([Source Code](https://github.com/zverik/level0) / [Wiki](https://wiki.openstreetmap.org/wiki/Level0))
* [MapWith.ai](https://mapwith.ai/) - AI assisted versions of iD. ([Meta-Repo](https://github.com/facebookmicrosites/Open-Mapping-At-Facebook) / [Editor Source Code](https://github.com/facebookincubator/RapiD) / [Wiki](https://wiki.openstreetmap.org/wiki/RapiD))
* [OSMyBiz](https://osmybiz.osm.ch) - Website for managing informations about your business. ([Source Code](https://gitlab.com/geometalab/osmybiz) / [Wiki](https://wiki.openstreetmap.org/wiki/OSMyBiz))
* [OnOSM](https://www.onosm.org/) - Allows anyone to submit business information as a note for inclusion into OSM. ([Source Code](https://github.com/osmlab/onosm.org) / [Wiki](https://wiki.openstreetmap.org/wiki/Onosm.org))
* [Deriviste](https://osm.cycle.travel/deriviste/) - Provides a simple interface to add nodes to OpenStreetMap based on what you see in Mapillary street-level imagery. ([Source Code](https://github.com/systemed/deriviste) / [Wiki](https://wiki.openstreetmap.org/wiki/Deriviste))
* [Healthsites.io](https://healthsites.io/map) - An online editor focused on adding and improving data on global health facilities. ([Source Code](https://github.com/healthsites/healthsites/) / [Wiki](https://wiki.openstreetmap.org/wiki/Healthsites.io))

### Mobile Editors

<!--lint disable no-repeat-punctuation-->
* [StreetComplete](https://github.com/westnordost/StreetComplete) - App for improving OSM by answering simple questions. (Android / [Wiki](https://wiki.openstreetmap.org/wiki/StreetComplete))
* [Vespucci](https://vespucci.io/) - Advanced full-data-model editor for Android. (Android / [Source Code](https://github.com/MarcusWolschon/osmeditor4android) / [Wiki](https://wiki.openstreetmap.org/wiki/Vespucci))
* [GoMap!!](https://apps.apple.com/app/id592990211) - Feature-rich mobile editor for iOS. (iOS / [Source Code](https://github.com/bryceco/GoMap) / [Wiki](https://wiki.openstreetmap.org/wiki/Go_Map!!))
<!--lint enable no-repeat-punctuation-->

### Native Editors

* [JOSM](https://josm.openstreetmap.de) - Advanced extensible desktop editor. ([Source Code](https://josm.openstreetmap.de/browser) / [Wiki](https://wiki.openstreetmap.org/wiki/JOSM))
* [Potlatch 3](https://www.systemed.net/potlatch/) - Native intermediate-level editor built in Adobe AIR. ([Source Code](https://github.com/systemed/potlatch3) / [Wiki](https://wiki.openstreetmap.org/wiki/Potlatch))

## Tools

### Web Tools

* [OpenMapTiles](https://openmaptiles.org/) - Set of tools for self-hosted vector maps and map services with labels in more than 50 languages. ([Source Code](https://github.com/openmaptiles) / [Wiki](https://wiki.openstreetmap.org/wiki/OpenMapTiles))
* [OSMNames](http://osmnames.org/) - Geocoding tool ranking places according to the corresponding Wikipedia page popularity. ([Source Code](https://github.com/osmnames/osmnames) / [Wiki](https://wiki.openstreetmap.org/wiki/OSMNames))
* [overpass-turbo](http://overpass-turbo.eu) - Web based data mining tool for OpenStreetMap using Overpass API. ([Source Code](https://github.com/tyrasd/overpass-turbo) / [Wiki](https://wiki.openstreetmap.org/wiki/Overpass_turbo))
* [osmcha](https://osmcha.mapbox.com) - Detector for suspicious changesets. ([Source Code](https://github.com/mapbox/osmcha-frontend) / [Wiki](https://wiki.openstreetmap.org/wiki/OSMCha))
* [hdyc](http://hdyc.neis-one.org) - Statistics viewer for contributions of any OSM user. ([Wiki](https://wiki.openstreetmap.org/wiki/How_did_you_contribute%3F)) <!-- markdown-link-check-disable-line -->
* [achavi](https://overpass-api.de/achavi/) - Augmented change viewer. ([Source Code](https://github.com/nrenner/achavi/) / [Wiki](https://wiki.openstreetmap.org/wiki/Achavi))
* [Analytic OSM Tracker](https://github.com/MichaelVL/osm-analytic-tracker) - Tracker for changesets in your region.
* [Osmose](https://osmose.openstreetmap.fr) - QA-tool for fixing problems detected in OpenStreetMap data. ([Source Code](https://github.com/osm-fr?q=osmose) / [Wiki](https://wiki.openstreetmap.org/wiki/Osmose))
* [opening_hours evaluation tool](https://openingh.openstreetmap.de/evaluation_tool/) - Tool for evaluating `opening_hours` tags. ([Source Code](https://github.com/opening-hours/opening_hours.js))
* [taginfo](https://taginfo.openstreetmap.org/) - Website displaying information on tags and their usage. ([Source Code](https://github.com/taginfo/taginfo/) / [Wiki](https://wiki.openstreetmap.org/wiki/Taginfo))
* [Turn Restrictions](https://ahorn.lima-city.de/tr/) - Viewer for turn-restrictions and linked errors.
* [NLMaps](https://nlmaps.gorgor.de/) - Website allowing to query OSM data using plain English.
* [My Notes](https://my-notes.osm-hr.org/) - Search for finding your old unresolved notes.
* [YoHours](https://projets.pavie.info/yohours/) - Tool for generating `opening_hours` tags. ([Source Code](https://framagit.org/PanierAvide/YoHours))
* [OpenStreetMap Welcome Tool](https://welcome.osm.be/) - Tool for finding fresh mappers in your area. ([Source Code](https://github.com/osmbe/osm-welcome-tool))
* [Web To OSM Opening Hours](https://webmapping.cyou/WebToOSMOH/) - Tool for converting human-readable opening hours to `opening_hours` tags. ([Source Code](https://github.com/OSM-de/WebToOSMOH))
* [ohsome Dashboard](https://ohsome.org/apps/dashboard/) - Tool for visualizing changes over a certain time period. ([Wiki](https://wiki.openstreetmap.org/wiki/Ohsome_Dashboard))

### Mobile Tools

* [OSMTracker](https://github.com/labexp/osmtracker-android) - Offline GPS tracking tool for recording GPX tracks. (Android / [Wiki](https://wiki.openstreetmap.org/wiki/OSMTracker_(Android)))

### Native Tools

* [Baremaps](https://www.baremaps.com/) - Open source pipeline for producing Mapbox vector tiles from OpenStreetMap with Postgis and Java. ([Source Code](https://github.com/baremaps/baremaps))

<!--Offline, may be because of russia-ukraine-war - * [whodidit](http://zverik.osm.rambler.ru/whodidit/) - Changesets analyzer.-->

## Tasking Managers

Tasking Managers are websites which assign small tasks to individual users to work towards a common goal.

This section is a great place to start if you want to get into improving OpenStreetMap.

* [HOT Tasking Manager](https://tasks.hotosm.org/) - Mapping tasks for supporting humanitarian missions in crisis areas.
* [MapRoulette](https://maproulette.org/) - Various challenges for making small edits to achive big tasks. ([Source Code](https://github.com/osmlab/maproulette3) / [Wiki](https://wiki.openstreetmap.org/wiki/MapRoulette))
* [Pic4Review](https://pic4review.pavie.info/#/) - Tool for adding objects to OSM by reviewing images. ([Source Code](https://framagit.org/Pic4Carto/Pic4Review) / [Wiki](https://wiki.openstreetmap.org/wiki/Pic4Review))
* [Map Complete](https://mapcomplete.osm.be/) - Tool for mapping in scoped tasks. ([Wiki](https://wiki.openstreetmap.org/wiki/MapComplete))
* [Damn Project](https://www.damn-project.org/) - Project for mapping by dividing big areas into small squares mappable by humans. ([Source Code](https://git.sr.ht/~qeef/damn-deploy) / [Wiki](https://wiki.openstreetmap.org/wiki/Divide_and_map._Now.))
* [NotesReview](https://ent8r.github.io/NotesReview/) - Interface for searching and resolving OSM notes. ([Source Code](https://github.com/ENT8R/NotesReview))
* [TeachOSM Tasking Manager](https://tasks.teachosm.org/) - Tasking Manager made for school classrooms to help map for humanitarian causes.

## Maps

### Web Maps

* [changeset-map](http://osmlab.github.io/changeset-map/) - Map visualizing changesets. ([Source Code](https://github.com/osmlab/changeset-map))
* [last-week-on-osm](https://tyrasd.github.io/latest-changes/#2/15.0/-15.0) - Map for exploring latest changesets. ([Source Code](https://github.com/tyrasd/latest-changes/))
* [Baato Before-After Maps](https://beforeafter.baato.io/) - Generate before-after maps to visualize the work your local community has done. ([Source Code](https://github.com/baato/before-after))
* [Show me the way](https://osmlab.github.io/show-me-the-way/) - Live map showing latest changes on aerial imagery. ([Source Code](https://github.com/osmlab/show-me-the-way/) / [Wiki](https://wiki.openstreetmap.org/wiki/Show_Me_The_Way))
* [OSM In Realtime](https://osm-in-realtime.jwestman.net/) - Visualization of the changes made to OpenStreetMap as they happen. ([Source Code](https://gitlab.com/jwestman/osm-in-realtime) / [Wiki](https://wiki.openstreetmap.org/wiki/OSM-in-realtime))
* [indoor=](https://indoorequal.org) - Map for viewing indoor data from OpenStreetMap. ([Wiki](https://wiki.openstreetmap.org/wiki/Indoor%3D)) <!-- markdown-link-check-disable-line -->
* [Qwant Maps](https://www.qwant.com/maps) - Modern map with POI search and routing functionality. ([Wiki](https://wiki.openstreetmap.org/wiki/Qwant_Maps))
* [F4map Demo](https://demo.f4map.com/) - 3D rendering demo of OpenStreetMap data. ([Wiki](https://wiki.openstreetmap.org/wiki/F4_Map))
* [FacilMap](https://facilmap.org/) - Map with easy possibility to filter for POI types. ([Source Code](https://github.com/FacilMap/facilmap) / [Wiki](https://wiki.openstreetmap.org/wiki/FacilMap))
* [Straßenraumkarte Neukölln](https://supaplexosm.github.io/strassenraumkarte-neukoelln/?map=micromap) - High-detail micromap of the district "Neukölln" of Berlin, Germany. ([Wiki](https://wiki.openstreetmap.org/wiki/Micromapping#Stra.C3.9Fenraumkarte_Neuk.C3.B6lln))
* [Road Curvature](https://roadcurvature.com/map/) - Helps to find curvy roads for those who enjoy them. ([Source Code](https://github.com/adamfranco/curvature))

### Mobile Maps

* [OsmAnd](https://osmand.net) - Map viewing and navigation (routing) application with offline functionality available for Android and iOS. (Android, iOS / [Source Code Android](https://github.com/osmandapp/OsmAnd) / [Source Code iOS](https://github.com/osmandapp/OsmAnd-iOS) / [Wiki](https://wiki.openstreetmap.org/wiki/OsmAnd))
* [Organic Maps](https://organicmaps.app/) - A free offline maps app based on OSM. (Android, iOS / [Source Code](https://github.com/organicmaps/organicmaps) / [Wiki](https://wiki.openstreetmap.org/wiki/Organic_Maps))
* [Magic Earth](https://www.magicearth.com/) - A free turn-by-turn navigation app. (Android, iOS / [Wiki](https://wiki.openstreetmap.org/wiki/Magic_Earth))

### Generators

* [MyOSMatic](https://print.get-map.org/new/) - Website for generating printable street maps from OSM data. ([Source Code](https://github.com/hholzgra/maposmatic/))
* [Field Papers](http://fieldpapers.org/) - Generate maps for printing, annotate them, and manage your notes after. ([Source Code](https://github.com/fieldpapers/fieldpapers) / [Wiki](https://wiki.openstreetmap.org/wiki/Field_Papers))

### Map Styles

* [Terrain Classic](https://github.com/stamen/terrain-classic) - World-wide CartoCSS port of Stamen's classic terrain style.

### Map Games

* [Back Of Your Hand](https://backofyourhand.com/) - A web map game that tests your knowledge by having you find a street in a given area. ([Source Code](https://github.com/adam-lynch/back-of-your-hand))

## Libraries

### C/C++

* [libosmium](https://github.com/osmcode/libosmium) - Fast and flexible C++ library for working with OpenStreetMap data. ([Wiki](https://wiki.openstreetmap.org/wiki/Osmium))
* [OSRM](https://github.com/Project-OSRM/osrm-backend) -  Routing engine for use in C++ applications. ([Wiki](https://wiki.openstreetmap.org/wiki/Open_Source_Routing_Machine))
* [mapnik](https://github.com/mapnik/mapnik) - Combines pixel-perfect image output with lightning-fast cartographic algorithms, and exposes interfaces in C++, Python, and Node. ([Wiki](https://wiki.openstreetmap.org/wiki/Mapnik))

### JavaScript

* [openstreetmap-tag-map](https://github.com/tanrax/openstreetmap-tag-map) - Tag for Riot.js to generate iframe-map from the country and region.
* [node-osmium](https://github.com/osmcode/node-osmium) - Node wrapper for libosmium for working with OpenStreetMap data.
* [node-mapnik](https://github.com/mapnik/node-mapnik) - Node wrapper for mapnik.
* [Leaflet](https://leafletjs.com/) - An open-source JavaScript library for mobile-friendly interactive maps. ([Source Code](https://github.com/Leaflet/Leaflet) / [Wiki](https://wiki.openstreetmap.org/wiki/Leaflet))
* [OpenLayers](https://openlayers.org/) - A high-performance library for rendering raster and vector maps. ([Source Code](https://github.com/openlayers/openlayers) / [Wiki](https://wiki.openstreetmap.org/wiki/OpenLayers))
* [MapLibre GL JS](https://maplibre.org/projects/#js) - A map renderer with GPU-accelerated vector tile rendering. ([Source Code](https://github.com/maplibre/maplibre-gl-js) / [See Related List](#related-awesome-maplibre))

### Python

* [overpass-wrapper](https://github.com/mvexel/overpass-api-python-wrapper) - Wrapper around the OpenStreetMap Overpass API.
* [osmapi](https://github.com/metaodi/osmapi) - Python wrapper for the OpenStreetMap API. ([Wiki](https://wiki.openstreetmap.org/wiki/Osmapi_(Python_library)))
* [osmcha](https://github.com/willemarcel/osmcha) - Python package to detect suspicious OSM changesets.
* [osmnx](https://github.com/gboeing/osmnx) - Visualizer for street networks. ([Wiki](https://wiki.openstreetmap.org/wiki/OSMnx))
* [python-mapnik](https://github.com/mapnik/python-mapnik) - Python wrapper for mapnik.

### Java

* [OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner) - Open source multi-modal trip planner. ([Wiki](https://wiki.openstreetmap.org/wiki/OpenTripPlanner))
* [GraphHopper](https://github.com/graphhopper/graphhopper) - Open source route planning library and server using OpenStreetMap. ([Wiki](https://wiki.openstreetmap.org/wiki/GraphHopper))

## Public APIs

* [overpass](http://overpass-api.de) - Read-only API that serves up custom selected parts of the OSM map data. ([Source Code](https://github.com/drolbr/Overpass-API) / [Wiki](https://wiki.openstreetmap.org/wiki/Overpass_API))
* [osm.mazdermind](https://osm.mazdermind.de/replicate-sequences/) - Maps Timestamp to replicate sequences. ([Source Code](https://github.com/MaZderMind/replicate-sequences))
* [planet.osm](http://planet.osm.org) - Minutely/weekly/yearly/full dumps of osm data. ([Wiki](https://wiki.openstreetmap.org/wiki/Planet.osm))
* [bbbike](https://extract.bbbike.org) - Custom extracts of areas from planet.osm. ([Wiki](https://wiki.openstreetmap.org/wiki/BBBike_@_World))

## Miscellaneous

* [OpenGeofiction](https://opengeofiction.net/) - A completely fictional user-made world map, created using the OSM software platform. ([Wiki](https://wiki.openstreetmap.org/wiki/OpenGeofiction))

## Video

### Global

* [State of the Map](https://www.youtube.com/channel/UCLqJsr_5PfdvDFbgv1qp2aQ) - YouTube channel of the State of the Map conference containing VoDs of talks. ([Wiki](https://wiki.openstreetmap.org/wiki/State_of_the_Map))
* [Humanitarian OpenStreetMap Team (HOT)](https://www.youtube.com/user/hotosm) - YouTube channel of the HOT containing content regarding humanitarian OSM work.

### Regional

* [OpenStreetMap Indonesia YouTube Channel](https://www.youtube.com/channel/UCRqMbcsT9ummMvByc1BlsDQ)
* [OpenStreetMap Poland YouTube Channel](https://www.youtube.com/channel/UCH4PSBSafxZ-YWg8RCRbHjA)
* [OpenStreetMap US YouTube Channel](https://www.youtube.com/channel/UCQpS2iHNVR-_6nAxt87nwCw)

## Additional Resources

### Websites

* [LearnOSM.org](https://learnosm.org/en/beginner/) - Extencive beginners' guide to editing OpenStreetMap. ([Wiki](https://wiki.openstreetmap.org/wiki/LearnOSM))
* [What OSM?](https://whatosm.pavie.info/) - Tool for finding tools for contributing to OSM by answering three simple questions.
* [TeachOSM](https://teachosm.org/) - Project assisting educators at all levels to introduce open source mapping and OpenStreetMap in the classroom. ([Wiki](https://wiki.openstreetmap.org/wiki/TeachOSM))

### Wiki-Pages

* [Main Page](https://wiki.openstreetmap.org/wiki/Main_Page) - An overview page with links to the most useful pages.
* [Beginners' guide](https://wiki.openstreetmap.org/wiki/Beginners'_guide) - Five-step-guide on what OpenStreetMap is and how it works.
* [Mapping projects](https://wiki.openstreetmap.org/wiki/Mapping_projects) - Mapping projects to participate in.
* [OSM Promotional Material Programme](https://wiki.openstreetmap.org/wiki/OSM_Promotional_Material_Programme) - Information on receiving promotional merch such as Stickers.

## Articles

* [Volunteer armies map ‘invisible’ communities hit by coronavirus](https://www.asahi.com/ajw/articles/13729507) - OpenStreetMap contributors map over 1,100 handwashing stations. (5 min read, 2020-10-15, The Asahi Shimbun)

## Communities

### Global Communities

* [OpenStreetMap Community](https://community.openstreetmap.org/) - Official forums hosted by the OpenStreetMap Foundation.
* [r/openstreetmap](https://www.reddit.com/r/openstreetmap) - Inofficial Reddit forum dedicated to sharing OSM related links and news.
* [“OpenStreetMap World” Discord](https://discord.gg/openstreetmap) - OSM related instant messaging and voice chat group.

## Related lists

* [awesome-maplibre](https://github.com/maplibre/awesome-maplibre#readme) - A collection of awesome things that use or support MapLibre! <span id="related-awesome-maplibre"/>

## Footnotes

OpenStreetMap and the OpenStreetMap Logo are a trademark of the OpenStreetMap Foundation, and is used with their permission. This project is not endorsed by or affiliated with the OpenStreetMap Foundation.

The OpenStreetMap Logo by Ken Vermette is used under the Creative Commons Attribution-ShareAlike 3.0 License.
