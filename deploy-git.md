GIT:
ng build --configuration production --base-href https://anilmj7.github.io/kpjgraniteexports/
angular-cli-ghpages -d dist/kpj-granite/ --no-silent


firebase:
npm install -g firebase-tools
firebase login
firebase init

ng build --configuration production --aot
firebase deploy

https://www.bacancytechnology.com/blog/deploy-angular-12-application-using-firebase-hosting