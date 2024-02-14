# keiken-week1-day1-ex1

### How Permissions Are Granted to Delete a File ?
In Linux, to delete a file the user should have both write and execute permissions on the directory containing that file. we use chmod linux command to give permissions to owner, groups and others. 

**Important** : the main thing to know is that we should not confused between directory's permission and file's permission

### Create a file that your colleague can edit but not delete:
To allow the colleague to edit but not delete a file: 
*********************
`mkdir E_d`
`chmod +t E_e `
`cd E_d`
`touch editok` 
`chmod 664 editok` 
+t : sticky bit that prevent deletion
********************
here the collegue has read and write permissions for the file but the directorry has only write 
### Create a file that your can delete but not edit :

here the collegue only read permissions because he can not edit but its parent can be modified(delete files from it without modifying any file).
*******************
`mkdir D_e`
`cd D_e`
`chmod 773 D_e `
`touch deleteok`
`chmod 444 deleteok` 
*******************


 ### Does it make sense to be able to assign such rights?
Yes, it makes sense to assign such rights as they help maintain data integrity by preventing accidental or unauthorized deletion of important files during collaborative editing.
### What are the practical consequences of this experience?
Allowing users to delete files without editing them gives them the freedom to clean their workspace or remove unnecessary files easily.


