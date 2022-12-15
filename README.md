# image-upload-with-process

講義の演習課題サンプル

画像のアップロードを行うWebインターフェイスと、アップロードされた画像のファイル変更を検知して画像処理を行う画像処理プログラムを組み合わせたシステムの構築

## Initial Setting

```zsh
$ git clone https://github.com/2022AIT-OOP2-GXX/image-upload-with-process.git
$ cd image-upload-with-process
$ python -m venv .env
$ source .env/bin/activate
(.env) $ pip install -r requirements.txt
```

## Require

```
Flask==2.2.2
opencv-python==4.6.0.66
watchdog==2.2.0
```

## Usage
### Webインターフェイスの起動

```zsh
$ source .env/bin/activate
(.env) $ python web.py
```

### 画像処理プログラムの起動

```zsh
$ source .env/bin/activate
(.env) $ python image_process.py
```
