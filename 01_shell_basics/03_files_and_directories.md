To create a new directory(folder) run the mkdir command followed by directory name
***Example 1***    #create single directory
<pre>$ mkdir project1 </pre>
 
***Example 2*** #create multiple directory
<pre>$ mkdir project2 project3 project3 </pre>

To create the empty file,run the touch command followed by filename
***Example 1*** #create the single directory
<pre>$ touch file.txt </pre>

***Example 2*** #create multiple file at once
<pre>$ touch file1.txt file2.txt file3.txt </pre>

To copy file from one location to another,run the cp command
<pre>$ cp source_file destination_file </pre>

To copy a directory and all its contents recursively run the cp -r command
<pre>$ cp -r source_directory destination_directory </pre>

To  move or  rename a file or directory,run the mv command 
<pre>$ mv source_file destination_file </pre>

To display the detailed information about a file or directory,run stat command:
<pre>$ stat file_name </pre>
 
To determine the type of the file, run the file command
<pre>$ file file_name </pre>

To check the disk usage of the file or directory,run the du command
<pre>$ du filename </pre>

To check the disk usage in the human readable format, run du -h command
<pre>$ du -h file_name</pre>


To display filesystem diskspace usage ,run the df command
<pre>$ df <pre>

To display file system dsik space usage in human readable format run df -h command
<pre>$ df -h <pre>

To remove an empty directory,run the rmdir command followed by the directory which you want to delete:
<pre>$ rmdir folder_name </pre>

To remove a file, run rm command 
<pre>$ rm file.txt</pre>

To remove a file and its content recursively, rm -r command
<pre>$ rm -r file2.txt </pre>

To forcefully remove a directory and its contents without confirmation, run rm -rf command:
<pre>$ rm -rf dirname </pre>
