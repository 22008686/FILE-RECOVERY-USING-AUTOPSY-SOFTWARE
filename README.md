# FILE-RECOVERY-USING-AUTOPSY-SOFTWARE

## AIM
To use **Autopsy Digital Forensics Tool** to retrieve deleted files from a disk image.

---

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tool**: [Autopsy Digital Forensics](https://www.autopsy.com/)  
- **Test Data**: Disk image file (`disk.dd`, `disk.img`, `.E01`)

---

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Run File System & Data Recovery Modules"]
    E --> F[Locate Deleted Files in Results]
    F --> G[Recover and Export Deleted Files]
```
## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### Install Autopsy
```
<img width="1082" height="593" alt="Screenshot 2025-09-13 135840" src="https://github.com/user-attachments/assets/b1854591-7591-4b67-9414-81dc36856fc7" />


```
### Create a New Case
```
<img width="1080" height="1016" alt="Screenshot 2025-09-13 140124" src="https://github.com/user-attachments/assets/7ad47470-a20e-4209-afbb-38f6e796d1b0" />


```
### Add Disk Image
```
<img width="1917" height="1018" alt="Screenshot 2025-09-13 140626" src="https://github.com/user-attachments/assets/92b9285a-e4ac-4b4a-98f6-66c4813f20a2" />

```
### Locate Deleted Files
```
<img width="1911" height="1017" alt="Screenshot 2025-09-13 141930" src="https://github.com/user-attachments/assets/2c5ac5de-3a09-4957-9b43-939f3958822a" />

```

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
