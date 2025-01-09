<h1>HDD to SDD Disk Imaging/Cloning a Hard Drive</h1>

In this project, I transferred all data, including the OS and applications, from an HDD to an SSD using disk cloning. The goal was to upgrade to faster storage without losing any functionality. I prepared the drives, ensured proper partition alignment for SSD performance, and verified the system booted correctly after the migration. This process improved system speed and reliability while showcasing my ability to handle hardware upgrades and data integrity during migrations.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Clonezilla</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b>

<h2>Step-by-Step Guide: Cloning an HDD to SSD Using Clonezilla</h2>

<p align="center">

<h3>1.Preparation</h3>
I started by connecting the Samsung 990 EVO Plus SSD to the system alongside the existing Toshiba HDD. Since the SSD uses an M.2 interface, I installed it into the motherboard’s M.2 slot, ensuring compatibility.

<h3>2.Setting Up Clonezilla</h3>
Next, I downloaded Clonezilla and created a bootable USB using Rufus. This software is great because it’s reliable and free for disk cloning.

<h3>3.Booting into Clonezilla</h3>
I restarted the system and booted from the USB. To do this, I accessed the BIOS/UEFI and temporarily set the USB as the first boot device. Once Clonezilla loaded, I followed the on-screen prompts to start the disk cloning process.

<h3>4.Selecting the Cloning Mode</h3>
I chose the “device-to-device” mode since I was cloning directly from the HDD to the SSD. Clonezilla offers options for more advanced configurations, but this mode works perfectly for most migrations.

<h3>5.Choosing Source and Target Drives</h3>
This step required careful attention. I selected the Toshiba HDD as the source drive and the Samsung SSD as the target drive. I double-checked these selections to ensure I wasn’t overwriting any important data.

<h3>6.Partition Management</h3>
Clonezilla automatically handles partition adjustments during the cloning process. However, I made sure to align partitions correctly for optimal SSD performance—a key factor when switching to high-speed storage like the Samsung 990 EVO Plus.

<h3>7.Cloning the Drives</h3>
With everything configured, I initiated the cloning process. Clonezilla displayed real-time progress, which helped me monitor the transfer. It’s essential to let this process complete without interruptions to maintain data integrity.

<h3>8.Finalizing and Testing</h3>
Once the cloning was done, I restarted the system, accessed the BIOS, and set the SSD as the primary boot drive. After booting into Windows, I verified that all files, applications, and the OS were functioning correctly. The system was noticeably faster, with significantly reduced boot and application load times.

<h3>9.Post-Migration Cleanup</h3>
I confirmed TRIM was enabled in Windows to maintain SSD performance over time. I then formatted the old HDD, giving the client the option to repurpose it for additional storage or backups.
</p>

<h2> Conclusion </h2>
This project demonstrates my ability to execute a seamless data migration using disk cloning tools like Clonezilla. By carefully managing each step—from hardware preparation to post-migration testing—I ensured the system's performance was significantly enhanced without any data loss. This process highlights my technical proficiency in storage upgrades, data integrity, and system optimization.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
