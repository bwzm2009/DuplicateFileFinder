# Duplicate File Finder

A user-friendly GUI tool designed to help you find and manage duplicate files on your system. Built with Python and PyQt5, the tool provides a range of options from filtering search criteria to multiple file deletion methods.

## Features:

- **Intuitive GUI**: Easily navigate and manage duplicate files.
- **Search Criteria**: Filter search based on file size, extensions, and even skip certain extensions.
- **Delete Options**: Choose from deleting permanently, moving to trash, moving to a new folder, or replacing with a hard link.
- **ZIP File Handling**: The tool can search inside ZIP files for duplicates and handle them effectively.

## Prerequisites:

- **Python**: Ensure Python is installed on your system. If not, download and install it from [Python's official site](https://www.python.org/downloads/).
  
- **7-Zip**: This tool utilizes 7-Zip for handling ZIP files. Make sure to have 7-Zip installed and its path configured. The default expected path for 7-Zip is `C:\Program Files\7-Zip\7z.exe`. You can download 7-Zip from [here](https://www.7-zip.org/download.html).

## Installation & Setup:

1. Download the `DuplicateFileFinder.py` file.

2. Install the required Python packages:
    ```bash
    pip install PyQt5 send2trash
    ```

3. Run the application:
    ```bash
    python DuplicateFileFinder.py
    ```

## Usage:

1. **Search Directories Tab**: Add directories you want to search for duplicates. You can add multiple directories.
2. **Search Criteria Tab**: Specify file size range, file extensions to search, and extensions to skip. You can also choose to search inside ZIP files.
3. **Delete Options Tab**: Choose how you want to delete the duplicate files.
4. **Duplicates Tab**: View and manage the found duplicate files.

## Future Features:

- Limit scanning of folder against itself.
- Percent similar search functionality
- Limit search by file date
- Limit search to file name and/or size, not hash
- Limit search to created/modified date

## Contributing:

If you find any bugs or wish to suggest a new feature, please open an issue or submit a pull request.

## Imortance Notice:

I am not a programmer, most of this code was developed through internet searches, help from AI, and other resources.


## License:

This project is open-source and available under the MIT License.
