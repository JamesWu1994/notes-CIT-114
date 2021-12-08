# 9.01 What is Storage?
* Storage is basically a technology that allows a user to retain digital data onto a medium. It is one of the core components of a computer and in cloud computing, something that you need to understand the differences.
## Volatile vs Non-Volatile
* Volatile memory is a type of storage whose contents are erased when the system's power is turned off or interrupted.
* NV or Non-volatile memory is a term used to describe any memory or storage that is saved regardless of the power to the computer is on or off. It is also called persistent storage or permanent storage.
## Local Storage Types
* In computing, there is many forms of storage. Temporary storage, such as RAM, allows a computer to temporarily store information while the computer is in use, however when power is removed, the information stored in temporary storage is lost. Permanent storage is where you keep your operating system, applications, and other data files that you use on a computer system. The information will be saved even if there is no power to the system.
## Read Only Memory (RAM)
* As the computer boots, parts of the operating system and drivers are loaded into memory (RAM), which allows the CPU to process the instructions faster and speeds up the boot process. RAM is temporary storage that allows data and programs to be stored in memory in order the operating system to use them.

# 9.02 Disaster Recovery and Technology
## Disaster Recovery
* disaster recovery is a set of policies, tools, and procedures that enable the recovery or continuation of critical IT infrastructure and systems following a disaster. Storage is one of those key areas you want to carefully plan your recovery.
* Disaster recovery (DR) starts with a plan that works in conjunction with the business continuity and contingency plans. In DR, the goal is to get a business back operating as normally as possible as quickly as possible. This involves a lot of planning, skill at troubleshooting, and practice of the DR plan that may involve full drills practicing the written steps then updating them with changes.
* The first step in recovering from a disaster is making sure that the disaster is over.

## Fault Tolerance
* Fault tolerance is the idea that a system can continue to run properly even in the event of a failure of a component of that system. The ability to tolerate a failure of a critical component in a system and maintain functionality is also referred to as graceful degradation.
* When you design a system that will tolerate failures, the system will continue to work as expected rather than work at a reduced level or fail entirely. To do this you need to reduce the single points of failure like having a single hard drive act as a backup, isolate failures or contain failures and be able to reverse issues. This is where replication, redundancy and backups create a fault tolerant system.

## Replication
* Replication of IT infrastructure and data means that you have a full working duplicate of the data, systems, and networks that are critical. Replicated systems may be used at the same time to provide distribution of workloads across multiple identical systems. In terms of data, replicated data is written to multiple hard drives possibly in multiple locations.
* Replication is the most expensive of the fault tolerant options, in traditional infrastructure, as it requires to you to have multiple identical systems in place for each area you want to replicate. In large businesses, replicated data centers are called hot sites, as they have everything required to get a business back up in running including power, data and networking.

## Redundancy
* Redundancy is the idea where you have IT infrastructure in place to keep a business running, but it may be at a reduced capacity.

# 9.03 Storage in the Enterprise
As an individual, a single hard drive is sufficient for a computer to run your operating system and save your files. However, in large or complex businesses this will not suffice.
## Redundant Array of Independent Disks (RAID)
* Depending on the level you use, you can lose a drive and still keep all your data safe. Computers and servers can use a RAID to replicate data across multiple redundant drives in order to ensure data is available.
* RAIDs are used often as part of other devices such as Network Attached Storage, Storage Area Networks, as well as internal drives for a Computer or File Server.
* The most common levels used by businesses for backups are RAID 1, RAID 5, RAID 6 and RAID 1+0.

## File Servers
* A file server is a type of server on a network that is used to provide authorized users with access to files. It has all of the same components that a computer or server has including a CPU, RAM and storage, but the storage used for serving files is generally larger and optimized for serving files. Normally file servers are kept off of the public internet for security reasons, but are available on an internal enterprise network.

## Network Attached Storage (NAS)

