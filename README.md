# Document Management System Project

## Overview

 - This project aims to create an efficient document management system in sharepoint that facilitates smooth retrieval and approval of content enabled through implementing content types, metadata columns, integrated work flows, customized views and so on.

### Document Library Organization

- **Content Types:**
  - For this project, Content Types were implemented in order to provide a structured content management that ensures consistency.
  - Custom metadata columns provide a standardized way of content creation.
  - The custom metadata columns can be easily added in the filters pane to make content retrieval very simple and customizable.

- **Views:**
  - Standard View: lists all documents along with selected(customizable)columns. Visibility of documents depends on site permissions.
  - Group by Views: Documents are grouped based on one or more column values. Customized views can be created depending on specific needs.
  - Calendar View: Displays documents as calendar events, suitable for documents with associated deadlines or dates.
  - Approve/reject view: Displays documents grouped by approved or rejected value.

- **Filters:**
  - Custom metadata columns are pinned to the filters pane to assist in content filtering. Filtering can be done using one or more columns, helping narrow down on the specific document we are looking for.
  -  Filtering greatly assists in finding documents with certain properties that otherwise would have been time consuming to search for in a typical folder/sub-folder document organization.

### Version Control and Approval Workflows

- Each time a file is modified a major version is created for that file. Members with the right permissions can revert back to former versions of a modified file.
- When a new file is created or modified an automated flow is triggered that will send an approval request for the assigned person. Once the assigned person either approves or rejects the file, the column named Approval Status will be updated accordingly. 

### Demo of the project
- link: https://files.fm/u/zj6sqk976y

