# opensphere-tests-vscode
Code snippets for use with Visual Studio code when writing tests in Cypress.  These snippets are written for direct use with [opensphere-tests](https://github.com/justin-bits/opensphere-tests).  Also contains settings for Visual Studio Code.

## Features
Adds snippets for...
* New spec files
* Working with elements, and descendants of elements
* Error handling

Adds settings for...
* ```cypress.json``` intelligent code completion
* File move, save, and delete behavior
* Tabs, spaces, and ruler

## Installation
1. Ensure the .vscode folder exists at the root of the project. Note that the .vscode folder is hidden and may need to be created. ```\opensphere\.vscode```
        
        mkdir .vscode
  
2. Clone this repository directly to the .vscode folder in the project.  Snippets must ***not*** be located in a subfolder to .vscode; if they are they won't work. 

   * To clone from project root
        
         git clone https://github.com/justin-bits/opensphere-tests-vscode.git
        
   * To clone from within ```.vscode```
 
         git clone https://github.com/justin-bits/opensphere-tests-vscode.git .