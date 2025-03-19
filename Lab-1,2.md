Experiment Description - Use the touch command to create sets of empty practice files to use during this lab. In each set, replace X with the numbers 1 through 6. Create six files with names of the form songX.mp3, snapX.jpg, filmX.avi.
Create three subdirectories for organizing your files, and name the subdirectories friends, family, and work. Use a single command to create all three subdirectories at the same time.

-The touch command with brace expansion is used to create multiple files efficiently.

touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi

-The mkdir command is used to create multiple directories in one go.

mkdir freinds family work

-The ls command is used to list the created files and directories.

ls

![Screenshot 2025-02-04 104517](https://github.com/user-attachments/assets/09b0a624-4177-4fcc-a8fb-e09a0fbcc2bc)
