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

<img width="1917" height="1016" alt="Screenshot 2025-09-13 190330" src="https://github.com/user-attachments/assets/61f81507-bbd7-456b-8289-61c3025682a7" />

- Select **Local Disk** → **next** 

<img width="1914" height="1016" alt="Screenshot 2025-09-13 190413" src="https://github.com/user-attachments/assets/479286c9-9642-42ae-834f-fd4c3f2dafd0" />


### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

<img width="1910" height="1019" alt="Screenshot 2025-09-13 141747" src="https://github.com/user-attachments/assets/4402856a-c0d9-45f2-9923-6bc92a7d42b5" />


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files

<img width="1912" height="1017" alt="Screenshot 2025-09-13 190542" src="https://github.com/user-attachments/assets/7e44f0f3-25fe-4cef-aa85-054c536200b3" />

### Folder after deleting the files

<img width="1908" height="1019" alt="Screenshot 2025-09-13 190759" src="https://github.com/user-attachments/assets/05e28e37-7e39-4988-94f3-d5ce89f276e0" />

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
