# Deploy UI5 Application to AS ABAP using program /UI5/UI5_REPOSITORY_LOAD

Feb5,2025

Tcode: SE38
Program name: /UI5/UI5_REPOSITORY_LOAD

วิธีการใช้งานจะมี 3 วิธีที่จะนำเสนอ
1. Upload
2. Download
3. Delete

## How to Upload
1. Enter SAPUI5 application name
2. Choose Radio button "Upload" and Execute

   ![image](https://github.com/user-attachments/assets/a6c8ec28-1776-401d-90ad-6eaa7e7fcdbd)

4. Select the source dirctory, webapp (webcontent) folder and click OK.

   ![image](https://github.com/user-attachments/assets/1884b6bc-3fab-4992-b199-31f285b6d139)

6. A summary of the selected objects is displayed. Scroll down to the bottom and click on
   "Click here to Upload"
   
7. Wait until to upload is completed. Then check the BSP Application in Tcode: SE80

   ![image](https://github.com/user-attachments/assets/57fa6df4-732e-40da-ae11-67ad050eb9a3)

9. Check service name ypatfio21 (The SAPUI5 Application) in Tcode: SICF
   
10. Right click and choose "Test Service"
    
    ![image](https://github.com/user-attachments/assets/13201103-4658-4a36-926a-e77575ae5ed6)

11. The Application runs successfully in the browser

    ![image](https://github.com/user-attachments/assets/8d328463-6e4f-442d-9f35-1b5d054e099b)

