# SAHGEE
This is a tool built in GEE that allows for spatial and temporal hazard modeling of landslides.
Of course, the tool is not just for landslide disasters, but other natural disasters can also be modeled accordingly, such as floods and fires. Users only need to modify a small part of the code, the overall framework has been realized and do not need to change.
The user only needs to enter the mapping units of the area to be evaluated, e.g. grid, slope units, etc. The mapping cells also need to contain binary labels for whether or not a disaster has occurred. For example, in this tool, the slope cells are uploaded, and in addition to that, each slope cell contains whether a landslide has occurred or not and the size of the area of the landslide that occurred. All other landslide impact factors were evaluated directly using publicly available data from GEE (topographic factors, vegetation indices, rainfall data).

# Display Tool
![image](https://github.com/user-attachments/assets/8293fd3e-43ea-4245-83be-b60cbd66287f)
![image](https://github.com/user-attachments/assets/35268c76-3fb3-4374-93b4-389f20acf885)
![image](https://github.com/user-attachments/assets/a64dbaf8-00bc-4126-9fd7-b14a9b552121)
![image](https://github.com/user-attachments/assets/85b9b681-69d1-494a-aa82-b42616cbece7)
![image](https://github.com/user-attachments/assets/41f3f704-a745-4253-a855-7ea2f65c85d5)![image](https://github.com/user-attachments/assets/e2151661-2325-4278-812d-73189356af69)![image](https://github.com/user-attachments/assets/100e9cd9-fee8-4aff-991a-612aaee7a855)
![image](https://github.com/user-attachments/assets/7ec607cb-ae29-41a6-b92f-cc0fb4c4bb7b)
![image](https://github.com/user-attachments/assets/5404e31a-f3c1-46e6-bfff-622f9e5c8c8a)
![image](https://github.com/user-attachments/assets/7115d3f6-8489-467f-a5cd-169a8623af4b)![image](https://github.com/user-attachments/assets/c4bf8629-12ba-415b-8809-2ee9bddf3ddc)![image](https://github.com/user-attachments/assets/19789f36-4b46-43fb-b341-45d755a40252)

You can access the tool in GEE through this link(https://ee-liuhj946.projects.earthengine.app/view/sahgee) and there is no need to register for a GEE account.
The original idea for the study was inspired by the following article.
Titti G, Napoli G N, Conoscenti C, et al. Cloud-based interactive susceptibility modeling of gully erosion in Google Earth Engine[J]. International Journal of Applied Earth Observation and Geoinformation, 2022, 115: 103089.
