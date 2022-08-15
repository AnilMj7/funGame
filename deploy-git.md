GIT:
ng add angular-cli-ghpages

ng build --configuration production --base-href https://anilmj7.github.io/funGame/
angular-cli-ghpages -d dist --no-silent


firebase:
npm install -g firebase-tools
firebase login
firebase init

ng build --configuration production --aot
firebase deploy

https://www.bacancytechnology.com/blog/deploy-angular-12-application-using-firebase-hosting