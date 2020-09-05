## RAILS-REACT-APP

### Database

```rails db:create``` </br>
```rails db:migrate```

### Start

```rake start```</br>

Both React and Rails will start. Sweet, just one terminal window!

### Heroku Deploy

If you have already created your Heroku app, you can easily add a 
remote to your local repository with the heroku ```git:remote``` command.
All you need is your Heroku app’s name:

```heroku git:remote -a your-heroku-app```</br>
```set git remote heroku to https://git.heroku.com/your-heroku-app.git```</br>

#### Rename your remote:

```git remote rename heroku heroku-staging```</br>


#### To add corrects buildpacks to this project:

```heroku buildpacks:add heroku/nodejs --index 1```</br>
```heroku buildpacks:add heroku/ruby --index 2```</br>


#### Deploy:

```git push heroku your_branch:master```</br>
