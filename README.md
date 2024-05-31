# ModuleFederation

Angular CLI: 15.2.11
Node: 18.20.3
Package Manager: npm 10.8.1
OS: win32 x64


Package&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Version
------------------------------------------------------
@angular-devkit/architect &nbsp;&nbsp;&nbsp;&nbsp;0.1502.11 (cli-only) <br>
@angular-devkit/core&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;15.2.11 (cli-only) <br>
@angular-devkit/schematics&nbsp;&nbsp;&nbsp;15.2.11 (cli-only) <br>
@schematics/angular&nbsp;&nbsp;&nbsp;&nbsp;15.2.11 (cli-only) <br>

ng new myApp --create-application=false

cd cd .\mono-workspace\

ng g application host-app --routing --style=scss

ng g application mfe-app --routing --style=scss

<terminal 01><br>
cd .\mono-workspace\  
ng s host-app -o 

<terminal 02><br>
cd .\mono-workspace\
ng s mfe-app -o 

<terminal 03><br>
cd .\mono-workspace\<br>
npm i webpack webpack-cli --save-dev<br>
ng add @angular-architects/module-federation --project host-app --port 4200<br>
ng add @angular-architects/module-federation --project mfe-app --port 4300<br> 
