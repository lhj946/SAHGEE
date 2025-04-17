SAHGEE
===
This is a tool built in GEE that allows for spatial and temporal hazard modeling of landslides.<br>

Of course, the tool is not just for landslide disasters, but other natural disasters can also be modeled accordingly, such as floods and fires. Users only need to modify a small part of the code, the overall framework has been realized and do not need to change.<br>

The user only needs to enter the mapping units of the area to be evaluated, e.g. grid, slope units, etc. The mapping cells also need to contain binary labels for whether or not a disaster has occurred. For example, in this tool, the slope cells are uploaded, and in addition to that, each slope cell contains whether a landslide has occurred or not and the size of the area of the landslide that occurred. All other landslide impact factors were evaluated directly using publicly available data from GEE (topographic factors, vegetation indices, rainfall data).<br>

Display Tool
===
![image](https://github.com/user-attachments/assets/8293fd3e-43ea-4245-83be-b60cbd66287f)
![image](https://github.com/user-attachments/assets/7cb47322-7825-4a55-b02b-7313a83282a3)
![image](https://github.com/user-attachments/assets/2b3e5c47-7065-4ada-86aa-48774231d308)
![image](https://github.com/user-attachments/assets/7d3e4854-4acf-461d-b507-0d17c66bc8c8)
![image](https://github.com/user-attachments/assets/db7210ac-c909-4922-abb4-34af8a9f3814)
![image](https://github.com/user-attachments/assets/fae051b3-8d00-47d5-a549-79a15edd8fe8)



Use
===
You can access the tool in GEE through this [link](https://ee-liuhj946.projects.earthengine.app/view/sahgee) and there is no need to register for a GEE account.

Cite
===
The original idea for the study was inspired by the following article.<br>
Titti G, Napoli G N, Conoscenti C, et al. Cloud-based interactive susceptibility modeling of gully erosion in Google Earth Engine[J]. International Journal of Applied Earth Observation and Geoinformation, 2022, 115: 103089.
