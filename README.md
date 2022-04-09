# PySparkの学習用レポジトリ

## 参考文献
[【PySpark入門】第１弾 PySparkとは？](https://blog.serverworks.co.jp/introducing-pyspark-1)

## dockerで起動
* イメージの取得
    ```
    docker pull jupyter/pyspark-notebook
    ```
* 起動
    ```
    $ docker run -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes --name pyspark jupyter/pyspark-notebook
    ```