# Deploy express on ts-node env to Heroku server

## How to use

1. Clone this repository and Install dependency

```
git clone
npm install
```

2. Set up Heroku environment

Heroku account is needed. Please sign one up for this application.

1. Install [heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)

```
brew tap heroku/brew && brew install heroku
```

2. Remove existing git repo and create a new one

```
rm -rf .git
git init
```

2. Log into Heroku account and create a new project

```
heroku login
heroku create <project name>
```

3. Make sure the heroku remote exists

```
git remote -v
```

4. Push code to heroku server to deploy

```
git add .
git commit -m"Init project"
git push heroku master
```
