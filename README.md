# opensphere-tests-vscode
Code snippets for use with Visual Studio code when writing tests in Cypress.  These snippets are written for direct use with [opensphere](https://github.com/ngageoint/opensphere).  Also contains settings for Visual Studio Code.

## Features
Adds snippets for...
* New spec files
* Working with elements, and descendants of elements
* Error handling
* Image comparisons

Adds settings for...
* ```cypress.json``` intelligent code completion
* File move, save, and delete behavior
* Tabs, spaces, and ruler
* Windows support (line endings, Git bash)

## Installation
Note: Snippets must ***not*** be located in a subfolder to .vscode; if they are they won't work. Cloning in a way that results in ```.vscode/opensphere-tests-vscode/*snippet_files*``` existing, will not work.  Expected: ```/opensphere/.vscode/*snippet_files*```

Choose ONE option below:

* Project: To clone from project root and create the .vscode folder at the same time:
        
         cd to /opensphere

         git clone https://github.com/justin-bits/opensphere-tests-vscode.git .vscode

* Project: To create the .vscode folder in the project, then clone from within the folder:
      
        mkdir .vscode

        cd .vscode

        git clone https://github.com/justin-bits/opensphere-tests-vscode.git .