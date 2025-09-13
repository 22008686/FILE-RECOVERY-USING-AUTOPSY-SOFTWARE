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
<img width="1082" height="593" alt="Screenshot 2025-09-13 135840" src="https://github.com/user-attachments/assets/bf5db89f-6e4d-4870-b1e2-f0508de626a5" />

```
### Create a New Case
```
<img width="1080" height="1016" alt="Screenshot 2025-09-13 140124" src="https://github.com/user-attachments/assets/bfb8f7c6-84d7-4819-96fa-6b69baf37325" />

```
### Add Disk Image
```
<img width="1910" height="1019" alt="Screenshot 2025-09-13 141747" src="https://github.com/user-attachments/assets/9aef5364-dfff-403c-805c-5e4aa3deb819" />

```
### Locate Deleted Files
```
<img width="1911" height="1017" alt="Screenshot 2025-09-13 141930" src="https://github.com/user-attachments/assets/15907f44-f833-4268-807c-4b8f037098f4" />

```

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
