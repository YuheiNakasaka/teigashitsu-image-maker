# 低画質画像メーカー

低画質な画像を生成するする「低画質画像メーカー」のコマンドライン版です。

jpg/png/gifの静止画に対応。透過もいける。

# Requirement

- Python3.x
- pip
- numpy
- Pillow
- scikit-learn

# Option

- Imagemagick
  - ImagemagickいれてPATHが通ってればgifアニメーションも一応変換できたりする。透過入ってると汚い画像になるけど。

# USAGE

一番ラクなやつ。実行場所にoutput.pngができる。

```
python teigashitsu -f target.jpg
```

ドットサイズを指定することもできる。

```
python teigashitsu -f target.jpg -s 2
```

色数を指定することもできる。

```
python teigashitsu -f target.jpg -s 2 -c 8
```

- -f(入力画像)
  - 必須
- -o(出力画像)
  - 任意
- -s(ドットサイズ)
  - 任意
- -c(色数)
  - 任意
