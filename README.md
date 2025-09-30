# IfcSplitAndMerge
Split and merge IFC files



### Current features:
- Load IFC file
- 3D view of loaded model
- Mesh compression (deduplication, quantization) for efficient rendering of large meshes.
- Select elements in 3D view through single click or rubberband
- Select elements in tree view
- Find and select entities by STEP ID (local ID, unique in each file) or GUID (globally unique ID) via text input
- Write IFC file with selected entities


### Planned features
- Find and select by name, type, property sets etc not implemented yet
- merging of several IFC models not implemented yet


![Screenshot 2025-06-30 123232](https://github.com/user-attachments/assets/34a9a284-23e4-4ca3-8655-f94291c215d5)


<img width="2550" height="1696" alt="image" src="https://github.com/user-attachments/assets/d92d3dba-26e6-4eed-8cf7-1b3d33e8e489" />

#### Select elements:
<img width="2546" height="1691" alt="image" src="https://github.com/user-attachments/assets/b1f83793-1621-4f88-8231-9c1a35b141a3" />

#### Write file with selected elements:
<img width="2550" height="667" alt="image" src="https://github.com/user-attachments/assets/66fa768f-4237-45de-a3cb-7cf6d66632bf" />

#### Result: IFC file with only the selected elements:
<img width="2547" height="812" alt="image" src="https://github.com/user-attachments/assets/c36d59b5-1a8e-451e-9f15-ad72d14ab5b8" />


Free to use. Download under Releases on the right

### Use as SDK or base for other IFC applications

You can use this tool as a template for your own IFC application, or parts of it for other applications.
The source code is very clean and minimalistic, perfect for easy maintenance and further development.
In case you are interested, please contact info at ifcquery.com


### Credits:

this tool uses 
 - https://github.com/ThatOpen/engine_web-ifc for fast and robust loading and processing of IFC files.
 - Qt as GUI toolkit
 - OpenSceneGraph for the 3D view
