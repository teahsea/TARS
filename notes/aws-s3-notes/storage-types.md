# Storage Types
    - Basics
        - Block 
            - HDD SSD
        - File
            - Built on top of block storage.
            - Protocols =>  Server Message Block (SMB) and Network File System (NFS)
        - Object 
            - Built on top of block storage.
            - Storign the data into binary objects.
            - Supports versoning.

# AWS Storage Portfolio

    - Services
        - online and offline data and file-transfer services, 
        - edge storage services, 
        - hybrid storage services,
        - data-protection services.

        - CORE Services
            - Block
                - AWS EBS
                    - It's used to attach Ec3 instance
            - Object
                - S3 /  S3 Glacier
            - File
                - For Shared files
                - Amazon EFS - uses NFS Protocol.

    - The optimal storage solution for a system varies based on the following characteristics:
        - Type of access method (block, file, or object)
        - Patterns of access (random or sequential)
        - Required throughput measured in megabits per second
        - Required input output operations per second (IOPS)
        - Frequency of access (online, offline, archival)
        - Frequency of update [write once, read many (WORM); dynamic]
        - Availability and durability constraints


