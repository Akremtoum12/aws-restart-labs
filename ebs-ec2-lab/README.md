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

## 🖼️ Screenshots

### 1. Created a New EBS Volume
![EBS Volume Created](./screenshots/1_volume_created.png)

---

### 2. Attached Volume to EC2
![Volume Attached](./screenshots/2_volume_attached.png)

---

### 3. Disk Usage Before Mounting
![df -h Before Mounting](./screenshots/3_df_before.png)

---

### 4. Mounted Volume and Verified
![df -h After Mounting](./screenshots/4_df_after.png)

---

### 5. Wrote and Verified File
![File Created](./screenshots/5_file_created.png)

---

### 6. Created EBS Snapshot
![Snapshot Created](./screenshots/6_snapshot_created.png)

---

### 7. Restored Volume from Snapshot
![Restored Volume](./screenshots/7_restored_volume.png)

---

### 8. Verified File on Restored Volume
![File Restored](./screenshots/8_file_restored.png)

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

