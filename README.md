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

# Checksum MD5, SHA1, SHA256, SHA
> $ echo '[a] [b]' | md5sum -c
  - \[a]: checksum
  - \[b]: filename
example linux:
> $ echo '8180611b87209d3897b0735a56780204 PhysioNetChallenge2020_Training_CPSC.tar.gz' | md5sum -c

On window using powershell
> $ certutil -hashfile .\\PhysioNetChallenge2020_Training_CPSC.tar.gz MD5
