# IfcSplitAndMerge
Split and merge IFC files



### Current features:
- Load IFC file
- 3D view of loaded model
- Mesh compression (deduplication, quantization) for efficient rendering of large models.
- Select elements in 3D view through single click or rubberband
- Select elements in tree view
- Find and select entities by STEP ID (local ID, unique in each file), GUID (globally unique ID), name or description via text input
- Split feature: Write IFC file with selected entities. Selecting objects like IfcBuildingStorey or single objects with any of the above mentioned selection methods.


### Planned features
- Find and select by type, property sets etc not implemented yet
- Writing IFC files of merged models not implemented yet


![Screenshot 2025-06-30 123232](https://github.com/user-attachments/assets/34a9a284-23e4-4ca3-8655-f94291c215d5)


<img width="2550" height="1696" alt="image" src="https://github.com/user-attachments/assets/d92d3dba-26e6-4eed-8cf7-1b3d33e8e489" />


#### Select elements in 3D view (single or rubberband selection), treeview, or text input search criteria:
<img width="2546" height="1691" alt="image" src="https://github.com/user-attachments/assets/b1f83793-1621-4f88-8231-9c1a35b141a3" />

#### Write file with selected elements:
<img width="2550" height="667" alt="image" src="https://github.com/user-attachments/assets/66fa768f-4237-45de-a3cb-7cf6d66632bf" />

#### Result: IFC file with only the selected elements:
<img width="2547" height="812" alt="image" src="https://github.com/user-attachments/assets/c36d59b5-1a8e-451e-9f15-ad72d14ab5b8" />


Free to use. **[⬇️ Download IfcSplitAndMerge](https://github.com/ifcquery/IfcSplitAndMerge/releases)**


### Use as SDK or base for other IFC applications

You can use this tool as a template for your own IFC application, or parts of it for other applications.
The source code is very clean and minimalistic, perfect for easy maintenance and further development.
In case you are interested, please contact info&#40;&#97;&#116;&#41;ifcquery&#46;&#99;&#111;&#109;


### IFC files for testing:
https://github.com/ThatOpen/engine_web-ifc/tree/main/tests/ifcfiles/public

https://github.com/user-attachments/files/15805837/ViadottoAcerno.zip


### Credits:

this tool uses 
 - https://github.com/ThatOpen/engine_web-ifc for fast and robust loading and processing of IFC files.
 - Qt as GUI toolkit
 - OpenSceneGraph for the 3D view

<img width="2901" height="1717" alt="image" src="https://github.com/user-attachments/assets/ed7d6657-377f-440d-baf9-d213f8158b7e" />

<img width="2903" height="1719" alt="image" src="https://github.com/user-attachments/assets/6a726c33-1a25-410a-ac6e-e8e8d869117d" />


