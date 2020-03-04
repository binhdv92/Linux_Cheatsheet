# Linux_Cheatsheet

# Archive file
## tar.gz
1. Create
>$ tar -cvf Videos.tar ./Latest/

2. Untar
>$ tar -zxvf filename.tar.gz
 - z: the file is a "gzipped" file
 - x: extract files
 - v: verbose, print out the result during doing extract
 - f: Use the following tar for the operation.
 
 >$ tar -xvzf filename.tar.gz -C /folder/subfolder/
  - -C: Extract files to a specific directory or path