* NAS is short for Network Attached Storage. A NAS device is any storage device that is connected to a network and provides a network with additional storage. A NAS does not have any processing power on its own, meaning it cannot be used to execute or run network shared programs. Most home routers today have a USB port allowing for an external hard drive to be connected as a NAS. In this configuration, anyone connected to the router can access the hard drive.
* A NAS will present and manage file systems for any client computers who are authorized to access it over the Internet.

## Storage Area Network (SAN)

* A Storage Area Network, SAN for short, is a specialized high-speed network that provides access at a raw block-address level. Systems can attach it to servers using technologies like Fiber Channel (FC) or Internet Small Computing System Interface (iSCSI) so that the storage appears to be attached locally rather than connected via a network.

* A SAN will provide other compuers with raw block-address level storage capacity by attaching it to those systems.

# 9.04 Storage in the Cloud
* Cloud storage is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service.

## Cloud Storage Requirements

* Durability. Data should be redundantly stored, ideally across multiple facilities and multiple devices in each facility. Natural disasters, human error, or mechanical faults should not result in data loss.
* Availability. All data should be available when needed, but there is a difference between production data and archives. The ideal cloud storage will deliver the right balance of retrieval times and cost.
* Security. All data is ideally encrypted, both at rest and in transit. Permissions and access controls (Links to an external site.) should work just as well in the cloud as they do for on premises storage.

# 9.05 Encrypting Storage
* Plain text is the original message or information before it has been encrypted. This text can be read by anyone as it is readable text.
* Cipher text is the encrypted version of the original plain text message after algorithm called a cipher has been applied to it. The encryption algorithm takes the plain text message and makes it so that it is no longer readable text.
* Data at rest simply means that the information is being stored physically where it is inactive or in use but not in being actively transmitted over a network. This data is most at risk for being stolen via physical theft or unauthorized access to file storage.

# 9.06 Data Backups
* Types of Backups
  * Full or Normal: Backs up every selected files or folders in full then clears the archival bit. This backup takes the longest and most space but is faster to restore
  * Copy: Makes a copy and backups up selected files or folders regardless of modification date or archive bit status. Does not clear the archive bit.
  * Incremental: After completing a full backup, it backs up changes made to selected files that modified since the last backup then clears the archival bit.
  * Differential: After completing a full backup, it backs up changes made to selected files that were modified since the last full backup and does not clear the archival bit.
  * Daily: Backs up files that were created or modified today. It ignores the archive bit, looking at the modification date only.

# 9.07 Backup Locations
* Backups that are stored locally generally use an external hard drive, RAID, network attached storage (NAS), USB drive or even a DVD, where the backup is in the same physical location (on-site) as the business.
* Backups stored locally will be faster to backup and restore. The shorter data transfer distance will decrease the amount of time it takes to restore files and get a business back up and running. However, they are at greater risk if the entire business is destroyed including all the backups. A flood or power surge can easily destroy all electronics if not properly protected leaving you with no backups.

## Cloud Storage
* Cloud storage allows for a business to move the backup to cloud storage infrastructure outside of the business location. Saving important data to cloud storage such as Google Drive, Dropbox, or Box.com can help move data outside away from the local business. 

* Object storage, often referred to as object-based storage, is a data storage architecture for handling large amounts of unstructured data. This is data that does not conform to, or cannot be organized easily into, a traditional relational database with rows and columns.
* File storage organizes and stores data inside a folder. Files are named, tagged with metadata (typically the file name, file type, and when it was created and last updated) and organized in folders under a hierarchy of directories and subdirectories. You can think of file storage in the same way you store physical paper files in a filing cabinet.
* Block storage offers an alternative to file-based storage—one with improved efficiency and performance. Block storage breaks a file into equally-sized chunks of data and stores these data blocks separately under a unique address. You don't need a file-folder structure. Instead, you can store the collection of blocks anywhere in the system for maximum efficiency.
