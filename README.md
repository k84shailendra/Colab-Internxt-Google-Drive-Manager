# Colab-Internxt-Google-Drive-Manager
A Google Colab-based tool for managing Internxt Drive and to interacting it with Google Drive. 
This repository enables users to perform various file operations, including listing, uploading, downloading, moving, and deleting files in Internxt Drive, with seamless integration with Google Drive within the Colab environment.


---

## *Colab-Internxt-Google-Drive-Manager*
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1C-bidCjqKJv0Z0HrVThI1HjxgixUSt5Q)

---
###
![](https://media.publit.io/file/Image-G.png)
###
*This script offers an interactive interface for managing files and folders on Internxt Drive directly from a Google Colab notebook. It utilizes widgets to provide an intuitive way to perform various operations such as listing items, uploading and downloading files, creating and managing folders, and more. By using this script, you can easily:*

- [List all items on your Internxt Drive.]
- [View files in specific source and destination folders.]
- [Create new folders with designated IDs and names.]
- [Upload files from your local system (Google drive/Mount drive) to a chosen folder on Internxt Drive.]
- [Download files from Internxt Drive to your local system (Google drive/Mount drive).]
- [Move files within Internxt Drive from one folder to another.]
- [Trash files or folders to remove them from your drive.]
- [Logout from your Internxt account.]

---


# Here’s a brief description of each section and its functionality:

1. **List All Items Widget**
   - **Purpose:** Lists all items on Internxt Drive.
   - **Action:** When the button is clicked, it runs a command to list all items and displays the output.

2. **List Files in Source Folder Widget**
   - **Purpose:** Lists files in a specified source folder on Internxt Drive.
   - **Action:** Takes a folder ID as input, runs a command to list files in that folder, and shows the result.

3. **List Files in Destination Folder Widget**
   - **Purpose:** Lists files in a specified destination folder on Internxt Drive.
   - **Action:** Takes a folder ID as input, runs a command to list files in that folder, and displays the result.

4. **Create Folder Widget**
   - **Purpose:** Creates a new folder on Internxt Drive.
   - **Action:** Takes folder ID and name as input, runs a command to create the folder, and shows the result.

5. **Upload File Widget**
   - **Purpose:** Uploads a file to a specified destination folder on Internxt Drive.
   - **Action:** Takes file path and destination folder ID as input, runs an upload command, and displays the result.

6. **Download File Widget**
   - **Purpose:** Downloads a file from Internxt Drive to a specified local directory.
   - **Action:** Takes file ID and destination directory as input, runs a download command, and shows the result.

7. **Move File Widget**
   - **Purpose:** Moves a file from one location to another within Internxt Drive.
   - **Action:** Takes file ID and destination folder ID as input, runs a move command, and displays the result.

8. **Trash File/Folder Widget**
   - **Purpose:** Moves a file or folder to the trash on Internxt Drive.
   - **Action:** Takes file or folder ID as input, runs a command to trash the item, and shows the result.

9. **Logout Widget**
   - **Purpose:** Logs out from Internxt Drive.
   - **Action:** Runs a logout command and displays the result.

Each widget has a button to trigger an action, an input field for necessary parameters, and an output area to display the results or errors of the command execution. This script provides a user-friendly interface for managing files and folders on Internxt Drive directly from a Colab notebook.


---
