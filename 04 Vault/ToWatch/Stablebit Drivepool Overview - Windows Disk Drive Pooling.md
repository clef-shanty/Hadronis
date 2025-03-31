---
Date Added: 
tags:
  - "#Youtube"
  - "#Source/Youtube"
  - "#📽️"
Status:
  - In Progress
Source:
  - YouTube
Creator: HTWingNut
Channel Name: HTWingNut
Video-URL: <iframe width="500" height="280" src="https://www.youtube.com/embed/yFVbuzPLv0o?si=u0d8baXIkmD8FBV8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Month:
  - "[[ August 2024]]"
Quarter:
  - "[[Q3 - 2024]]"
Year:
  - "[[2024]]"
Rating: ⭐⭐⭐⭐
Topics:
  - Windows
  - DrivePool
  - Backups
---

##### Media Extended
https://www.youtube.com/watch?v=yFVbuzPLv0o&t=10s

## Timestamp Notes


- [00:25](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=26#t=25.85) Introduction to Drive Pool

- [03:46](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=227#t=03:46.57) Windows Storage Spaces Option

- [06:15](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=376#t=06:15.98)  Installing Stablebit DrivePool

- [08:00](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=481#t=08:00.58) DrivePool Demonstration

```meta-bind-button
label: Play/Pause
icon: ""
hidden: false
class: ""
tooltip: ""
id: ""
style: primary
actions:
  - type: command
    command: media-extended:toggle-play
```

---
## Best Ideas

1.  [[
2.  [[
---

## Tools

1.  [[]]
2.  [[]]

---
## Reflection

---

## AI Summaries

### Source: NoteGPT

Summary

StableBit DrivePool is a user-friendly Windows solution for pooling multiple disk drives into a single volume, ideal for file servers without complex NAS setups.

Highlights
💻 Drive Pooling: Combines multiple drives into a single volume for easier data management.
⚙️ Windows Management: Native Windows options exist but have limitations compared to DrivePool.
🔄 Data Distribution: Automatically spreads data across pooled drives, simplifying storage.
🔒 Data Protection: Offers duplication features to safeguard critical data against drive failures.
🚀 Performance: Allows for performance optimizations, including SSD caching.
🛠️ Easy Recovery: If a drive fails, data on other drives remains accessible, ensuring reliability.
🌐 Network Sharing: Simplifies sharing pooled drives across a network, enhancing accessibility.
Key Insights
📦 User-Friendly Interface: DrivePool offers a straightforward setup and management of disk pools, making it accessible for users of all technical levels.
💰 Cost-Effective Solution: At $30, DrivePool provides a robust alternative to expensive NAS solutions, especially for home file servers.
📊 Flexible Data Management: Users can manage data placement on specific drives, allowing for tailored storage solutions based on individual needs.
🔄 Automatic Balancing: The balancing feature ensures optimal use of storage space, enhancing performance and prolonging drive lifespan.
🛡️ Redundancy Options: Users can choose to duplicate important files across multiple drives, providing peace of mind against data loss.
🔄 Seamless Integration: DrivePool works with existing NTFS drives, allowing for easy migration and data recovery, increasing versatility.
🌍 Remote Access: The network sharing feature enables users to access their pooled drives remotely, making it ideal for collaborative environments.

---
### Source: Recall
# Stablebit Drivepool Overview - Windows Disk Drive Pooling


![](https://i.ytimg.com/vi/yFVbuzPLv0o/maxresdefault.jpg)


## Intro to Drivepool [(00:00:00)](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=0s)


- Drive Pool is a Windows-based drive pooling solution that allows users to combine multiple disk drives into a single volume or drive letter.
- Windows has native options for drive pooling, but Drive Pool offers unique features and benefits.
- Drive Pool is a good option for users who want to run a Windows-based file server without the complexity or expense of a Network Attached Storage (NAS) setup.



## Windows Built In Pooling Options Disk Management [(00:00:44)](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=44s)


- Windows has built-in options for combining multiple hard drives into a single volume, allowing for increased storage capacity.
- These options include spanned volumes, striped volumes, and mirrored volumes.
- Spanned volumes combine disks of different sizes into a single larger volume, similar to Jagpool, but with key differences.
- Striped volumes, similar to [[Data striping | RAID 0]], distribute data across all disks for faster read and write speeds, but data loss occurs if any disk fails.
- Mirrored volumes create a single drive letter by writing data to two identical disks, ensuring data availability even if one disk fails.
- RAID 5, which requires a [[Windows Server]] license, is not available in the native [[Logical Disk Manager | Disk Management]] tool.



## Windows Storage Spaces [(00:03:23)](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=203s)


- Windows Storage Spaces is a built-in feature that allows users to create storage pools from multiple physical drives.
- Users can create different types of pools, including simple, two-way mirror, three-way mirror, and parity.
- While Windows Storage Spaces offers some redundancy options, it may not provide complete data protection in the event of a drive failure, which is where third-party solutions like StableBit DrivePool can be beneficial.



## Download and Install Free Trial [(00:04:33)](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=273s)


- StableBit DrivePool is a paid product that offers a 30-day free trial.
- The free trial can be accessed by downloading the software from the StableBit website.
- The free trial is only valid for one installation per machine and cannot be reset by uninstalling and reinstalling the software.
- The software is available for both 64-bit and 32-bit Windows operating systems.
- After downloading, the software can be installed by double-clicking the downloaded file.
- During installation, users can choose a custom installation location or accept the default location.
- Once installed, users can activate a 30-day free trial license.



## Adding empty disks to pool [(00:06:50)](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=410s)


- Drive Pool can be used with both new and existing hard drives.
- When adding a new drive to the pool, Drive Pool will automatically format the drive and assign it a drive letter.
- Drive Pool supports [[NTFS]] partitions only.
- Drive Pool creates drive letters for each individual drive, as well as a drive letter for the pool itself.
- Data should be managed on the drive pool drive letter, not the individual drive letters.
- When a drive is added to the pool, a "PoolPart" folder is created on the drive.
- The "PoolPart" folder contains a portion of the data from the pool, distributed across all drives in the pool.
- To view the "PoolPart" folder, hidden files and folders must be enabled in [[File Explorer | Windows Explorer]].
- When files are copied to the drive pool, they are distributed across all drives in the pool.



## Adding disk to pool that has existing data [(00:11:45)](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=705s)


- To add a disk with existing data to a DrivePool, follow the same process as adding an empty disk.
- After adding the disk, the existing data on the disk will not be automatically added to the pool.
- To add the data to the pool, drag and drop the folders from the newly added disk into the DrivePool's "Pool Part" folder.
- Once the data is added to the pool, the DrivePool will rebalance the data across all disks according to its default distribution rules.
- The rebalancing process will distribute a larger percentage of data to the largest disk in the pool.



## Balancing data across disks [(00:15:00)](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=900s)


- Drive Pool offers options for balancing data across disks, including immediate balancing, scheduled balancing, and no automatic balancing.
- The balancing tab provides options for equalizing disk space, optimizing [[Solid-state drive | SSDs]], and evacuating files from problematic hard drives.
- Drive Pool allows users to specify where files are stored, including the ability to store specific folders on designated disks.
- Drive Pool offers duplication functionality, allowing users to create duplicates of files or folders across multiple disks for data redundancy.
- Users can choose to duplicate entire pools or specific folders, with the duplication level adjustable based on the number of disks in the pool.



## Disk transfer and disk failure [(00:18:59)](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=1139s)


- DrivePool utilizes [[NTFS]] disks, ensuring data accessibility even if the computer or motherboard fails. Files can be accessed by connecting the disk to another NTFS-compatible machine.
- DrivePool allows for transferring the license and reconfiguring the pool on a new computer, preserving [[Data integrity | data integrity]].
- Removing a disk from the pool results in the loss of files stored exclusively on that disk. However, files stored on other disks within the pool remain accessible.
- Re-inserting a previously removed disk into the pool automatically reintegrates it, restoring access to the files stored on that disk.



## Setting up as a shared network drive [(00:20:55)](https://www.youtube.com/watch?v=yFVbuzPLv0o&t=1255s)


- Drive Pool can be set up as a shared network drive by right-clicking the Drive Pool, selecting "Properties," then "Sharing," and sharing the drive.
- Once shared, the Drive Pool can be accessed remotely from another computer on the network by entering the IP address of the computer hosting the Drive Pool.
- Drive Pool can be used to combine multiple smaller drives into a single larger drive, which can be useful for storing large files like games or for creating a file server.


---

### Mindmap
![[NoteGPT_MindMap_1723335738600.png]]