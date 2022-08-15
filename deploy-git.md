ng build --configuration production --base-href https://anilmj7.github.io/kpjgraniteexports/

angular-cli-ghpages -d dist/kpj-granite/ --no-silent


firebase:
ng build --configuration production --aot
firebase deploy