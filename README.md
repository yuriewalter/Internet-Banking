# Internet Banking

## Getting started
You can follow this README or you can follow this [video](https://mifosforge.jira.com/wiki/spaces/docs/pages/498794497/Developer+Environment+Setup+for+Online+Banking+App+2.0).

Clone the project:

    $ git clone https://github.com/openMF/web-self-service-app.git

Install dependencies:

    $ cd web-self-service-app
    
    $ npm install
    $ bower install

Install gem 'sass'
    
   Make sure that you have '''ruby''' installed (if not goto https://www.ruby-lang.org/en/documentation/installation/ ).
        
    $ gem install sass

Run development web-server:

    $ gulp serve

Use these credentials to logIn `username: selfservice password: password`

    
## Contributing Guidelines:
* Contributors must follow these [guidelines](https://github.com/openMF/web-self-service-app/blob/develop/CONTRIBUTING.md)    

## Features

* AngularJS
* Angular UI Router
* Angular Material
* Sass styles
* Gulp build
* Stylish, clean, responsive layout with original design
* BrowserSync for the ease of development

## Deploy to Github pages  

    $ gulp build
    $ gulp deploy
