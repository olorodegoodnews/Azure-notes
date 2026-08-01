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
