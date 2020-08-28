# What's New

**osm-community-index** is an open source project. You can submit bug reports, help out,
or learn more by visiting our project page on GitHub:  :octocat: https://github.com/osmlab/osm-community-index

Please star our project on GitHub to show your support! :star:

_Breaking changes, which may affect downstream projects, are marked with a_ :warning:


<!--
# A.B.C
##### YYYY-MMM-DD

* Added resources:
* Added events:
* Updated:

[#xxx]: https://github.com/osmlab/osm-community-index/issues/xxx
-->

# 2.1.1
##### 2020-Apr-13

* Support new resource type `xmpp` ([#347])
* Added resources:
  * Croatia forum, wiki, website ([#346])
  * OSM Japan Slack ([#343])
  * Mailing list and Twitter for DE:Mecklenburg-Western Pomerania ([#342])
  * OSM Greek resources ([#339])
  * Talk-tz mailing list (Tanzania) ([#337])
  * Talk-africa mailing list ([#335])
  * OSM FR-BZH + FR-35 channels ([#330])
* Updated:
  * Fix boundaries of Isle of Man, Guernsey, and Jersey ([#333])
  * Add a custom geojson for Ireland, and use it for Irish resources ([#332])
  * Update URL for YouthMappers George Mason University ([#331])
  * Fix UK East Midlands and Brazil Riograndedosul geojsons ([#329])
  * Fix Ukraine boundary ([#328])
* Removed:
  * OSM-Vancouver-meetup ([#327])

[#327]: https://github.com/osmlab/osm-community-index/issues/327
[#328]: https://github.com/osmlab/osm-community-index/issues/328
[#329]: https://github.com/osmlab/osm-community-index/issues/329
[#330]: https://github.com/osmlab/osm-community-index/issues/330
[#331]: https://github.com/osmlab/osm-community-index/issues/331
[#332]: https://github.com/osmlab/osm-community-index/issues/332
[#333]: https://github.com/osmlab/osm-community-index/issues/333
[#335]: https://github.com/osmlab/osm-community-index/issues/335
[#337]: https://github.com/osmlab/osm-community-index/issues/337
[#339]: https://github.com/osmlab/osm-community-index/issues/339
[#342]: https://github.com/osmlab/osm-community-index/issues/342
[#343]: https://github.com/osmlab/osm-community-index/issues/343
[#346]: https://github.com/osmlab/osm-community-index/issues/346
[#347]: https://github.com/osmlab/osm-community-index/issues/347


# 2.0.0
##### 2020-Jan-15

* Updated:
  * :warning: Build environment now requires Node 10 or greater.
  * :warning: New approach to specifying locations introduces some breaking changes but shrinks the data significantly. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.  ([#298], [#291])
    * Resource files now use a `locationSet` property to make it easier to specify where the resources are included and excluded.
    * Removed: `countryCodes` properties
    * Removed: `featureId` properties and most `.geojson` files (everything that was just a country or a circular point is now gone, as it can be calculated)
    * This approach leverages code from [country-coder](https://github.com/ideditor/country-coder) and [location-conflation](https://github.com/ideditor/location-conflation) projects.
    * `dist/features.json` is now a FeatureCollection that only contains the _custom_ boundaries.
  * You can now view the community index data on a map at http://openstreetmap.community

[#291]: https://github.com/osmlab/osm-community-index/issues/291
[#298]: https://github.com/osmlab/osm-community-index/issues/298

* Added resources:
  * Many Telegram channels from the OSM wiki ([#220])
  * OSM Italy Piemonte resources ([#313])
  * AASTU Youth Mappers and OSM Ethiopia Telegram ([#321], [#317])
  * Mapeado Colaborativo, Geoinquietos Zaragoza ([#325])
  * Moldova OSM Telegram group and Google Groups group ([#326])
  * OSM Latin America Resources ([#324])
  * OSM Viersen meetup ([#320])
  * OSM South Africa Twitter and Mailing List ([#318])
  * OSM Slovak resources ([#310])
  * OSM Germany Matrix ([#308], [#307])
  * OSM Kerala resources ([#288], [#290], [#304])
  * OSM Bulgaria resources ([#303])
  * MappingWR Waterloo ([#302])
  * OSM Spain and OSM Albania Twitter accounts ([#301])
  * OSM China Telegram ([#294])
  * OSM Hungary Matrix ([#299])

[#220]: https://github.com/osmlab/osm-community-index/issues/220
[#288]: https://github.com/osmlab/osm-community-index/issues/288
[#290]: https://github.com/osmlab/osm-community-index/issues/290
[#294]: https://github.com/osmlab/osm-community-index/issues/294
[#299]: https://github.com/osmlab/osm-community-index/issues/299
[#301]: https://github.com/osmlab/osm-community-index/issues/301
[#302]: https://github.com/osmlab/osm-community-index/issues/302
[#303]: https://github.com/osmlab/osm-community-index/issues/303
[#304]: https://github.com/osmlab/osm-community-index/issues/304
[#307]: https://github.com/osmlab/osm-community-index/issues/307
[#308]: https://github.com/osmlab/osm-community-index/issues/308
[#310]: https://github.com/osmlab/osm-community-index/issues/310
[#313]: https://github.com/osmlab/osm-community-index/issues/313
[#317]: https://github.com/osmlab/osm-community-index/issues/317
[#318]: https://github.com/osmlab/osm-community-index/issues/318
[#320]: https://github.com/osmlab/osm-community-index/issues/320
[#321]: https://github.com/osmlab/osm-community-index/issues/321
[#324]: https://github.com/osmlab/osm-community-index/issues/324
[#325]: https://github.com/osmlab/osm-community-index/issues/325
[#326]: https://github.com/osmlab/osm-community-index/issues/326

* Updated resources:
  * OSM Kosovo ([#312], [#323])
  * Fixed location of Rio Grande do Sol ([#315])
  * Fixed typo and boundary polygon for UK East Midlands ([#314])
  * Update contact and add Telegram for OSM Ghana ([#306])
  * Fixed boundary polygon for Northern Scotland ([#297])
  * Fixed several Canadian resources ([#296])
  * Fixed language codes `ua`->`uk` for Ukranian ([#292])
  * Bump OSM Poland forum priority ([#287])

[#287]: https://github.com/osmlab/osm-community-index/issues/287
[#292]: https://github.com/osmlab/osm-community-index/issues/292
[#296]: https://github.com/osmlab/osm-community-index/issues/296
[#297]: https://github.com/osmlab/osm-community-index/issues/297
[#306]: https://github.com/osmlab/osm-community-index/issues/306
[#312]: https://github.com/osmlab/osm-community-index/issues/312
[#314]: https://github.com/osmlab/osm-community-index/issues/314
[#315]: https://github.com/osmlab/osm-community-index/issues/315
[#323]: https://github.com/osmlab/osm-community-index/issues/323

* Added events:
  * State of the Map 2020 ([#322], [#319])

[#322]: https://github.com/osmlab/osm-community-index/issues/322
[#319]: https://github.com/osmlab/osm-community-index/issues/319


# 1.0.0
##### 2019-Oct-23

* New:
  * Features now include an automatically calculated `area` property, making it easier for downstream projects to sort resources by area ([#286])
    * :warning: This new property breaks backward compatibility of the `combined.geojson` files.
  * Add an `osm-lc` type and `osm-lc.svg` icon for official OSM Local Chapters (see [#1])
  * Resources now support an `order` property, to allow communities to control how their resources are sorted ([#114])
  * Resource `contacts` property is now optional

[#286]: https://github.com/osmlab/osm-community-index/issues/286
[#114]: https://github.com/osmlab/osm-community-index/issues/114
[#1]: https://github.com/osmlab/osm-community-index/issues/1

* Added resources:
  * Several Telegram groups: OSM Africa, Bosnia-Herzegovina, Japan, Taiwan, DE-Hamburg, France, Netherlands, Israel, Saudi Arabia ([#220])
  * Map Kibera, OSM Kenya ([#278], [#279])
  * OSM Ukraine ([#277])
  * OSM Ireland ([#275], [#282])
  * OSM Scotland ([#271], [#283])
  * OSM Galicia ([#265], [#266], [#267], [#268])
  * OSM Netherlands ([#264], [#270], [#274])
  * OSM Switzerland ([#262], [#263], [#284])
  * OSM Belgium ([#255], [#256], [#257], [#258], [#259], [#260], [#269])

[#220]: https://github.com/osmlab/osm-community-index/issues/220
[#255]: https://github.com/osmlab/osm-community-index/issues/255
[#256]: https://github.com/osmlab/osm-community-index/issues/256
[#257]: https://github.com/osmlab/osm-community-index/issues/257
[#258]: https://github.com/osmlab/osm-community-index/issues/258
[#259]: https://github.com/osmlab/osm-community-index/issues/259
[#260]: https://github.com/osmlab/osm-community-index/issues/260
[#261]: https://github.com/osmlab/osm-community-index/issues/261
[#262]: https://github.com/osmlab/osm-community-index/issues/262
[#263]: https://github.com/osmlab/osm-community-index/issues/263
[#264]: https://github.com/osmlab/osm-community-index/issues/264
[#265]: https://github.com/osmlab/osm-community-index/issues/265
[#266]: https://github.com/osmlab/osm-community-index/issues/266
[#267]: https://github.com/osmlab/osm-community-index/issues/267
[#268]: https://github.com/osmlab/osm-community-index/issues/268
[#269]: https://github.com/osmlab/osm-community-index/issues/269
[#270]: https://github.com/osmlab/osm-community-index/issues/270
[#271]: https://github.com/osmlab/osm-community-index/issues/271
[#274]: https://github.com/osmlab/osm-community-index/issues/274
[#275]: https://github.com/osmlab/osm-community-index/issues/275
[#277]: https://github.com/osmlab/osm-community-index/issues/277
[#278]: https://github.com/osmlab/osm-community-index/issues/278
[#279]: https://github.com/osmlab/osm-community-index/issues/279
[#282]: https://github.com/osmlab/osm-community-index/issues/282
[#283]: https://github.com/osmlab/osm-community-index/issues/283
[#284]: https://github.com/osmlab/osm-community-index/issues/284

* Added events:
  * SOTM Asia 2019 ([#280], [#281])

[#280]: https://github.com/osmlab/osm-community-index/issues/280
[#281]: https://github.com/osmlab/osm-community-index/issues/281

* Removed resources:
  * OSM NYC ([#252])

[#252]: https://github.com/osmlab/osm-community-index/issues/252

* Updated:
  * Simplify several features and cleanup seams:  India, Venezuela, France, Netherlands, Galicia, Belgium, Switzerland, Luxembourg, Iceland, Portugal, Asia/Africa border
  * Simplify all of the YouthMappers chapter circular boundaries
  * Make a `middle-east` folder and move Jordan, Saudi Arabia, Israel into it
  * Fix name of Khulna University YouthMappers (was just named "OpenStreetMap" before)
  * Fix typo `nugeria` -> `nigeria`
  * Cleanup and simplify YouthMappers logo ([#285])
  * Include Sardinia in Italy feature ([#261])
  * Korean resources now use a single polygon including both North and South ([#254])

[#254]: https://github.com/osmlab/osm-community-index/issues/254
[#261]: https://github.com/osmlab/osm-community-index/issues/261
[#285]: https://github.com/osmlab/osm-community-index/issues/285


# 0.12.0
##### 2019-Aug-26

* Updates:
  * Refine the outlines of UPRI and FeuTech YouthMappers regions [#248], [#249])

[#248]: https://github.com/osmlab/osm-community-index/issues/248
[#249]: https://github.com/osmlab/osm-community-index/issues/249


# 0.11.0
##### 2019-Aug-01

* Distribute `combined.geojson` containing all resources and features
(useful for displaying everything on a map, re: [#79])

[#79]: https://github.com/osmlab/osm-community-index/issues/79


# 0.10.0
##### 2019-Jul-26

* Add resources:
  * Add resources for OSM Nicaragua ([#246])
  * Add GeoGeeks Western Australia and GeoGeeks Perth ([#243], [#244])
  * Add resources for OSM Venezuela ([#242])
  * Add resources for OSM Luxembourg ([#239])

* Updates:
  * Fix Chile boundary multipolygon

[#239]: https://github.com/osmlab/osm-community-index/issues/239
[#242]: https://github.com/osmlab/osm-community-index/issues/242
[#243]: https://github.com/osmlab/osm-community-index/issues/243
[#244]: https://github.com/osmlab/osm-community-index/issues/244
[#246]: https://github.com/osmlab/osm-community-index/issues/246


# 0.9.0
##### 2019-Jun-30

* Add resources:
  * Add resources for OSM Portugal ([#235])

* Updates:
  * Fix URL for NYU Mobile Health YouthMappers ([#238])

[#238]: https://github.com/osmlab/osm-community-index/issues/238
[#235]: https://github.com/osmlab/osm-community-index/issues/235

## 0.8.0
##### 2019-Jun-17

* Update Resources:
  * Maptime Australia -> Maptime Oceania, add talk-nz ([#232])

* Add Resources:
  * Add OpenStreetMap Uruguay ([#227])

[#232]: https://github.com/osmlab/osm-community-index/issues/232
[#227]: https://github.com/osmlab/osm-community-index/issues/227


## 0.7.0
##### 2019-May-21

* New Features:
  * Add all YouthMappers chapters, and support for `youthmappers` community type ([#224], [#152])

* Add Resources:
  * Add OpenStreetMap Slovenia Twitter ([#226])

* Add events:
  * State of the Map US 2019

[#226]: https://github.com/osmlab/osm-community-index/issues/226
[#224]: https://github.com/osmlab/osm-community-index/issues/224
[#152]: https://github.com/osmlab/osm-community-index/issues/152


## 0.6.0
##### 2019-Jan-23

* New Features:
  * Add support for `aparat` community type ([#212])

* Add Resources:
  * Add Norwegian Telegram ([#213])
  * Add Iran resources: Telegram, Aparat, Forum ([#210])
  * A few renames: "Korea" -> "South Korea",  "Srilanka" -> "Sri Lanka" ([#205], [#206])
  * OSM Asia community ([#203])

[#213]: https://github.com/osmlab/osm-community-index/issues/213
[#212]: https://github.com/osmlab/osm-community-index/issues/212
[#210]: https://github.com/osmlab/osm-community-index/issues/210
[#206]: https://github.com/osmlab/osm-community-index/issues/206
[#205]: https://github.com/osmlab/osm-community-index/issues/205
[#203]: https://github.com/osmlab/osm-community-index/issues/203


## 0.5.0
##### 2018-Dec-03

* New features:
  * Add support for new community types `github`, `osm`, `wiki`, `youtube` ([#200])
* Add resources:
  * Add resources for OSM India ([#198], [#199])
* Remove resources:
  * Remove Maptime Belgium ([#197])

[#200]: https://github.com/osmlab/osm-community-index/issues/200
[#199]: https://github.com/osmlab/osm-community-index/issues/199
[#198]: https://github.com/osmlab/osm-community-index/issues/198
[#197]: https://github.com/osmlab/osm-community-index/issues/197


## 0.4.8
##### 2018-Nov-26

* Add community resources:
  * Add Kosovo Telegram group ([#194])
  * Add Maptime HRVA Twitter ([#191])
  * Add polygons for several Indian states ([#186], [#187], [#188], [#189], [#190])
  * Add link to IRC channel ([#181])
  * Add link to Discord ([#183])
* Updates:
  * Fix croatia.geojson from LineString to Polygon ([#195])
  * Update Puducherry, India OSM community's mailing list ([#185])
  * Switch IRC links to use webchat.oftc.net ([#136], [#184])
  * Fix OSM-LATAM bounding polygon ([iD#5282])

[#194]: https://github.com/osmlab/osm-community-index/issues/194
[#191]: https://github.com/osmlab/osm-community-index/issues/191
[#190]: https://github.com/osmlab/osm-community-index/issues/190
[#189]: https://github.com/osmlab/osm-community-index/issues/189
[#188]: https://github.com/osmlab/osm-community-index/issues/188
[#187]: https://github.com/osmlab/osm-community-index/issues/187
[#186]: https://github.com/osmlab/osm-community-index/issues/186
[#183]: https://github.com/osmlab/osm-community-index/issues/183
[#181]: https://github.com/osmlab/osm-community-index/issues/181
[#195]: https://github.com/osmlab/osm-community-index/issues/195
[#185]: https://github.com/osmlab/osm-community-index/issues/185
[#184]: https://github.com/osmlab/osm-community-index/issues/184
[#136]: https://github.com/osmlab/osm-community-index/issues/136
[iD#5282]: https://github.com/openstreetmap/iD/issues/5282


## 0.4.7
##### 2018-Aug-26

* Add community resources:
  * OSM Rio Grande Telegram Group ([#176])
  * OSM LATAM ([#171], [#172])
  * Iceland ([#170])
  * Botswana ([#170])
* Add events:
  * State of the Map LATAM 2018
* Updates:
  * Update OSM-US Slack join URL ([#169])

[#176]: https://github.com/osmlab/osm-community-index/issues/176
[#172]: https://github.com/osmlab/osm-community-index/issues/172
[#171]: https://github.com/osmlab/osm-community-index/issues/171
[#170]: https://github.com/osmlab/osm-community-index/issues/170
[#169]: https://github.com/osmlab/osm-community-index/issues/169


## 0.4.6
##### 2018-Jul-26

* Add community resources:
  * Talk-us-massachusetts mailing list ([#168])
  * Portland, Oregon Google group ([#167])

[#168]: https://github.com/osmlab/osm-community-index/issues/168
[#167]: https://github.com/osmlab/osm-community-index/issues/167


## 0.4.5
##### 2018-Jun-25

* Add community resources:
  * Slovenia ([#161])
  * Croatia ([#158])
* Add events:
  * State of the Map US 2018 ([#164])

[#164]: https://github.com/osmlab/osm-community-index/issues/164
[#161]: https://github.com/osmlab/osm-community-index/issues/161
[#158]: https://github.com/osmlab/osm-community-index/issues/158


## 0.4.4
##### 2018-Jun-13

* Add community resources:
  * Czech web, Facebook, Twitter ([#156])
  * German Telegram supergroup ([#155])
  * OSM global Telegram supergroup ([#154])
  * Thailand Facebook page ([#153])
* Fixes:
  * Fix contact email address for OSM Korea Telegram contact ([#151])
  * Simplified Maptime Albania-Tirana polygon ([#149])

[#156]: https://github.com/osmlab/osm-community-index/issues/156
[#155]: https://github.com/osmlab/osm-community-index/issues/155
[#154]: https://github.com/osmlab/osm-community-index/issues/154
[#153]: https://github.com/osmlab/osm-community-index/issues/153
[#151]: https://github.com/osmlab/osm-community-index/issues/151
[#149]: https://github.com/osmlab/osm-community-index/issues/149


## 0.4.3
##### 2018-May-14
* Fixes:
  * Fix Maptime Tirana polygon ([#147])

[#147]: https://github.com/osmlab/osm-community-index/issues/147


## 0.4.2
##### 2018-May-14
* Add community resources:
  * Finland ([#146])
  * OSM Italy Telegram ([#144])
  * OSM Hungary Meetup ([#143])
  * OSM Belgium Maptime ([#142])
  * Albania ([#141])
  * Chiang Mai, Thailand Meetup ([#139])
  * Thailand ([#138])
  * OSM UK feature polygons ([#137])
  * OSM Paraguay Telegram ([#134])
  * OSM Ecuador Telegram ([#133])
  * OSM Cuba Telegram ([#132])
  * OSM Nicuragua Telegram ([#131])
  * OSM Colombia Telegram ([#130])
  * Several Belgium resources and improvements ([#126], [#125], [#120])
  * OSM.jp Website ([#124])
  * OSM Malaysia Facebook ([#119])
  * Germany Ostwestfalen mailing lists ([#118])
  * Hungary ([#116])
  * Denmark ([#115])
* Fixes:
  * Replace irc2go links with irc.openstreetmap.org links ([#136])
  * Fix OSM Bangladesh url ([#128])
  * Fix OSM Berlin Meetup url ([#122])
  * Fix OSM Brazil Meetup time ([#121])

[#146]: https://github.com/osmlab/osm-community-index/issues/146
[#144]: https://github.com/osmlab/osm-community-index/issues/144
[#143]: https://github.com/osmlab/osm-community-index/issues/143
[#142]: https://github.com/osmlab/osm-community-index/issues/142
[#141]: https://github.com/osmlab/osm-community-index/issues/141
[#139]: https://github.com/osmlab/osm-community-index/issues/139
[#138]: https://github.com/osmlab/osm-community-index/issues/138
[#137]: https://github.com/osmlab/osm-community-index/issues/137
[#136]: https://github.com/osmlab/osm-community-index/issues/136
[#134]: https://github.com/osmlab/osm-community-index/issues/134
[#133]: https://github.com/osmlab/osm-community-index/issues/133
[#132]: https://github.com/osmlab/osm-community-index/issues/132
[#131]: https://github.com/osmlab/osm-community-index/issues/131
[#130]: https://github.com/osmlab/osm-community-index/issues/130
[#128]: https://github.com/osmlab/osm-community-index/issues/128
[#126]: https://github.com/osmlab/osm-community-index/issues/126
[#125]: https://github.com/osmlab/osm-community-index/issues/125
[#124]: https://github.com/osmlab/osm-community-index/issues/124
[#122]: https://github.com/osmlab/osm-community-index/issues/122
[#121]: https://github.com/osmlab/osm-community-index/issues/121
[#120]: https://github.com/osmlab/osm-community-index/issues/120
[#119]: https://github.com/osmlab/osm-community-index/issues/119
[#118]: https://github.com/osmlab/osm-community-index/issues/118
[#116]: https://github.com/osmlab/osm-community-index/issues/116
[#115]: https://github.com/osmlab/osm-community-index/issues/115


## 0.4.1
##### 2018-Apr-24
* Add community resources:
  * Brasilia Telegram ([#112])
  * Facebook, Twitter, OSMF, and help.openstreetmap.com ([#103])
  * Korean Telegram ([#110])
  * UK East and West Midlands meetups, talk-gb and irc channel ([#102], [#107])
  * OSM Graz ([#106])
  * talk-it-trentino and talk-it-southtyrol mailing lists ([#104], [#105])
  * Berlin, Germany ([#100])
  * Italy ([#99])
  * Bolivia ([#98])
  * Peru ([#97])
  * Austria web forum ([#96])
  * Sweden ([#87], [#95])
  * Norway ([#94])
  * Updates to Argentina resources ([#91], [#92])
  * Puducherry, India ([#89])
  * Malaysia ([#86])
  * Colombia ([#85])
  * Ghana ([#84])
  * France ([#83])
  * Spain talk-es ([#81])
  * Belgium meetup groups ([#76])
  * Myanmar ([#75])
* Add events:
  * Brazilian meetups ([#112])
  * State of the Map World 2018
  * State of the Map Asia 2018 ([#88])

[#112]: https://github.com/osmlab/osm-community-index/issues/112
[#110]: https://github.com/osmlab/osm-community-index/issues/110
[#107]: https://github.com/osmlab/osm-community-index/issues/107
[#106]: https://github.com/osmlab/osm-community-index/issues/106
[#105]: https://github.com/osmlab/osm-community-index/issues/105
[#104]: https://github.com/osmlab/osm-community-index/issues/104
[#103]: https://github.com/osmlab/osm-community-index/issues/103
[#102]: https://github.com/osmlab/osm-community-index/issues/102
[#100]: https://github.com/osmlab/osm-community-index/issues/100
[#99]: https://github.com/osmlab/osm-community-index/issues/99
[#98]: https://github.com/osmlab/osm-community-index/issues/98
[#97]: https://github.com/osmlab/osm-community-index/issues/97
[#96]: https://github.com/osmlab/osm-community-index/issues/96
[#95]: https://github.com/osmlab/osm-community-index/issues/95
[#94]: https://github.com/osmlab/osm-community-index/issues/94
[#92]: https://github.com/osmlab/osm-community-index/issues/92
[#91]: https://github.com/osmlab/osm-community-index/issues/91
[#89]: https://github.com/osmlab/osm-community-index/issues/89
[#88]: https://github.com/osmlab/osm-community-index/issues/88
[#87]: https://github.com/osmlab/osm-community-index/issues/87
[#86]: https://github.com/osmlab/osm-community-index/issues/86
[#85]: https://github.com/osmlab/osm-community-index/issues/85
[#84]: https://github.com/osmlab/osm-community-index/issues/84
[#83]: https://github.com/osmlab/osm-community-index/issues/83
[#81]: https://github.com/osmlab/osm-community-index/issues/81
[#76]: https://github.com/osmlab/osm-community-index/issues/76
[#75]: https://github.com/osmlab/osm-community-index/issues/75


## 0.4.0
##### 2018-Apr-16
* Add community resources:
  * Germany ([#69], [#72])
  * Rome and Lazio meetups ([#68], [#67])
  * Austria ([#64])
  * Chile ([#56], [#57], [#58], [#59])
  * OSM-CA Slack and OSM Ottawa meetup ([#63], [#51])
  * Madagascar ([#53])
  * MapMinnesota ([#55])
  * Bangladesh, India, Indonesia, Mongolia, Nepal, Sri Lanka ([#48])
  * Brazil and Bahia ([#47])
  * Update Australia geojson and add mailing list ([#45])
* Add geojson-precision, drop precison of geojsons to 5 digits ([#70])
* Validate that event dates are pareseable ([#62])
* Fix winding order of all geojsons
* Support types "discord" and "matrix" (e.g. riot chat) ([#49])

[#72]: https://github.com/osmlab/osm-community-index/issues/72
[#70]: https://github.com/osmlab/osm-community-index/issues/70
[#69]: https://github.com/osmlab/osm-community-index/issues/69
[#68]: https://github.com/osmlab/osm-community-index/issues/68
[#67]: https://github.com/osmlab/osm-community-index/issues/67
[#64]: https://github.com/osmlab/osm-community-index/issues/64
[#63]: https://github.com/osmlab/osm-community-index/issues/63
[#62]: https://github.com/osmlab/osm-community-index/issues/62
[#59]: https://github.com/osmlab/osm-community-index/issues/59
[#58]: https://github.com/osmlab/osm-community-index/issues/58
[#57]: https://github.com/osmlab/osm-community-index/issues/57
[#56]: https://github.com/osmlab/osm-community-index/issues/56
[#55]: https://github.com/osmlab/osm-community-index/issues/55
[#53]: https://github.com/osmlab/osm-community-index/issues/53
[#51]: https://github.com/osmlab/osm-community-index/issues/51
[#49]: https://github.com/osmlab/osm-community-index/issues/49
[#48]: https://github.com/osmlab/osm-community-index/issues/48
[#47]: https://github.com/osmlab/osm-community-index/issues/47
[#45]: https://github.com/osmlab/osm-community-index/issues/45


## 0.3.0
##### 2018-Apr-03
* Add several communities:
  * Czech Republic ([#43])
  * Spain ([#44])
  * Taiwan ([#42], [#41])
  * Japan ([#40])
  * Vancouver, BC ([#39])
  * Argentina ([#38])
  * Belarus ([#33])
  * India ([#28])
  * Many metro regions around US ([#27])
  * Australia ([#17])
  * Russia ([#11])
  * Philippines ([#9])
* Add FontAwesome icons for each resource type (see [#1], [#31])
* Add support for tracking events ([#25])
* Resources don't require `featureId` anymore (world resources won't have one)
* Separate "url" (required) and "signupUrl" (optional) ([#20])
* Include both "description" (one line) and "extendedDescription" ([#20])
* Add upcoming events ([#25])

[#44]: https://github.com/osmlab/osm-community-index/issues/44
[#43]: https://github.com/osmlab/osm-community-index/issues/43
[#42]: https://github.com/osmlab/osm-community-index/issues/42
[#41]: https://github.com/osmlab/osm-community-index/issues/41
[#40]: https://github.com/osmlab/osm-community-index/issues/40
[#39]: https://github.com/osmlab/osm-community-index/issues/39
[#38]: https://github.com/osmlab/osm-community-index/issues/38
[#33]: https://github.com/osmlab/osm-community-index/issues/33
[#31]: https://github.com/osmlab/osm-community-index/issues/31
[#28]: https://github.com/osmlab/osm-community-index/issues/28
[#27]: https://github.com/osmlab/osm-community-index/issues/27
[#25]: https://github.com/osmlab/osm-community-index/issues/25
[#20]: https://github.com/osmlab/osm-community-index/issues/20
[#17]: https://github.com/osmlab/osm-community-index/issues/17
[#11]: https://github.com/osmlab/osm-community-index/issues/11
[#9]: https://github.com/osmlab/osm-community-index/issues/9
[#1]: https://github.com/osmlab/osm-community-index/issues/1


## 0.2.0
##### 2018-Mar-19
* Don't check in built files on master ([#26])
* Automatically prettify source JSON files ([#22])
* Raise an error if we detect duplicate ids ([#21])

[#26]: https://github.com/osmlab/osm-community-index/issues/26
[#22]: https://github.com/osmlab/osm-community-index/issues/22
[#21]: https://github.com/osmlab/osm-community-index/issues/21

## 0.1.0
##### 2018-Mar-14
* Add languageCodes to track languages spoken. ([#6])
* Require points of contact for resources ([#12])
* Separate data (resources) and polygons (features) ([#7])

[#12]: https://github.com/osmlab/osm-community-index/issues/12
[#7]: https://github.com/osmlab/osm-community-index/issues/7
[#6]: https://github.com/osmlab/osm-community-index/issues/6
