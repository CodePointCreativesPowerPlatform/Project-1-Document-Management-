# Document Management System (DMS)

## Overview
The Document Management System (DMS) is a robust system designed to efficiently organize, control, and manage documents within an organization. It focuses on features such as document organization, version control, approval workflows, metadata management, user access, security, and automation.

## Features

### Document Library Organization
The DMS provides various features to organize documents effectively:

- Logical Folders and Subfolders: Documents can be organized based on content type, department, or any relevant criteria.
- Views:
  - Standard View: Displays documents in a list format with customizable columns, such as title, author, date created, and modified date.
  - Group by View: Groups documents based on specific columns, allowing quick access to documents related to a particular category.
  - Calendar View: Presents documents as calendar events, suitable for documents with associated deadlines or dates.
- Filters:
  - Basic Filters: Users can filter documents by date created, modified date, author, or any displayed column.
  - Metadata Filters: Custom metadata columns can be used to filter documents based on keywords, tags, categories, or other relevant attributes.

### Version Control and Approval Workflows
The DMS ensures document integrity and facilitates collaborative workflows:

- Version Control: Changes made to documents are tracked, enabling users to revert to previous versions if necessary.
- Approval Workflows: Workflows can be implemented to ensure proper review and authorization before finalizing documents.

### Metadata Management
Metadata plays a crucial role in document management and retrieval:

- Custom Metadata Columns: Administrators can define metadata columns to capture information relevant to documents, such as department, keywords, and approval status.
- Document Status and Approval Workflow Integration: The document status can be automatically updated based on the outcome of the approval workflow.

### User Access and Security
User access and security are essential aspects of a DMS:

- Permissions: The system allows setting appropriate permissions for user groups, controlling access to documents and functionalities. Permissions can include read access, write access, delete access, upload access, and manage permissions.
- User Groups: Users can be divided into groups based on their roles and responsibilities, ensuring appropriate access rights.

### Auditing and Logging
To maintain accountability and track user actions, the DMS includes auditing and logging mechanisms:

- Auditing and Logging: The system records user actions within the DMS environment, providing an audit trail of document-related activities.

## Automation and Customizations

In addition to the core features mentioned above, the following customizations and automations have been implemented:

1. Automated Approval Flow: When a new file is added to the document library, an automated flow is triggered. It sends an approval request and updates the document's status to either "rejected" or "approved" based on the response received.
   - If the document is rejected, it is moved to another folder.
2. Automatic Deletion of Rejected Files: Another automation is in place to check whether the files in the rejected folder have been there for more than seven days. If so, the automation deletes those files.
3. Customized Document Formatting: The documents or files within the DMS have been customized using JSON formatting, allowing for a tailored and visually appealing display.
4. Additional Views:
   - Approved Files View: This view displays only the approved files, providing a quick overview of the documents that have undergone the approval process successfully.
   - Grouped by Calendar View: Documents are grouped based on calendar events, making it convenient for managing documents associated with specific deadlines or dates.
   - Recently Viewed by Owner View: This view shows the documents recently accessed by the owner, facilitating easy retrieval of recently accessed files.

User Permissions for Reading and Editing

To enhance user access control, the DMS includes the ability to assign specific permissions for reading and editing documents. This feature ensures that only authorized individuals can view and modify documents based on their assigned roles and responsibilities.
