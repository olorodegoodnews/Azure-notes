# Azure Storage

## Azure Storage Account

An Azure Storage Account is the top-level Azure resource that provides access to Azure storage services.

### Key Points

- Required before creating Blob Containers, File Shares, Queues, or Tables.
- Storage account names must be globally unique.
- Standard performance is suitable for most workloads.
- LRS stores multiple copies of data within one Azure region.

### What I Learned

I created my first Azure Storage Account using an existing Resource Group and learned the purpose of the Performance and Redundancy settings.

---

## Blob Containers

A Blob Container is a logical container used to organize blobs inside an Azure Storage Account.

### Key Points

- A Storage Account can contain multiple Blob Containers.
- Blob Containers store unstructured data such as images, videos, documents, and backups.
- Access to a Blob Container can be controlled through access levels and Azure RBAC.

### What I Learned

I created my first Blob Container inside an Azure Storage Account and learned that it acts like a folder for organizing blob data.


---

## Azure Blob

A blob is a file stored in Azure Blob Storage.

### Common Blob Types

- Images
- Documents
- Videos
- Backups
- Application files

### What I Learned

- A Blob Container stores blobs.
- Files are uploaded into a Blob Container.
- Azure Blob Storage is designed for unstructured data.


---

## Blob Container Access Levels

Azure Blob Containers support three access levels:

### Private

- Only authorized users can access blobs.
- Recommended for production workloads.

### Blob

- Anonymous users can read blobs if they know the URL.
- They cannot list all blobs in the container.

### Container

- Anonymous users can list and read all blobs in the container.

### What I Learned

I reviewed the available Blob Container access levels and understood when each option should be used.


---

## Azure Lifecycle Management

Lifecycle Management automatically manages blob data based on rules.

### Benefits

- Reduces storage costs
- Automates blob management
- Moves data between access tiers
- Deletes old data based on retention policies

### Common Actions

- Move to Cool tier
- Move to Archive tier
- Delete old blobs

### What I Learned

I created a Lifecycle Management rule that automatically moves blobs to the Cool access tier after 30 days, helping optimize storage costs.


---

## Blob Versioning

Blob Versioning automatically saves previous versions of a blob whenever it is modified.

### Benefits

- Recover overwritten files
- Track file changes
- Improve data protection

---

## Blob Soft Delete

Soft Delete allows deleted blobs to be recovered before they are permanently removed.

### Benefits

- Recover accidentally deleted files
- Protect important business data
- Improve disaster recovery

### Best Practice

Enable both Blob Versioning and Soft Delete for production storage accounts.

### What I Learned

I enabled Blob Versioning and Soft Delete on my Azure Storage Account to protect blob data from accidental modification or deletion.
