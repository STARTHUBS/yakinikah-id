# yakinikah-id

### Requirements

First of all, make sure that you have install these all requirements on your machine:
- PHP >= 5.6.4 with Mbstring PHP Extension, mysql
- Composer
- NodeJs
- NPM
- Gulp

### Installation

- Run `composer install`
- Run `npm install`
- cd node_modules/semantic-ui
- Run `gulp install` => select `Automatic` => Select 'Yes' => Type `resources/assets/semantic` when asked `where to put semantic-ui`
- Navigate to `resources/assets/semantic`
- Run `gulp build`
- Move env.development to .env by typing cp env.development .env
- Change `DB_DATABASE`, `DB_USERNAME`, `DB_PASSWORD` and ohter configuration
- Run `npm run dev`