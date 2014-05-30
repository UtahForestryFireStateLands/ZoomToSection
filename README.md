UTAH ZOOM TO SECTION TOOL.

This is an ArcGIS tool to focus the currently open map on a section within a township and range the user specifies. 

Instructions.

1.	Unzip the folder to where you keep your toolboxes in arcgis.
(C:\Users\Sean\Documents\ArcGIS is a popular default)
2.	While you have a map open in ArcGIS double click the script within the UtahZoomToSection toolbox.
3.	Enter the requested information (Township, Range, and Base Meridian).
4.	That’s it, this tool should work regardless of what .mxd you’re working from or where the tool was unzipped.

Notes.


1.	The tool will not zoom to any range or township ending in .5 but should zoom to the closest whole numbered range or township.
2.	If the section is not found the tool will zoom to the extent of Utah or the Great Salt Lake.
3.	If the included geodatabase is moved to a different directory from the toolbox or deleted the tool will cease to function. It will work to move both the toolbox and the geodatabase together.


Created by:
Sean Hirschi
shirschi@utah.gov
GIS Analyst
Forestry, Fire, and State Lands.
