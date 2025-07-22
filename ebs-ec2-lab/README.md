# 📦 Working with Amazon EBS and EC2

In this lab, I practiced using Amazon Elastic Block Store (EBS) and EC2.  
This included provisioning storage, attaching it to compute instances, and simulating a real-world backup and recovery scenario using snapshots.

---

## 🧪 Lab Objectives

- ✅ Create an EBS volume and attach it to an EC2 instance
- ✅ Format and mount the volume using EC2 Instance Connect
- ✅ Write data to the volume and take a snapshot
- ✅ Restore a new volume from the snapshot and verify the data

---

----------
## 🖼️ Screenshots

### 1. Created a New EBS Volume
![EBS Volume Created](./screenshots/screenshot%201.JPG)

---

### 2. Attached Volume to EC2
![Volume Attached](./screenshots/screenshot%202%20-%20aataching%20EBS%20volume.JPG)


---

### 3. Disk Usage Before Mounting
![df -h Before Mounting](./screenshots/screenshot%203%20-%20df%20-h%20before%20mounting.JPG)


---

### 4. Mounted Volume and Verified
![df -h After Mounting](./screenshots/screenshot%204%20-%20df%20-h%20after%20mounting.JPG)


---

### 5. Wrote and Verified File
![File Creation and Verification](./screenshots/screenshot%205%20-%20file%20creation%20and%20verification.JPG)


---

### 6. Created EBS Snapshot
![Snapshot Created](./screenshots/screenshot%206%20-%20snapshot%20created.JPG)


---

### 7. Restored Volume from Snapshot
![Restored Volume](./screenshots/screenshot%207%20-%20restored%20volume%20available.JPG)

---

### 8. Verified File on Restored Volume
![File Restored](./screenshots/Screenshot%208%20-%20file%20restored%20from%20snapshot.JPG)

---

## 🧠 What I Learned

- How to manage block storage in AWS using EBS
- How to perform basic Linux file system operations
- How to use snapshots for data backup and recovery
- The importance of choosing correct AZs for volume attachment

---

## 🛠️ Tools Used

- AWS EC2
- Amazon EBS
- EC2 Instance Connect
- Linux CLI

