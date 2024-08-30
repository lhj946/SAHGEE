SAHGEE
===
This is a tool built in GEE that allows for spatial and temporal hazard modeling of landslides.<br>

Of course, the tool is not just for landslide disasters, but other natural disasters can also be modeled accordingly, such as floods and fires. Users only need to modify a small part of the code, the overall framework has been realized and do not need to change.<br>

The user only needs to enter the mapping units of the area to be evaluated, e.g. grid, slope units, etc. The mapping cells also need to contain binary labels for whether or not a disaster has occurred. For example, in this tool, the slope cells are uploaded, and in addition to that, each slope cell contains whether a landslide has occurred or not and the size of the area of the landslide that occurred. All other landslide impact factors were evaluated directly using publicly available data from GEE (topographic factors, vegetation indices, rainfall data).<br>

Display Tool
===
![image](https://github.com/user-attachments/assets/8293fd3e-43ea-4245-83be-b60cbd66287f)
![image](https://github.com/user-attachments/assets/35268c76-3fb3-4374-93b4-389f20acf885)
![image](https://github.com/user-attachments/assets/ee34339f-8691-407b-8f15-d87fe1fd4531)
![image](https://github.com/user-attachments/assets/0254c88b-f59d-4948-a900-65f25fe9e62f)
![image](https://github.com/user-attachments/assets/fb53cca3-ea4d-496c-9508-8cf26d1e6747)
![image](https://github.com/user-attachments/assets/2cba1312-9535-4c80-a365-7777c952d98c)
![image](https://github.com/user-attachments/assets/d169a01d-ce38-40de-b961-0c6745fbf18a)
![image](https://github.com/user-attachments/assets/d4a1adac-21c7-4c19-a2ca-a25f797160c0)
![image](https://github.com/user-attachments/assets/46c2f35d-6189-4927-9fa6-592617550c5e)
![image](https://github.com/user-attachments/assets/a78ed8f9-99d7-4e3a-a8c9-a5b8aa134d7d)
![image](https://github.com/user-attachments/assets/bd2636e4-6445-4374-9725-12b59fde37ef)
![image](https://github.com/user-attachments/assets/a3e55602-e685-4b12-a64a-c46c9113736a)

Use
===
You can access the tool in GEE through this [link](https://ee-liuhj946.projects.earthengine.app/view/sahgee) and there is no need to register for a GEE account.

Cite
===
The original idea for the study was inspired by the following article.<br>
Titti G, Napoli G N, Conoscenti C, et al. Cloud-based interactive susceptibility modeling of gully erosion in Google Earth Engine[J]. International Journal of Applied Earth Observation and Geoinformation, 2022, 115: 103089.
