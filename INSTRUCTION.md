ng new mono-workspace --create-application=false
ng g application host-app --routing
ng g application mfe-app --routing
npm i webpack webpack-cli --save-dev - install webpack cli
ng add @angular-architects/module-federation --project host-app --port 4200
ng add @angular-architects/module-federation --project mfe-app --port
