# Using-the-Autopsy-retrieve-the-deleted-files
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

<img width="1082" height="593" alt="Screenshot 2025-09-13 135840" src="https://github.com/user-attachments/assets/fd409332-ce92-47ac-b25c-eaa1f00cf8db" />

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

<img width="1080" height="1016" alt="Screenshot 2025-09-13 140124" src="https://github.com/user-attachments/assets/83317df2-8c6e-4aa9-a501-15ae00d80e2e" />

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

<img width="926" height="466" alt="Screenshot 2025-09-13 144100" src="https://github.com/user-attachments/assets/2057dd57-1c0f-49ca-b148-565d4d6b59a3" />


- Select **Local Disk** → **next** 

<img width="926" height="469" alt="Screenshot 2025-09-13 144155" src="https://github.com/user-attachments/assets/b9ff29f8-fc03-4a32-b6fd-668fbc79d643" />

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

<img width="1910" height="1019" alt="Screenshot 2025-09-13 141747" src="https://github.com/user-attachments/assets/4402856a-c0d9-45f2-9923-6bc92a7d42b5" />


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
<img width="1911" height="1017" alt="Screenshot 2025-09-13 141930" src="https://github.com/user-attachments/assets/f205c716-5e08-46f3-8c87-714708f05bc1" />



### Folder after deleting the files
<img width="1905" height="1016" alt="Screenshot 2025-09-13 135310" src="https://github.com/user-attachments/assets/bc661c66-62f0-4340-a3cf-b58af40e3c36" />

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
