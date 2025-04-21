# EXP 4: Using-the-Autopsy-retrieve-the-deleted-files

## AIM:
To install Autopsy software on windows operating system and analyse the file and folder configuration.

## EQUIPMENT REQUIRED:
● Hardware: Personal Computer (PC)
```
Register Number:212223100035
Name: Muhammad Afshan A
```
## DESIGN STEPS:

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`E:`), where the folder created in the New Virtual Disk
- Create a new folder or use the entire disk and then copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![alt text](IMAGE-1.png)

- Enter a **Case Name** (e.g., `Autopsy-1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![alt text](IMAGE-2.png)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![alt text](IMAGE-3.png)

- Select **Local Disk** → **next** 

![alt text](IMAGE-4.png)

- Select Disk → **Choose the VHD drive (`New Volume(E:)`)**

![alt text](IMAGE-5.png)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![alt text](IMAGE-6.png)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![alt text](IMAGE-7.png)

- Select a folder to see the recovered files (e.g., `K:\DFDI-Extracted`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![alt text](IMAGE-8.png)

### Folder after deleting the files
![alt text](IMAGE-9.png)

### Folder after extracting the deleted images using autopsy

![alt text](IMAGE-10.png)

## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
