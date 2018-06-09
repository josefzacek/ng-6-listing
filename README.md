# nglisting

https://nglisting.josefzacek.com

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Deployment

Install angular-cli-ghpages

`npm i -g angular-cli-ghpages`

Built app and optimize for production

`ng build --prod `

Add CNAME file (needed for custom subdomain setup)

`echo "nglisting.josefzacek.com" > dist/CNAME`

Publish to gh-pages (nglisting is name of app)

`ngh --dir dist/nglisting --no-silent`
