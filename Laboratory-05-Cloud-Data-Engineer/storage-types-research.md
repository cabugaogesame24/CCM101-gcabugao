# Cloud Storage Types

Cloud storage has different types depending on how the data is stored and used. The three common types are Block Storage, File Storage, and Object Storage.

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| *Block Storage* | Divides data into blocks and provides storage that can be attached to a computer or virtual machine. | Commonly used for operating systems, databases, and applications that need direct storage access. | AWS EBS |
| *File Storage* | Keeps data as files and folders in a shared file system. | Useful for shared documents, files, and applications that need access to the same folders. | AWS EFS |
| *Object Storage* | Keeps files as individual objects with their data and related information. These objects are stored inside buckets. | Useful for photos, videos, backups, and other large amounts of unstructured data. | Amazon S3 |

## Why Object Storage Is a Good Choice for the Client

Object Storage is suitable for the client's photo-sharing application because it is designed to handle files such as photos and videos. It can also handle a growing amount of data, which makes it useful when many users continue uploading images.
