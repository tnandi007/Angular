# How do you create a new angular app without installing Angular CLI globally ?
1. Create a folder , put a package.json file there with only one dependency

                 "dependencies": {
             "@angular/cli": "11.2.2"
           }
2. Went into that folder, run  --> npm install (so now you have required angular CLI node modeuled downloaded here)
3. Now you can run -- > npm run ng new <app_name> to get started.

** This will help you to build application in different angular versions as you want
