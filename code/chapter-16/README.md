# 16章: Kerasを使ったエンドツーエンドのディープラーニングと、自動運転車のシミュレーション

16章はゲストによる寄稿のため、原著のリポジトリ[PracticalDL/Practical-Deep-Learning-Book/code/chapter-16](https://github.com/PracticalDL/Practical-Deep-Learning-Book/tree/master/code/chapter-16)でも外部のリポジトリ[microsoft/AutonomousDrivingCookbook/AirSimE2EDeepLearning](https://github.com/microsoft/AutonomousDrivingCookbook/tree/master/AirSimE2EDeepLearning)を参照しています。

上記のリポジトリでは [`InstallPackages.py`](https://github.com/microsoft/AutonomousDrivingCookbook/blob/7a412165fcff2bc427ea1498bb3c0ec7b1e0f522/InstallPackages.py) を利用しての環境構築が推奨されていますが、ライブラリのバージョン指定が無くそのままでは現在動作しないものがあるため、次のようにバージョンを指定してインストールしてください:

```
pip install --upgrade pip
pip install tensorflow==1.15.5
pip install keras==2.1.2
pip install keras-tqdm==2.0.1
pip install tqdm==4.40.0
pip install matplotlib==2.1.2
pip install msgpack-rpc-python
pip install pandas
pip install numpy
pip install h5py
```

```
conda install opencv
```

また、Python 3.7 系の動作に一部対応していないコードが含まれているため、Python 3.6 系の利用を推奨します。

- https://github.com/microsoft/AutonomousDrivingCookbook/issues/89
- https://github.com/microsoft/AutonomousDrivingCookbook/issues/116
