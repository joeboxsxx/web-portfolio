# Web Front Portfolio

Tech Select 学習サイト 実践編 ポートフォリオ のソースコードです。

```sh
# Start
$ docker run -dit --rm --name portfolio1 -v "$PWD/public":/usr/local/apache2/htdocs/ -p 3000:80 httpd:2.4-alpine
```

<http://localhost:3000/>

```sh
# Stop & Remove Container
$ docker stop portfolio1
```
# web-portfolio
