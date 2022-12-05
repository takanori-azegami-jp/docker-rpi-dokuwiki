# docker-rpi-dokuWiki
RaspberryPi(64bit)にDockerでDokuWikiを構築（Wiki構築）

## コンテナ起動
docker-compose.ymlを配置したフォルダに移動して実行
~~~
$ docker-compose up -d --build
~~~
## ブラウザからURLでDokuWikiに接続
~~~
http:// [DockerホストのIPアドレス] :8080
~~~
![picture 1](images/README/1670203476014.png)  


## 参考
[docker-composeを利用してDokuWikiを構築する](https://mebee.info/2020/07/04/post-13052/)
