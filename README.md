# Awesome OpenStreetMap [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="osm-logo.svg" align="right" width="100">](https://www.openstreetmap.org/about)

> A curated list of awesome [OpenStreetMap](https://www.openstreetmap.org)-projects.

OpenStreetMap is an open map being used by millions of devices and users every day. It can both be edited and used by anyone free of charge.

This list contains projects using OpenStreetMap data for creative purposes, as well as projects dedicated to improving OpenStreetMap.

We also have a list of <a href="UNMAINTAINED.md">unmaintained projects</a>. If you are a developer, consider adopting one!

## Contents

* [Editors](#editors)
  * [Web Editors](#web-editors)
  * [Mobile Editors](#mobile-editors)
  * [Native Editors](#native-editors)
* [Tools](#tools)
  * [Web Tools](#web-tools)
  * [Mobile Tools](#mobile-tools)
  * [Native Tools](#native-tools)
* [Changeset Tools](#changeset-tools)
  * [Web Services](#web-services)
* [Tasking Managers](#tasking-managers)
* [Maps](#maps)
  * [Web Maps](#web-maps)
  * [Mobile Maps](#mobile-maps)
  * [Generators](#generators)
  * [Map Styles](#map-styles)
  * [Map Games](#map-games)
  * [Goal Tracking](#goal-tracking)
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

<!-- lint disable no-undefined-references -->

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
* [StreetComplete](https://github.com/westnordost/StreetComplete) - App for improving OSM by answering simple questions. ([Android](https://play.google.com/store/apps/details?id=de.westnordost.streetcomplete) / [Wiki](https://wiki.openstreetmap.org/wiki/StreetComplete))
* [Vespucci](https://vespucci.io/) - Advanced full-data-model editor for Android. ([Android](https://play.google.com/store/apps/details?id=de.blau.android) / [Source Code](https://github.com/MarcusWolschon/osmeditor4android) / [Wiki](https://wiki.openstreetmap.org/wiki/Vespucci))
* [GoMap!!](http://gomaposm.com) - Feature-rich mobile editor for iOS. ([iOS](https://apps.apple.com/app/id592990211) / [Source Code](https://github.com/bryceco/GoMap) / [Wiki](https://wiki.openstreetmap.org/wiki/Go_Map!!))
* [Every Door](https://every-door.app) - Every Door is an Android and iOS app that lets you create and edit objects in OpenStreetMap. It supports editing node and polygon features, and creating point features like shops, benches, and building entrances. ([Android](https://play.google.com/store/apps/details?id=info.zverev.ilya.every_door) / [iOS](https://apps.apple.com/app/id1621945342) / [Source Code](https://github.com/zverik/every_door) / [Wiki](https://wiki.openstreetmap.org/wiki/Every_Door))
* [OSM Go!](https://github.com/DoFabien/OsmGo) - OSM Go! is an Android application and a Progressive Web Applications (PWA) for contributing to OpenStreetMap. ([Android](https://play.google.com/store/apps/details?id=fr.dogeo.osmgo) / [WebApp](https://osmgo.com/#/main) / [Source Code](https://github.com/DoFabien/OsmGo) / [Wiki](https://wiki.openstreetmap.org/wiki/Osm_Go!))
<!--lint enable no-repeat-punctuation-->

### Native Editors

* [JOSM](https://josm.openstreetmap.de) - Advanced extensible desktop editor. ([Source Code](https://josm.openstreetmap.de/browser) / [Wiki](https://wiki.openstreetmap.org/wiki/JOSM))
* [Potlatch 3](https://www.systemed.net/potlatch/) - Native intermediate-level editor built in Adobe AIR. ([Source Code](https://github.com/systemed/potlatch3) / [Wiki](https://wiki.openstreetmap.org/wiki/Potlatch))
* [Merkaartor](https://github.com/openstreetmap/merkaartor) - An opensource OSM editor, written in C++ and Qt

## Tools

### Web Tools

* [OpenMapTiles](https://openmaptiles.org/) - Set of tools for self-hosted vector maps and map services with labels in more than 50 languages. ([Source Code](https://github.com/openmaptiles) / [Wiki](https://wiki.openstreetmap.org/wiki/OpenMapTiles))
* [OSMNames](http://osmnames.org/) - Geocoding tool ranking places according to the corresponding Wikipedia page popularity. ([Source Code](https://github.com/osmnames/osmnames) / [Wiki](https://wiki.openstreetmap.org/wiki/OSMNames))
* [overpass-turbo](http://overpass-turbo.eu) - Web based data mining tool for OpenStreetMap using Overpass API. ([Source Code](https://github.com/tyrasd/overpass-turbo) / [Wiki](https://wiki.openstreetmap.org/wiki/Overpass_turbo))
* [hdyc](http://hdyc.neis-one.org) - Statistics viewer for contributions of any OSM user. ([Wiki](https://wiki.openstreetmap.org/wiki/How_did_you_contribute%3F)) <!-- markdown-link-check-disable-line -->
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


## Changeset Tools

### Web Services

* [osmcha](https://osmcha.org) - Detector for suspicious changesets. ([Source Code](https://github.com/mapbox/osmcha-frontend) / [Wiki](https://wiki.openstreetmap.org/wiki/OSMCha))
* [achavi](https://overpass-api.de/achavi/) - Augmented change viewer. ([Source Code](https://github.com/nrenner/achavi/) / [Wiki](https://wiki.openstreetmap.org/wiki/Achavi))
* [Osm Change Viz](https://resultmaps.neis-one.org/osm-change-viz) - Changeset visualizer displaying information about added/modified/deleted elements in different panels.
* [changeset-map](http://osmlab.github.io/changeset-map/) - Map visualizing changes in selected changesets. Used in OsmCha. ([Source Code](https://github.com/osmlab/changeset-map))
* [OSM History Viewer](https://osmhv.openstreetmap.de/) - Changeset visualization. ([Source Code](https://github.com/osmrmhv/osmrmhv))
* [Who did it?](https://simon04.dev.openstreetmap.org/whodidit/) - Map highlighting recent edits per tile. Provides RSS feeds for watching changes in custom bounding boxes.  ([Source Code](https://github.com/simon04/whodidit) / [Wiki](https://wiki.openstreetmap.org/wiki/Quality_assurance#WhoDidIt))
<!--Offline, may be because of russia-ukraine-war - * [whodidit](http://zverik.osm.rambler.ru/whodidit/) - Changesets analyzer.-->
* [Osm Change Tiles](https://resultmaps.neis-one.org/osm-change-tiles) - Map highlighting recent edits per tile. Provides RSS feeds for watching changes in custom bounding boxes.
* [Analytic OSM Tracker](https://github.com/MichaelVL/osm-analytic-tracker)[^selfhosted-only] - Tracker for changesets in your region.
* [Suspicious OSM Changesets](https://resultmaps.neis-one.org/osm-suspicious) - Find suspicious OSM changesets.
* [Changeset Text Search](https://resultmaps.neis-one.org/osm-changesets) - Filter OSM changesets by comment.
* [Latest Changeset Discussions](https://resultmaps.neis-one.org/osm-discussions) - Show latest discussions on OSM changesets.


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
* [OSM Streak](http://streak.osmz.ru/) - OSM Streak makes you do small tasks for OSM every day. Tasks are small and about five minutes each, but the point is to map every day, not map as much as you can. ([Source Code](https://github.com/Zverik/osmstreak))

## Maps

### Web Maps

* [last-week-on-osm](https://tyrasd.github.io/latest-changes/#2/15.0/-15.0) - Map for exploring latest changesets. ([Source Code](https://github.com/tyrasd/latest-changes/))
* [Baato Before-After Maps](https://beforeafter.baato.io/) - Generate before-after maps to visualize the work your local community has done. ([Source Code](https://github.com/baato/before-after))
* [Show me the way](https://osmlab.github.io/show-me-the-way/) - Live map showing latest changes on aerial imagery. ([Source Code](https://github.com/osmlab/show-me-the-way/) / [Wiki](https://wiki.openstreetmap.org/wiki/Show_Me_The_Way))
* [OSM In Realtime](https://osm-in-realtime.jwestman.net/) - Visualization of the changes made to OpenStreetMap as they happen. ([Source Code](https://gitlab.com/jwestman/osm-in-realtime) / [Wiki](https://wiki.openstreetmap.org/wiki/OSM-in-realtime))
* [osm-livechanges](http://live.openstreetmap.fr/) - Near-real-time display of edits in the OpenStreetMap database. ([Source Code](https://github.com/cstenac/osm-livechanges))
* [indoor=](https://indoorequal.org) - Map for viewing indoor data from OpenStreetMap. ([Wiki](https://wiki.openstreetmap.org/wiki/Indoor%3D)) <!-- markdown-link-check-disable-line -->
* [Qwant Maps](https://www.qwant.com/maps) - Modern map with POI search and routing functionality. ([Wiki](https://wiki.openstreetmap.org/wiki/Qwant_Maps))
* [F4map Demo](https://demo.f4map.com/) - 3D rendering demo of OpenStreetMap data. ([Wiki](https://wiki.openstreetmap.org/wiki/F4_Map))
* [FacilMap](https://facilmap.org/) - Map with easy possibility to filter for POI types. ([Source Code](https://github.com/FacilMap/facilmap) / [Wiki](https://wiki.openstreetmap.org/wiki/FacilMap))
* [Straßenraumkarte Neukölln](https://supaplexosm.github.io/strassenraumkarte-neukoelln/?map=micromap) - High-detail micromap of the district "Neukölln" of Berlin, Germany. ([Wiki](https://wiki.openstreetmap.org/wiki/Micromapping#Stra.C3.9Fenraumkarte_Neuk.C3.B6lln))
* [Road Curvature](https://roadcurvature.com/map/) - Helps to find curvy roads for those who enjoy them. ([Source Code](https://github.com/adamfranco/curvature))
* [OpenLevelUp!](https://openlevelup.net/) - An OSM based indoor viewer.([Wiki](https://wiki.openstreetmap.org/wiki/OpenLevelUp))
* [AccessMap](https://www.accessmap.io/) - A web map project to enable accessible, safe sidewalk trip planning for people with limited mobility. Currently rendering senveral cities in Washington State. ([Source Code](https://github.com/accessmap))
* [Cycle.Travel](https://cycle.travel/map) - An OSM-based bike route-planner, together with extensive editorial content about long-distance cycle routes and city cycling. ([Wiki](https://wiki.openstreetmap.org/wiki/Cycle.travel))
* [OSM Landuse](https://osmlanduse.org) - OSM based landuse and landcover WebGIS application.
* [OsmAPP](https://osmapp.org) - A browsable map showing data and offering simple POI-editing capabilities. ([Source Code](https://github.com/zbycz/osmapp))
* [Tracesmap](https://tracesmap.com/) - A map allowing for planning routes on OsmCarto and OpenTopoMap-derived retina maps.

### Mobile Maps

* [OsmAnd](https://osmand.net) - Map viewing and navigation (routing) application with offline functionality available for Android and iOS. (Android, iOS / [Source Code Android](https://github.com/osmandapp/OsmAnd) / [Source Code iOS](https://github.com/osmandapp/OsmAnd-iOS) / [Wiki](https://wiki.openstreetmap.org/wiki/OsmAnd))
* [Organic Maps](https://organicmaps.app/) - A free offline maps app based on OSM. (Android, iOS / [Source Code](https://github.com/organicmaps/organicmaps) / [Wiki](https://wiki.openstreetmap.org/wiki/Organic_Maps))
* [Magic Earth](https://www.magicearth.com/) - A free turn-by-turn navigation app. (Android, iOS / [Wiki](https://wiki.openstreetmap.org/wiki/Magic_Earth))
* [Komoot](https://www.komoot.com/) - A route planner and navigation app specializing in hiking and cycling. ([Android](https://market.android.com/details?id=de.komoot.android), [iOS](https://itunes.apple.com/de/app/id447374873?mt=8) / [Wiki](https://wiki.openstreetmap.org/wiki/Komoot))

### Generators

* [MyOSMatic](https://print.get-map.org/new/) - Website for generating printable street maps from OSM data. ([Source Code](https://github.com/hholzgra/maposmatic/))
* [Field Papers](http://fieldpapers.org/) - Generate maps for printing, annotate them, and manage your notes after. ([Source Code](https://github.com/fieldpapers/fieldpapers) / [Wiki](https://wiki.openstreetmap.org/wiki/Field_Papers))

### Map Styles

* [Terrain Classic](https://github.com/stamen/terrain-classic) - World-wide CartoCSS port of Stamen's classic terrain style.

### Map Games

* [Back Of Your Hand](https://backofyourhand.com/) - A web map game that tests your knowledge by having you find a street in a given area. ([Source Code](https://github.com/adam-lynch/back-of-your-hand))
* [PraxisMapper](https://github.com/drakewill-CRL/PraxisMapper) - GPS Game server, for making mobile games around exploring the real world. ([Source Code](https://github.com/drakewill-CRL/PraxisMapper))

### Goal Tracking

The services in this category allow you to track personal and fitness goals utilizing OpenStreetMap data.

* [CityStrides](https://citystrides.com/) - A web platform that encourages the user to run every street in their city. Based on your Strava data it shows where you have and have not run, provides challenges, a leaderboard, and a forum.

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
* [prettymapp](https://github.com/chrieke/prettymapp) - Create beautiful maps from OpenStreetMap data.

### Java

* [OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner) - Open source multi-modal trip planner. ([Wiki](https://wiki.openstreetmap.org/wiki/OpenTripPlanner))
* [GraphHopper](https://github.com/graphhopper/graphhopper) - Open source route planning library and server using OpenStreetMap. ([Wiki](https://wiki.openstreetmap.org/wiki/GraphHopper))
* [OSM2World](http://osm2world.org) - OSM2World is a converter that creates three-dimensional models of the world from OpenStreetMap data. It can be used as a stand-alone tool, on a server or as a library in Java programs. ([Source Code](https://github.com/tordanik/OSM2World) / [Wiki](https://wiki.openstreetmap.org/wiki/OSM2World))

## Public APIs

* [overpass](http://overpass-api.de) - Read-only API that serves up custom selected parts of the OSM map data. ([Source Code](https://github.com/drolbr/Overpass-API) / [Wiki](https://wiki.openstreetmap.org/wiki/Overpass_API))
* [osm.mazdermind](https://osm.mazdermind.de/replicate-sequences/) - Maps Timestamp to replicate sequences. ([Source Code](https://github.com/MaZderMind/replicate-sequences))
* [planet.osm](http://planet.osm.org) - Minutely/weekly/yearly/full dumps of osm data. ([Wiki](https://wiki.openstreetmap.org/wiki/Planet.osm))
* [bbbike](https://extract.bbbike.org) - Custom extracts of areas from planet.osm. ([Wiki](https://wiki.openstreetmap.org/wiki/BBBike_@_World))
* [OSMCha API](https://osmcha.org/api-docs/) - Powerful API that allows to query and retrieve changeset information. ([Source Code](https://github.com/willemarcel/osmcha-django))

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

* [LearnOSM.org](https://learnosm.org/en/beginner/) - Extensive beginners' guide to editing OpenStreetMap. ([Wiki](https://wiki.openstreetmap.org/wiki/LearnOSM))
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

[^selfhosted-only]: This project does not provide a hosted instance and has to be self-deployed. Refer to the project's website for instructions.
