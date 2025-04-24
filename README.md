# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
### NAME:G LEKASRI
### REGISTER NUMBER : 212223100025
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img
```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
Unallocated Space Analysis and Extracted Data Report
![Screenshot 2025-04-24](https://github.com/user-attachments/assets/2a2f536a-7827-4301-a55f-535a888edbeb)
![Screenshot 2025-04-24 2](https://github.com/user-attachments/assets/1be73802-5510-423f-a263-7163ab202e2f)
![Screenshot 2025-04-24 3](https://github.com/user-attachments/assets/8a4ab54a-961c-4c45-a795-a66c9a6e66fe)
![Screenshot 2025-04-24 4](https://github.com/user-attachments/assets/f9a84a73-fc59-49cb-bccb-3270cc886ae0)
![Screenshot 2025-04-24 5](https://github.com/user-attachments/assets/8914a593-2d58-4e27-af34-a9750d8e8efc)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

