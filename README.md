# listfileext

`listfileext` is a small Python script that lists all file extensions in a given directory and all it's sub-directories (recursivly). 

## Usage

If you want to know e.g. what for (obscure) files are in your documents folder, open a terminal and use this script like this:

	listfileext.py ~/Documents

As you see, you can use any path as parameter.

## Hidden files

By default hidden directories and files (like `.git` or `.gitignore`) are skipped, if you want to scan for those also, just open the script in a text editor of your choice and set the value of `skip_hidden_items` from `True` to `False`.
