Steps for angular app:

1.	Angular requires Node.js in your system, you can download Node Package Manager from https://nodejs.org/en/
2.	Never download latest one instead always download recommended one
3.	Type “node -v” command to check which version is installed
4.	Install Angular CLI using 
5.	npm install -g @angular/cli
6.	If it doesn’t work then login as a ROOT and try reinstalling it.
7.	Check angular version using command “ng -version”
8.	Go to webapp folder and run command “npm install” to install all the required dependencies
9.	Then go to webap/src/app/shared/services/api.service.ts
10.	Inside file “api.service.ts” you can find an object named as “public booksRoot: string=” inside the class
11.	Assign your API url to that object within double quotes
12.	Then run “npm run build” to build your project files
13.	After that you can build your docker image using “docker build -t {image name} .”
