# google-scripts-copyfiletofolders
A list of all google scripts that utilise a spreadsheet

1) Function to copy a file to various folders (copyfiletofolders)
Copies a file into multiple folders and renames it based on the folder name
  
2) To change protection in a file in a large number of folders (ChangeProtectionLargeFolders)
Changes the protection in a specific file in a large folder

Utilize a spreadsheet to input:
- Folder containing all folders to search
- Name to search
- Range of cell to protect

Used classes:
- DriveApp
- Folder
- FolderIterators
- Protection
- Range

Possible updates:
- To clean the names to be more understandable
