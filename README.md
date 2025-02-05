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


## How to Download
1. Enter SAPUI5 application name
2. Choose Radio button "Download" and Execute

   ![image](https://github.com/user-attachments/assets/595cbb85-e1d0-4d8a-a72e-b30e4cd7b690)

3. Choose destination folder to be saved

   ![image](https://github.com/user-attachments/assets/01e9c782-c6d1-4275-86ba-1efaf2c8035a)

4. Click on "Click here to Download" to confirm

   ![image](https://github.com/user-attachments/assets/fca041d5-388e-4160-9e32-dbf7fc76c86c)

5. Check in folder for the result. We can use this files in VS Code for the modification

   ![image](https://github.com/user-attachments/assets/a89e74bb-5025-4ee2-82d3-21e44f7ed3bd)
