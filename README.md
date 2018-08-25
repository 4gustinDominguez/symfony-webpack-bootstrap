# Symfony-webpack-bootstrap

```sh
$ git clone https://github.com/4gustinDominguez/symfony-webpack-bootstrap.git name-project
$ cd name-project
$ composer install
$ yarn install


yarn run encore dev
php -S 127.0.0.1:8000 -t public
```

Manual

#### Create symfony project
```sh
composer create-project symfony/website-skeleton name-project
```

```sh
cd name-project
```
#### Web Pack
```sh
yarn add @symfony/webpack-encore --dev
````

#### Add sass loader
```sh
yarn add sass-loader node-sass --dev
```

##### Bootstrap
```sh
yarn add jquery popper.js
```

###### boostrap 3.3.7
```sh
yarn add bootstrap-sass --dev 
```

###### boostrap 4.*
```sh
yarn add bootstrap --dev
```

##### Crear assets
```sh
yarn run encore dev
yarn run encore dev --watch
yarn run encore production
```