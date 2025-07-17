# Instructions for Setting Up SAS Proramming 1 Course Files in Workbench for Learners

You can successfully complete all demos, activities, and practices in the SAS Programming 1 course using SAS Viya Workbench for Learners. To set up the supporting course files, complete these steps:
1) From the SAS Viya Workbench page, click **Launch Visual Studio Code**.
2) Select <img width="26" height="22" alt="image" src="https://github.com/user-attachments/assets/e424807f-2ca0-47f1-8507-662cd5e29200" /> in the upper-left corner and choose **Terminal** > **New Terminal**.
3) Paste the following text into the terminal and press Enter: git clone https://github.com/stever-sas/EPG1V2.git
4) Verify a folder named **EPG1V2** is added in the Explorer. Open the **createdataPG1v2_Workbench.sas** program.
5) If the EPG1V2 folder is in MYFOLDER, then you do not need to modify the program.
6) If the EPG1V2 folder is in a different location, right-click **EPG1V2** in the Explorer and select **Copy Path**. In the program, replace the provided path in the %LET statement with the copied path.
7) Click <img width="22" height="22" alt="image" src="https://github.com/user-attachments/assets/d6ff737c-8603-4a15-b10e-e0f2f44d06e7" /> to run the program. Verify a report is generated listing 22 tables. You will also see several folders and files now available in the EPG1V2 folder. 

