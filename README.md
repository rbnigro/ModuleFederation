# ModuleFederation


#   / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
#   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
#  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
# /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/


Angular CLI: 15.2.11
Node: 18.20.3
Package Manager: npm 10.8.1
OS: win32 x64

Angular:
...

Package                      Version
------------------------------------------------------
@angular-devkit/architect    0.1502.11 (cli-only)
@angular-devkit/core         15.2.11 (cli-only)
@angular-devkit/schematics   15.2.11 (cli-only)
@schematics/angular          15.2.11 (cli-only)

ng new myApp --create-application=false

cd cd .\mono-workspace\

ng g application host-app --routing --style=scss

ng g application mfe-app --routing --style=scss

cd .\mono-workspace\  
ng s host-app -o 

cd .\mono-workspace\  
ng s mfe-app -o 
