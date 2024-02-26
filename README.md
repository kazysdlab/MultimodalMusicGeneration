**実行環境**
|環境条件|バージョン|
| --- | --- |
|Python|3.10|
|Pytorch|2.11+CUDA|
|CUDA|12.1|
実行環境の構築は、Dockerで`DockerFiles/DockerFile2`を使用してイメージを作成して下さい。
また、必要なパッケージが欠落していた場合は適宜pipなどでインストールしてください。
基本的には実行するコードは`Jupyters`内に格納されています。変換層のモデルを構築する場合、`Jupyters/CLIP_CLAP_Train_Final.jpynb`をJupyter Lab上で実行して下さい。
