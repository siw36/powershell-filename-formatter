![Filename Formatter](https://github.com/siw36/powershell-filename-formatter/blob/master/images/filename_formatter.png)

## Rename files by replacing strings and move the files to a destination directory
Filename Formatter is a simple PowerShell script that helps to customize filenames in a source directory and move them to a target directory.
Regardless of the file extension.

This is how it works:
• Define rules for renaming:
- Up to 4 characters / strings to be deleted.
- Up to 4 characters / strings to be replaced.
• Defining the file extension:
- Examples: avi, mkv, mp3, jpg etc. (without dot)
• Specify the source directory where the files are located:
- The source directory is searched recursively for all files with the appropriate file extension. (also subfolders)
• Specify the destination directory in which the files should be moved after renaming:
- The target directory and source directory can be identical if the files should not be moved.

Compatibility
Requirements for the program:
• Microsoft PowerShell 3.0 or later (pre-installed on every Windows)
• The installed version can be found with the following command: `$PSVersionTable.PSVersion`
