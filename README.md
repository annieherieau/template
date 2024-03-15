
# Project

description



## Demo

url / video / photo



## Installation (Ruby 3.2.2)

Clone repository

```bash
git clone git@github.com:Korblen/Projet_chaton_ultimate.git
```

Install dépendencies

```bash
bundle install
```
Precompile Assets

```bash
bundle exec rake assets:precompile
```

Database

```bash
rails db:create
rails db:migrate
rails db:seed
```

Launch server

```bash
rails server
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

```bash
MAILJET_LOGIN=''
MAILJET_PWD=''
MAILJET_DEFAULT_FROM=''

STRIPE_PUBLISHABLE_KEY=''
STRIPE_SECRET_KEY=''

DEV_HOST='http://localhost:3000'
PROD_HOST=''

# pour la prod sur Heroku
CLOUDINARY_CLOUD_NAME=""
CLOUDINARY_API_KEY=""
CLOUDINARY_SECRET_KEY=""
CLOUDINARY_URL="cloudinary://api_key:secret_key@cloud_name"
```
