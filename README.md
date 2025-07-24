# IfcSplitAndMerge
Split and merge IFC files



### Current features:
- Load IFC file
- 3D view of loaded model
- Select elements in 3D view through single click or rubberband
- Select elements in tree view
- Find and select entities by Express ID or GUID via text input
- Write IFC file with selected entities


### Planned features
- Find and select by name, type, property sets etc not implemented yet
- merging of several IFC models not implemented yet


![Screenshot 2025-06-30 123232](https://github.com/user-attachments/assets/34a9a284-23e4-4ca3-8655-f94291c215d5)


Free to use. Download under Releases on the right

### Use as SDK or base for other IFC applications

You can use this tool as a template for your own IFC application, or parts of it for other applications.
The source code is very clean and minimalistic, perfect for easy maintenance and further development.
In case you are interested, pleace contact info at ifcquery.com


### Credits:

this tool uses 
 - https://github.com/ThatOpen/engine_web-ifc for fast and robust loading and processing of IFC files.
 - Qt as GUI toolkit
 - OpenSceneGraph for the 3D view
