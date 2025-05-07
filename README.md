1. ng new mono-workspace --create-application=false
    cd mono-workspace
2. ng g application host-app --routing
3. ng g application mfe-app --routing
4. npm i webpack webpack-cli --save-dev 
    - install webpack cli
5. ng add @angular-architects/module-federation --project host-app --port 4200
6. ng add @angular-architects/module-federation --project mfe-app --port 4201

## TODO
- Run two projects in the same host