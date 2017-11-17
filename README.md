
You're going to need a couple things before proceeding:

    Node.js
    
    Node Packange Manager (NPM)
    
To check whether or not you have both of these installed, visiting your command line or console and type:

$ node -v

$ npm -v

Installing Angular 5 through the CLI

$ npm install -g @angular/cli@latest

To check the version of your Angular CLI, type:

$ ng -v

To install Angular 5 through the CLI, type:

$ ng new my-new-project --style=scss --routing

$ cd my-new-project

Execute the package installation via:

$ npm install

launch the development web server:

$ ng serve

__________________________________________________________________________________

Uninstall and install latest version :

npm uninstall -g angular-cli @angular/cli       (with admin rights)

npm cache clean --force                                       (with admin rights)

npm install -g @angular/cli@latest                   (in a new terminal without admin rights)

__________________________________________________________________________________

Troubleshooting if above do not work :

1) Uninstall existing @angular/cli

npm uninstall -g @angular/cli

npm cache clean --force                                       

Remove npm folder from <USER_HOME_DIR>\AppData\Roaming

2)      Uninstall Node.js (in Control Panel\Programs\Programs and Features)

3)      Install Node.js version 6.11

Get the installation file "node-v6.11.0-x64.msi" 

4)      Install @angular/cli globally

npm install -g @angular/cli@1.1.2

5)      Modify "<USER_HOME_DIR>\AppData\Roaming\npm\ng.cmd" to add --max_old_space_size=5048 parameter to the command

__________________________________________________________________________________

Commands to build the app:

Dev Mode : 

ng build --env=prod

Prod Mode : 

ng build --prod --output-hashing=none

Use the below command to build the angular app for production environment. With this, the size of the js files generated will be decreased from 25 MB to 5 MB so that the initial loading time of the files from server will be reduced.

ng build --prod --aot=false --output-hashing=none

__________________________________________________________________________________

troubleshooting with Logs,  will be written to build.log file.

build --prod --verbose > build.log

If you get the below error when you build the app then modify "HOME_DIR\AppData\Roaming\npm\ng.cmd" to add --max_old_space_size=5048 parameter to the command. Attached the same file for your reference.

FATAL ERROR: CALL_AND_RETRY_LAST Allocation failed - JavaScript heap out of memory

__________________________________________________________________________________

Installing specific components /librarys :

npm install node-uuid --save

npm install ng2-simple-timer --save

__________________________________________________________________________________


Angular API Reference : 

https://angular.io/docs/ts/latest/api/

https://angular.io/docs/ts/latest/api/core/index/

https://github.com/angular/angular

https://github.com/angular/angular-cli

https://github.com/angular/angular/blob/master/CHANGELOG.md


Reference links:

1**)  https://angular.io/docs/ts/latest/quickstart.html 

2) https://www.bennadel.com/blog/2542-logging-client-side-errors-with-angularjs-and-stacktrace-js.htm

3) https://blog.thoughtram.io/categories/angular-2/

4) https://www.tutorialspoint.com/angular2/index.htm

5) https://www.sitepoint.com/angular-2-tutorial/

6) http://learnangular2.com/

7) http://www.typescriptlang.org/docs/tutorial.html

8) https://github.com/mgechev

9) https://egghead.io/courses/angular-2-fundamentals

10) http://blog.mgechev.com/2016/01/23/angular2-viewchildren-contentchildren-difference-viewproviders/

11) https://angular-2-training-book.rangle.io/handout/advanced-angular/directives/view_containers_and_embedded_views.html

12) https://github.com/Velkata?tab=stars

13) https://auth0.com/blog/angular-2-series-part-3-using-http/

14) https://yakovfain.com/category/angular2/

15) https://www.tektutorialshub.com/angular-http-tutorial-with-rxjs-observables/

16) https://ruanbeukes.net/Angular-Typesafe-Reactive-Forms/

17**) https://codecraft.tv/courses/angular/custom-directives/creating-a-custom-directive/

18) https://github.com/angular/angular-cli/releases

19) https://docs.google.com/document/d/1Hv3VTRQC0H5yPe8ivJXaGst93yRAtD6nEFkQDLiK_IU/preview#heading=h.dfcbc7alhbcv

20) https://www.udemy.com/the-complete-guide-to-angular-2/learn/v4/announcements

21) https://blog.codewithdan.com/2017/02/08/10-angular-and-typescript-projects-to-take-you-from-zero-to-hero/

Thanks,
Charanseeram


 
