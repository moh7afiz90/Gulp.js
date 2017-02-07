# Gulp.js
Step by step to download and configure Gulp.js

Gulp.js

                                            Download and install npm

Step 1: Download Node.js and it comes with NPM (Node Package Management).
	NPM (it lets you download stuff from the Internet ).
  
  
Step 2: 
	
                                                                Windows
		Open Windows PowerShell - Right click and Run as an Administrator 
	
                                                                 MacOS
		Open the Terminal - type  “sudo” to run the command as an Administrator

Recommendation 
Remove any old gulp.js version that might installed on your computer by:
“npm rm gulp -g”
Clear: to clear the screen.


Step 3: Download Gulp.js by: 
“npm install gulp-cli -g”
gulp - cli = gulp - command Line Interface
-g = Globally : so you don't need to run gulp in a specific folder or directory 

                                                      Setting Up a Project

Step 1: Create an empty directory (Sample Project) in where in your computer to 
put all of our assets and with PowerShell navigate to your directory by: “ cd ~” & “ cd copy/paste the directory folder ”



Step 2: Initiate npm by: “ npm init” .
	It basically create package.json file (fill it out)




Step 3: To install gulp in your project, command “ npm install gulp --save-dev ” 
	npm install gulp --save-dev  = I want to install gulp and save as 
 	development dependencies and make sure you are in the same directory as your project.



Step 4: Create the following folders (app/dist) 
	Any of the source code will go to app folder
	Inside app: create the following folders/directories (css, scss) and index.html
	app: any of the source code will in this folder(scss,sass,jade).
  dist: when we run those files in in (gulp) the result (css,html) will go to dist folder.


Step 5: Create (gulpfile.js) Important
	In order to use gulp, we need to give it a bunch of task of instructions  which will be 
	Inside this file. It depends on you project

                                                          Creating Task

Step 1: 
Declare a variable (var gulp = require(‘ gulp ’)); )
Declare function gulp.task(‘ task-name ’ , function() {
		
//do something here	
	
});
	


