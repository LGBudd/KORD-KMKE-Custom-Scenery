# Chicago and Milwaukee Area Custom Scenery
Custom NLCD scenery for the area covered by Chicago (including KORD, KMDW), Milwaukee (KMKE) and the surrounding suburbs.

## License
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.

## Chicago and Milwaukee Area Custom Scenery

Custom scenery for the Chicago (KORD) and Milwaukee (KMKE) areas, for the FlightGear Flight Simulator. This includes:
- Area airports recommended as of October 2020 from the X-Plane Scenery Gateway
- Area includes scenery between the following coordinates: 
  - min lat 41.5
  - max lat 44.0
  - min lon -89.0
  - max lon -87.0 

- Custom Material definitions and Textures for the area to make the land cover more realistic.
- Optional USGS orthophotos around major airports within the included area.
- Groundnets for major airports (KMDW, KMKE) have been uploaded to Terrasync and are included in the FlightGear database. A new Airports folder for KORD was created since the primary takeoff and landing runways at O'Hare have changed since WS2.0 was developed.
- Updated NavData for KORD should be downloaded and installed with this custom scenery. The updated airport uses this updated navigation data.

The zip archives were created using the TerraGear and TerraGear-GUI programs developed by the FlightGear project. The file repository on Google Drive includes the source data.

### NOTE: 
This scenery is best when used together with "Champaign" and "KOSH-KATW-KGRB_and_UP_Mich" custom scenery. Use of these three custom sceneries together (KORD-KMKE-Custom-Scenery, Champaign-Custom-Scenery and KOSH-KATW-KGRB_and_UP_Mich) will minimize issues at the scenery borders. They also provide a significant North-South flight area with NLCD land cover and (optional) photorealistic scenery.

### Data Sources

- Airports: X-Plane Scenery Gateway: https://gateway.x-plane.com/
- Landcover: National landcover database (NLCD): https://www.usgs.gov/centers/eros/science/national-land-cover-database
- Elevation: Shuttle Radar Topology Mission 1-arc-second (SRTM-1), void-filled version: https://earthexplorer.usgs.gov/
- Rivers and waterbodies: National Hydrography Dataset (NHD): https://www.usgs.gov/core-science-systems/ngp/national-hydrography
- Buildings, roads, pylons, other objects: OpenStreetMap using osm2city: https://www.openstreetmap.org/ https://osm2city.readthedocs.io/en/latest/
- FlightGear TerraSync objects
- Orthophotos: USGS Orthophotos: https://earthexplorer.usgs.gov/ Credit: U.S. Geological Survey. Color correction done by a first-time amateur.
- Runway additions/deletion at KORD, along with new NavData
- OSM2City worldbuild objects, since it was found that differences in elevation between WS2.0 scenery and this custom scenery were not significant.

### To Download

Note that the file KORD-KMKE_Data_Files.zip is quite large in size but is NOT NEEDED for the scenery, only for further development, should that be desired. It is not not needed unless you are a developer. 

The KORD_KMKE_Custom_Scenery files are available for download at the following link https://drive.google.com/drive/folders/1u5Y2KHQvpC88teBWVHXiXIJLXlnbitrz?usp=sharing. There you can download the following zip archives: Airports.zip, Buildings.zip, Objects.zip, Pylons.zip, Roads.zip, Details.zip, Terrain.zip and (optionally) Orthophotos.zip. You may also download custom materials definitions and textures in the file Illinois-data.zip, which should help make the scenery more realistic.

### To Install

1.  Create a directory on your local hard drive
1.  Download Buildings.zip, Objects.zip, Pylons.zip, Roads.zip, Details.zip, Terrain.zip, NavData.zip and (optionally) Orthophotos,zip 
1.  Extract the files into the local directory you've created. For example, create a directory called "KORD_KMKE_Custom_Scenery" on your computer. Extract the downloaded files into this directory. 
1.  Add this directory to Additional Scenery Folders in the FlightGear GUI (launcher)
1.  If you previously installed Champaign_Custom_Scenery skip to step 6, as you've already done this. Otherwise, to use the custom materials definitions and custom textures:
    1.  Download Illinois-data.zip and extract it. Rename the folder to "data.zip".
    1.  Copy this "data" folder, open "$FG_ROOT" and paste. In Windows, this is the data folder within the FlightGear $FG_ROOT directory. This should result in Illinois.xml residing in the "$FG_ROOT/Materials/regions/" directory and a folder labeled "Illinois" in the "$FG_ROOT/Textures/Terrain/" directory.
    1.  Copy the following: `<region include="Materials/regions/illinois.xml"/>`
    1.  Paste the above into the "materials.xml" file within the "North America" section and save "materials.xml". 
1.  Start FlightGear. While on the start-up screen click "Add-ons". Scroll to the "Additional scenery folders" section, then click the plus (+) sign on the right side of the screen. A dialog box will pop up. Browse to the folder you created in step 1. Highlight the folder, then click "Select Folder". Confirm that the folder was added to the bottom of "Additional scenery folders". You can now highlight and move the folder to a higher priority if necessary. NOTE: If using more than one of the three sceneries mentioned in the "Chicago and Milwaukee Area Custom Scenery" section above, you must order them as follows to minimize issues at the scenery borders: KOSH-KATW-KGRB_and_UP_Mich (top), KORD-KMKE (middle), and Champaign (bottom). 
1.  Make the selections you want to use for your next flight then click "Fly", as usual.
1.  Go to View, Rendering Options and make selections to enable Pylons and Power Lines, Detailed Roads and Railways, Buildings (OpenStreetMap Data), Random Scenery Objects, Autogenerated Vegetation, OpenStreetMap Trees, Vegetation Shadows, and Scenery Objects, as appropriate for good performance on your computer. 

### Southwest Airlines Traffic Files for KMDW
A traffic file for Southwest Airlines flights to and from Chicago Midway Airport (KMDW) were generated. To install the file:
1) extract the .zip file into a temporary directory of your choosing.
2) cut the SWA.xml file and past it into the \FlightGear [version]\data\AI\Traffic\S folder.

## Screenshots

### Approach to Chicago (with orthophotos)
![Chicago Downtown](https://github.com/LGBudd/KORD-KMKE-Custom-Scenery/blob/master/Screenshots/Chicago20210326174334.png)

### Chicago "Loop" (Downtown) (with orthophotos)
![Chicago](https://github.com/LGBudd/KORD-KMKE-Custom-Scenery/blob/master/Screenshots/ChicagoB.png)

### Takeoff from Milwaukee (KMKE) (with orthophotos
![Takeoff from Milwaukee (KMKE)](https://github.com/LGBudd/KORD-KMKE-Custom-Scenery/blob/master/Screenshots/Takeoff%20from%20KMKE%203.png)

### Looking to the South of Milwaukee (with orthophotos)
![South of Milwaukee](https://github.com/LGBudd/KORD-KMKE-Custom-Scenery/blob/master/Screenshots/Looking%20to%20%20the%20South%20from%20Milwaukee.png)
