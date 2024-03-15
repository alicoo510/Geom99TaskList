# Week 7 checklist Virtual Machine
Created a new project for google cloud engine:project name and number which is unique to my project https://console.cloud.google.com/compute/instances?project=intrepid-league-417113
![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/55d9daaf-8426-4b47-8a00-09884aa27df9)

emable Compute engine API in new project
ran into an issue there is no available custome image, emailed shawn for help

![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/dc8d6a63-0c1e-46cf-9437-e4870250c077)

finished watching part 2 video while wating for email from shawn
![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/1791cc92-7579-4d3a-b078-65f6ae7f21fa)

made an instance using Shawns ArcGIS Server and a boot disk custome image and changing the firewall traffic
- create firwall rule using the correct IP for the fleming college computers, ingress, and the ttc port 444. giving the rule a name:flemingrdp444.
- enter student Username and passward to get computer running. Saved Password to a notpad document in _webDEV folder

![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/0b4fa3e3-fb67-40a4-86ec-e93b6333c545)
Made sure there was connection when this blue screen shows it indicated it is using the external IP address to talk to server
![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/42eb8587-e5d2-4471-8329-25098b0402b0)
![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/98fcff27-4720-4b26-9914-6a8648373d02)

an issue with the arcgis/manager saying there is no administrative access and so went back to firewall rule and edited to add in port 6443 and 6080 along with the 444 which was already there, then go in to remote desktop to create rule and enter ports so they are talking toeachother to get manager to work with the secure internal 6443 port

![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/9e3868c3-8183-49b3-92ad-b61723adf051)


![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/3c9554a7-967d-4239-816f-ba98908ec221)

opened arcGIS Pro and made a new arcgis server connection using the site admin login and the external IP adress

![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/f8afb2a2-40f5-437d-bf58-ec95a4e1f3aa)

 Rest point URL:  https://34.132.188.133:6443/arcgis/rest/services/SampleWorldCities/MapServer

![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/7b932069-cae3-49b8-b0f9-d0df421f89e2)


![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/a686b82f-3ac5-45f8-9608-ce3f52932396)
![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/6b3d6b97-1cb8-48c0-805f-0f2a841b5df5)

![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/aedf4de7-ba61-490b-bd43-7796b2b46ec6)

![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/e033eab0-9534-4b80-afc4-987984b6a994)
- forgot to change security settings on Virtual machine to allow the file to be shared over into arc Pro, has to go into 

![image](https://github.com/alicoo510/Geom99TaskList/assets/146375997/ee26cdd3-7e84-49b9-8b47-ccae04aacc7e)


# Read over articles in week 7 checklist
https://enterprise.arcgis.com/en/server/latest/publish-services/windows/services-in-arcgis-enterprise.htm

https://enterprise.arcgis.com/en/server/latest/publish-services/windows/relationships-between-web-services-and-portal-items.htm

