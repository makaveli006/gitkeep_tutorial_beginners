## Tracking Empty Directories with .gitkeep
#### Git does not track empty directories by default. To include them in the repository, a placeholder file like .gitkeep is commonly used. This file ensures the directory is versioned even when it contains no other files.

Example:  
1. To keep an empty logs/ folder:   
2. Create the file: logs/.gitkeep  
3.Update .gitignore:

* logs/*
* !logs/.gitkeep
  
This setup ignores all files in logs/ except .gitkeep, allowing the directory structure to be preserved in Git.
