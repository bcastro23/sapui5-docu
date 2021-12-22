# SAPUI5 - Learning

## UI5 Tooling
https://sap.github.io/ui5-tooling/

## Quick start SAPUI5
https://sapui5.hana.ondemand.com/#/topic/592f36fd077b45349a67dcb3efb46ab1

## Getting started ui5 CLI
https://sap.github.io/ui5-tooling/pages/GettingStarted/

### Create a project manually **(not best option)**
1- Create root app Folder e.g. MyApp
2- Create the app folder , a new folder called MyApp/webapp
3- Create pakage.json file $ npm init --yes
4- Create ui5.yaml file $ ui5 init
5- Create manifest.json file (create it manually)
	https://help.sap.com/doc/7e1c608ceda2445a8482d5335a41b5cf/1610%20001/en-US/74038a52dcd7404e82b38be6d5fb1458.html


### Another way to start with your project is by installing Yeoman template ###
1. check the templates $ yo --generators

 	@sapui5/sapui5-templates
	    1worklist
	    2masterdetail
	    3worklistodatav4
  	easy-ui5

2. Create new project for Fiori worklist, masterdetail or worklist odata
	$ yo @sapui5/sapui5-templates
	 ## https://www.npmjs.com/package/@sapui5/generator-sapui5-templates

3. Basic UI5 use easy-ui5 generator
	https://www.npmjs.com/package/generator-easy-ui5

	npm install -g yo generator-easy-ui5

	Scaffold project -> $ yo easy-ui5 project
	
4. Adding libraries
	$ ui5 add *library name* --config [ui5.yaml location] -> this adds library to ui5.yaml file
	$ npm i -> install dependencies to project

### Start with UI5 development and VS Code
	https://blogs.sap.com/2021/10/15/getting-ready-for-ui5-development-with-visual-studio-code/



