# Document Management System

## Overview

 - This project aims to create an efficient document management system in sharepoint that facilitates smooth retrieval and approval of content enabled through implementing  
 content types, metadata columns, integrated work flows, customized views and so on.

### Document Library Organization

- **Content Types:**
  - For this project, Content Types were implemented in order to provide a structured content management that ensures consistency. The custom metadata columns can be easily added in the filters pane to make content retrieval very simple and customizable.

- **Views:**
  - **Standard View:**
    - lists all documents along with selected(customizable)columns. Visibility of documents depends on site permissions.
  - **Group by View:**
    - Documents are grouped based on one or more column values. Customized views can be created depending on specific needs.
  - **Calendar View:**
    - Displays documents as calendar events, suitable for documents with associated deadlines or dates.

- **Filters:**
  - Custom metadata columns are pinned to the filters pane to assist in content filtering. Filtering can be done using one or more columns. Filtering is used in view creation.

### Version Control and Approval Workflows

- Each time a file is modified a major version is created for that file. Members with the right permissions can revert back to former versions of a modified file.
- When a new file is created or modified a flow is triggered that will send an approval request for the assigned person. Once the assigned person either approves or rejects the file, the column named Approval Status will be updated accordingly.

### Metadata Management

- **Custom Metadata Columns:**
  - Define metadata columns capturing information relevant to documents (e.g., Department, keywords, approval status).

- **Document Status and Approval Workflow Integration:**
  - Set document status based on approval workflow outcomes.

### User Access and Security

- **Permissions:**
  - Set appropriate permissions for user groups, controlling access to documents and functionalities.
    - Read access, Write access, Delete access, Upload access, Manage permissions.
  - Divide users into groups based on roles and responsibilities.

### Auditing and Logging

- Implement auditing and logging mechanisms to track user actions within the SharePoint environment.

## Resources
 -**[Configuring The List Using JSON]**
      **(https://learn.microsoft.com/en-us/sharepoint/dev/declarative-customization/list-form-configuration)**

 -**[Meta Data & Adding Meta Data to share point Columns]**
    **(https://blog.enterprisedna.co/adding-metadata-in-sharepoint-using-columns/#:~:text=Metadata%20in%20SharePoint%20provides%20information,document%20library%20to%20categorize%20files)**

 -**[Calendar View 1]**
**(https://support.microsoft.com/en-au/office/create-a-calendar-view-from-a-list-d7dcc7f6-8838-4f46-a60b-04048ebc3f00#:~:text=Select%20Create%20new%20view.,column%20or%20columns%20should%20apply.)**

- **[Calendar View 2]**
**(https://learn.microsoft.com/en-us/sharepoint/dev/declarative-customization/list-form-configuration](https://lists.handsontek.net/format-microsoft-lists-calendar-view/#google_vignette)**

- **[Customize permissions for a SharePoint list or library]** (https://support.microsoft.com/en-us/office/customize-permissions-for-a-sharepoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782#:~:text=Assign%20unique%20permissions%20in%20SharePoint&text=grant%20unique%20permissions%3A-,Go%20to%20the%20list%2C%20library%2C%20or%20survey%20and%20open%20it,won't%20see%20Grant%20Permissions.)
## Steps To Follow

1. **Create Your Own Branch:**
   - Create a new branch in the repository to work on this project.

2. **Generate a Read Me:**
   - Update the Read Me file with details about the project and your personal information.

3. **After Completion of the Project:**
   - Add a DEMO video link in your Read Me showcasing the Document Management System in action.

Feel free to customize and expand on the features and resources based on your project's specific requirements. Happy coding!
