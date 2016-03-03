# pick-basic-syntax-def
Sublime Text PICK/BASIC syntax definition

I had to make the transition from more modern development environments to working on Epicor Eclipse (http://www.epicor.com/products/eclipse-software.aspx) and working in their version of PICK/BASIC. Their Eterm editor is usable, but has some severe limitations. So, I made a new workflow that included SublimeText.

The YAML-tmLanguage file is for use with the Sublime Text Packag Dev: https://github.com/SublimeText/PackageDev . I have been slowly building the regex over time. It's not perfect, and my regex isn't top notch, but that's why I am putting it here. Help me make this better!


# My Workflow:

When editing a file in Eterm, I open a file in CBP as I normally would to make sure I am using Eclipse's internal version control and file locking system. 

I have sublime text setup with the SFTP plugin: https://wbond.net/sublime_packages/sftp. I use it to grab the file for local editing. 

In the editor, change syntax of the file to PICK/BASIC.

Save the file and push it back up to the server. 

Compile program in Eterm editor.

...

$PROFIT$






