# highland-explorer
Peakbaggin application for the Southren 6000 and Beyond club

## Expectations

- Should alllow user to keep track of which Southren 6000ft peaks they've summited
    - Personal list of peaks summited
    - date
    - maybe store a picture?
- Provide information about each peak
    - name
    - location
        - mountain range/area
        - long/lat
    - height
    - approaches
        - trail inforamtion
        - trailhead long/lat

## Details

### Platform

Website:

- static info
    - but use angularjs to make a dynamic app, of course
- won't keep track of personal progress
- Cheap - can put a static site up on dropbox...done!
    - or better yet use amazon buckets!
- Can Be Mobile Responive

WebApp:

- Can Keep track of personal progress
- $$ Will need to host a webserver and DB
- Can be mobile responve

PhoneApp:

- Lots' of really cool features to use, such as geolocation
- $$ Will need to host a webserver and DB
- Will need to learn about App Development
- Compatiable across multiple devices

Plan of attack should be:

1. Make Website first with static info
2. Make a webApp second maybe use serverless backend and dynomo db
3. Learn and research for Iphone development, and then if it takes off, make an app for all devices!

### Domain

#### Mounatain

Information about the Mountain, _static_

- Name
- Location
- Beta
    - **Routes**
    - Conditions
    - Notes
- Official or Bonus
- Height
- List of **Trip Reports**

#### Person

Person who is using the app,  _dynamic_

- Name
- Id
- List of **Trip Reports**
- List of **Mountains** Bagged
- About me
- User Photo

#### Trip Report

A person's Personal Trip Report, _dynamic_

- **Mountain**
- **Person**
- Date Summited
- **Route** Used
- Notes
- Photo

#### Route

Information to reach the summit of mountain, _static => dynamic_

- Name
- gpx tracks
- Photos?
- Waypoints

## The Southern 6000 Beyond 40 (52)

### Roan Highlands 3

- Grassy Ridge 6160
- Roan High Knob 6285
- Roan High Bluff 6267

### Craggies 1

- Craggy Dome 6080

### Great Balsams 10

- Cold Mountain 6030
- Shining Rock 6040
- Grassy Cove Top 6040
- Tennent Mountain 6040
- Black Balsam Knob 6214
- Chestnut Bald 6040
- Sam Knob 6040
- Mt Hardy 6110
- Reinhart Knob 6080
- Richland Balsam 6410

### Plott Balsams 4 (5)

- Yellow Face 6032
- Waterrock Knob 6292
- Lyn Lowry 6240
- Plott Balsam 6088
- Browning Knob 6240 *

### Smokies 12 (17)

- Clingman’s Dome 6643
- Mt Collins 6188
- Mt LeConte 6593
- Mt Kephart 6217
- Mt Sequoyah 6003
- Mt Chapman 6417
- Tri Corner Knob/Mt Yonaguska 6120
- Mark’s Knob 6169
- Mt Guyot 6621
- Old Black 6370
- Big Cataloochee 6155
- Luftee Knob 6234
- Mt Buckley 6580 *
- Mt Love 6446 *
- Mt Hardison 6134 *
- Mt Ambler 6120 *
- Thermo Knob 6080 *

### Black Mountains 10 (16)

- Mt Mitchell 6684
- Mt Craig 6647
- Balsam Cone 6611
- Cattail Peak 6600
- Mt Gibbes 6571
- Big Tom 6560 *
- Clingmans Peak 6557 *
- Potato Hill 6475 *
- Potato Knob 6400 *
- Blackstock Knob 6359
- Celo Knob 6327
- Mt Hallback 6320
- Gibbs Mountain 6224
- Winter Star Mountain 6212
- Percys Peak 6200 *
- Patton Knob 6040 *
