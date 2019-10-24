# WindowsScriptSchortcutTool

Tool to manage batch file that are copied to `C:\Windows\System32\` for ease of access through the home menu on Windows 10.

Different scripts have roles to allow you to import or export your files from the local folder to the destination one (in this case System32).

## How to use

### export

- Clone the repository.

- Put a batch file under the "batch" directory of this repository.

- Execute the `export.bat` file (with elevated access).

- Verify that the file was copied by executing the `list.sh` file (with git bash)

- Open the Home Menu and type `nameOfFile.` in the menu to see your script appear.

### import

- Execute the `import.sh` file using git bash.

- Now the batch files that were under `C:\Windows\System32\` should be copied under the "batch" directory of the repository.

## Tips

I would recommend instanciating a local git repository under the "batch" folder to keep track of changes made to the scripts.
