## Custom Scenery for the Chicago and Milwaukee Areas

Custom scenery for the Chicago (KORD) and Milwaukee (KMKE) areas, for the FlightGear Flight Simulator. This includes:
- The airports recommended as of October 2020 from the X-Plane Scenery Gateway
- Area includes scenery between the following coordinates: 
  - min lat
  - max lat 42.5
  - min lon -
  - max lon - 
- Optional USGS orthophotos around major airports within the included area.

### NOTE: 
This scenery is best when used together with "Champaign" and "Oshkosh and UP" custom scenery. Use of these three custom sceneries together (KORD-KMKE-Custom-Scenery, Champaign-Custom-Scenery and NWI-UPM-Custom-Scenery) will minimize issues at the scenery borders. They also provide a signicant North-South flight area with decent scenery.

### Data Sources

- Airports: X-Plane Scenery Gateway: https://gateway.x-plane.com/
- Landcover: National landcover database (NLCD): https://www.usgs.gov/centers/eros/science/national-land-cover-database
- Elevation: Shuttle Radar Topology Mission 1-arc-second (SRTM-1), void-filled version: https://earthexplorer.usgs.gov/
- Rivers and waterbodies: National Hydrography Dataset (NHD): https://www.usgs.gov/core-science-systems/ngp/national-hydrography
- Buildings, roads, pylons, other objects: OpenStreetMap using osm2city: https://www.openstreetmap.org/ https://osm2city.readthedocs.io/en/latest/
- FlightGear TerraSync objects
- Orthophotos: USGS Orthophotos: https://earthexplorer.usgs.gov/

### To Download

To download the custom scenery files, go to the Releases page and download the zip archives.

## Installation

To install:
1) Create a directory on your local hard drive
2) Download Buildings.zip, Objects.zip, Pylons.zip, Roads.zip, Terrain.zip, and Orthophotos,zip 
3) Extract the files into the local directory you've created. 

For example, create a directory called "KORD-KMKE" on your computer. Extract the downloaded files into this directory. 

4) Add this directory to Additional Scenery Folders in the FlightGear GUI (launcher) 
5) To use the custom materials definitions and custom textures created:
    a) Download Illinois-data.zip and extract it. Rename the folder to "data.zip".
    b) Copy this "data" folder, open "$FG_ROOT" and paste. In Windows, this is the data folder within the FlightGear 2020.4 directory. This should result in Illinois.xml residing in the "$FG_ROOT/Materials/regions/" directory and a folder labeled "Illinois" in the "$FG_ROOT/Textures/Terrain/" directory.
 6) Start FlightGear. While on the start-up screen click "Add-ons". Scroll to the "Additional scenery folders" section, the click the plus (+) sign on the right side of the screen. A dialog box will pop up. Browse to the folder you created in step 1. Highlight the folder, then click "Select Folder". Confirm that the folder was added to the bottom of "Additional scenery folders". You can now highlight and move the folder to a higher priority if necessary. 
 7) Make the selections you want to use for your next flight then click "Fly", as usual.
 8) Rendering Options enable OSM buildings, detailed roads and pylons under 

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LGBudd/NLCD-Terrain/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
