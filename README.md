# Basin-flow_direction-flow_accumulation-arcGIS_automation
This code serves to help users to automate DTM Raster files to file flow accumulation and flow direction in ArcMap.

How to use this code :
1. Open a new, empty map document in ArcMap.
2. Click Geoprocessing >> Python.
3. Paste this code :

	execfile(r'*\flow_dir_acc2_with_basin.py')

4. Press enter, than follow the instructions
5. The process is automatically begin


This code has the flow: 
1. Fill 
2. Flow direction 
3. Flow Accumulation 
4. Raster Calculator (Flow Accumulation > 25000) 
5. Stream Order 
6. Raster to Polyline (for Flow Direction) 
7. Raster to Polygon (for Flow Accumulation)
8. Basin
