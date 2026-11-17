Please create a simple Python desktop application using Tkinter
to compare a source folder with a backup folder.

Context:
This is a small prototype inspired by a file housekeeping workflow.
It will be tested using dummy files, not real business data.

Requirements:

1. Allow the user to select a source folder and a backup folder.

2. When the user clicks "Scan", recursively compare the files using
   their relative paths.

3. Display files that exist in the source folder but are missing
   from the backup folder.

4. Display the results clearly in the application, including:
   - Relative file path
   - Status

5. Allow the user to export the results as a CSV file. Ask the user
   where to save the report, and prevent the report from being saved
   inside either selected folder.

6. Show clear messages if folders are not selected, a folder cannot
   be accessed, or no missing files are found.

7. The application must only read and compare files. Do not copy,
   move, modify, or delete any files.

8. Use only the Python standard library. Provide the complete code
   in one Python file, with brief instructions on how to run it.

Please make the interface clear and professional, with a simple
layout suitable for a business user.
