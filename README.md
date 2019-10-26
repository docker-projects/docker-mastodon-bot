#  Mastodon Bot




## Crear la imagen

```
docker build -t mastodon .
```

## Crear el docker mastodon desde la imagen mastodon

```
docker run --name mastodon mastodon     
```


## Ejecutar el Bot

```
docker exec -it mastodon python3 bot.py

```


Based off the [tutorial written by Terence Eden](https://shkspr.mobi/blog/2018/08/easy-guide-to-building-mastodon-bots/)

Create your `token.secret` in the same directory as `bot.py`. Have fun and run!
