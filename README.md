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
<img width="1082" height="593" alt="Screenshot 2025-09-13 135840" src="https://github.com/user-attachments/assets/0a7ea282-5dfc-4412-9222-5598b2b39dfb" />

```
### Create a New Case
```
<img width="1080" height="1016" alt="Screenshot 2025-09-13 140124" src="https://github.com/user-attachments/assets/a87721a9-67d7-4206-8499-c2f4fa1664b0" />

```
### Add Disk Image
```
<img width="1910" height="1019" alt="Screenshot 2025-09-13 141747" src="https://github.com/user-attachments/assets/03fafc91-fb4c-462b-a1b1-1f44664de504" />

```
### Locate Deleted Files
```
<img width="1911" height="1017" alt="Screenshot 2025-09-13 141930" src="https://github.com/user-attachments/assets/a5dd5fa0-d0e8-4a8f-afa6-eed0b15b76de" />

```

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
