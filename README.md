# DataAnalysis_tutorial
このリポジトリでは、データ分析の勉強に使用したコードを載せていく
## Ohmsha_DataScience
[この本](https://www.ohmsha.co.jp/book/9784274222900/)の学習結果アウトプット
### パッケージ
以下のコードで必要なパッケージをインストールする
```
$ pip install -r requirements.txt
```
**rpy2**のインストールにはR言語のが必要のため、事前に以下のコマンドでインストールしておく
```
$ brew install R
```
また、**pyaudio**のインストールには、依存ライブラリであるportaudioが必要のため、事前に以下のコマンドでインストールしておく
```
$ brew update
$ brew install portaudio
$ brew link --overwrite portaudio
```