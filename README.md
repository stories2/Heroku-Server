# Heroku-Server
Heroku push server

## How to deploy

```
git push heroku master
```

## How to scale up / down heroku dyno

```
heroku ps:scale web=<number of container>
```

## How to run locally

```
heroku local web
```

## Troubleshooting

### Cannot deploy app

- Make sure original git push commit. Then, push to heroku.