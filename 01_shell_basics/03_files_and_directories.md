1.<strong>File and Directory Creation</strong> <br>
commands used to intialize new file or folder structures within filesystems <br>

<strong>touch</strong> <br>
<pre> touch filename </pre>
Creates the new empty file if it does not exists <br>

<strong>mkdir</strong> <br>
<pre> mkdir directory_name </pre>
Creates the directory in the specified path <br>

2.<strong> File and Directory Deletion</strong> <br>
Commands used to delete data from the system <br>

<strong> rmdir </strong> <br>
<pre> rmdir directory_name </pre>
Removes an empty directory from the filesystem <br>

<strong> rm </strong> <br>
<pre> rm filename</pre>
removes specific file to delete <br>

<strong>rm -r</strong> <br>
<pre> rm -r directory_name </pre>
Recusively deletes the directories and all of its content,includung subdirectories <br>

<strong>rm -rf</strong> <br>
<pre> rm -rf directory_name </pre>
Forcefully and recursively removes the directories without promting for conformation <br>

3.<strong> File Manuplation and Movement </strong> <br>
Commands for copying,moving and renaming files or directories <br>

<strong>cp</strong> <br>
<pre> cp source_file destination_file </pre>
copies files from one location to another <br>

<strong> cp -r </strong> <br>
<pre> cp -r source_directory destination_directory </pre>
Copies an entire directory and all its contents to new location <br>


<strong> mv </strong> <br>
<pre> mv source_file destination_file </pre>
Moves or renames the files and directories within the filesystem <br>

4.<strong>File Information and MetaData</strong> <br>
Commands used to inspect the properties,types and specific details of files <br>

<strong>stat</strong> <br>
<pre> stat file_name </pre>
Displays the detailed status information about the file including size,permission and timestamps.<br>

<strong>file</strong> <br>
<pre>file file_name </pre>
Determines the file type by inspecting its contents and header information <br>

<strong>basename</strong> <br>
<pre> basename [path] </pre>
Returns the final component only<br>

<strong>dirname</strong> <br>
<pre> dirname [path] </pre>
returns the parent directories portion of the file path<br>

5.<strong> Disk and Storage Usage </strong> <br>
Commands designed to monitor how much space is being utilized on the system <br>

<strong>du </strong> <br>
<pre> du [path] </pre>
Estimates the file space usage of particular directory or file <br>


<strong> du -h</strong> <br>
<pre> du -h </pre>
Displays disk usage in human-redable format using kilobytes,megabytes or gigabytes <br>

<strong>df</strong> <br>
<pre> df </pre>
Reports the amount of avaliable and disk uspace on all currently mounted filesystems <br>


<strong>df -h</strong> <br>
<pre> df -h</pre>
provides human readable summary of avaliable disk space across the system partitions
