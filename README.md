# Document Management System

## Overview

This project expands upon the core Document Management System (DMS) functionality with powerful customization for organization, approval, and metadata management. Building upon the features described in the original readme, we've further enhanced the system for increased usability and efficiency.

## Enhanced Features:

### Granular Permissions:

**Inheritance Broken:** Specific permissions granted for read, edit, and other actions to designated groups, ensuring precise control over document access. (Originally mentioned)
### Custom Metadata Management:

**File Status Tracking:** A "Status" column categorizes files as Approved, Rejected, or Pending for efficient filtering and grouping. (New addition)
Approver Identification: An "Approver Name" column stores the individual who approved or rejected each file, providing clear accountability. (New addition)
Organized Folder Structure:

**Type-Based Folders:** Dedicated folders ("CSV", "PDF", "MP4", "JPEG") automatically group files based on their extensions, simplifying navigation and retrieval. (New addition)
**Automated Workflows:**

**Approval-Driven Status Update:** A Power Automate flow triggered by file creation updates the status based on the approval outcome (Approved/Rejected), respectively moving files to designated folders. (New addition)
Weekly Rejected File Cleanup: Another flow automatically deletes Rejected files older than one week, streamlining storage management. (New addition)
## Enhanced Views:

**Calendar View:** Month-based calendar view for documents with associated deadlines or dates. (Originally mentioned)
**Standard Views:** Customizable list views with columns like title, author, date, and status. (Originally mentioned)
**All Documents View:** Comprehensive listing of all documents in the library. (Originally mentioned)
## Visual Cues:

**JSON formatting:** Color-coded status labels (green for Approved, red for Rejected) in views and columns offer quick visual indicators. (New addition)
Additional features from the original readme:

**Document Library Organization:** Logical folders, subfolders, views (Standard, Group by, Calendar), filters (basic and metadata) for efficient document classification and access.
**Version Control and Approval Workflows:** Track changes and implement review/authorization processes to ensure document accuracy and control.
User Access and Security: Granular permissions (read, write, delete, upload, manage) assigned to user groups for secure document access control.
**Auditing and Logging:** Track user actions within the SharePoint environment for enhanced accountability and transparency.
Benefits:

**Improved Accessibility:** Intuitive folder structure and categorized views simplify document access and retrieval.
Enhanced Collaboration: Granular permissions and clear approval trails ensure proper control and accountability.
Streamlined File Management: Automated workflows for status updates and cleanup optimize storage and organization.

**This enhanced DMS system empowers users with efficient document management, clear access control, and automated workflows, contributing to a more organized, collaborative, and secure workspace.**
