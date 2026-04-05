# AWS EBS Practical (Free Tier)

## 📌 Objective

To understand and implement Amazon Elastic Block Storage (EBS) with EC2.

## 🛠️ Services Used

* Amazon EC2
* Amazon EBS

## 🚀 Steps Performed

1. Launched EC2 instance (Amazon Linux)
2. Created EBS volume (8GB)
3. Attached volume to EC2
4. Formatted using ext4
5. Mounted to /data
6. Verified persistence

## 📷 Screenshots

<img width="1366" height="726" alt="05 04 2026_09 46 46_REC" src="https://github.com/user-attachments/assets/4b40bf90-fb82-4df5-8805-acf8a9d4e8af" />


## 📚 Commands Used

```bash
lsblk
mkfs -t ext4 /dev/xvdf
mount /dev/xvdf /data
df -h
```

## ✅ Outcome

Successfully attached and mounted EBS volume and verified persistent storage.

## 💡 Learnings

* Difference between EBS and instance store
* Persistent storage in AWS
* Linux disk management
