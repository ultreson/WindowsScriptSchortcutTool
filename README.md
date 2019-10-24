# WindowsScriptSchortcutTool

Tool to manage batch file that are copied to C:\Windows\System32\ for ease of access through the home menu on Windows 10.

Different scripts have roles to allow you to import or export your files from the local folder to the destination one (in this case System32).

## How to use

- Clone the repository.

- Put a batch file under the "batch" folder of this repository.

- Execute the "export.bat" file (with elevated access).

- Verify that the file was copied by executing the "list.sh" file (with git bash)

- Open the Home Menu and type "nameOfFile." in the menu to see your script appear.

## Tips

I would recommend instanciating a local git repository under the "batch" folder to keep track of changes made to the scripts. 