# Djangogirls_pure

Django girls チュートリアルの見本
https://tutorial.djangogirls.org/ja/

## Usage
### 仮想環境

作成
```
(myvenv) PS C:\Users\USER\djangogirls> python -m venv myvenv
```

起動
```
(myvenv) PS C:\Users\USER\djangogirls> . myvenv\Scripts\activate.ps1. myvenv\Scripts\activate.ps1
```

終了
```
(myvenv) PS C:\Users\USER\djangogirls> deactivate
```

### Djangoのインストール
```
(myvenv) ~$ pip install -r requirements.txt
```
### ブログのデータベースを作成
```
(myvenv) ~/djangogirls$ python manage.py migrate
```
### ウェブサーバを起動
```
(myvenv) ~/djangogirls$ python manage.py runserver
```
### gitの仕方
```
(myvenv) PS C:\Users\USER\djangogirls> git branch
(myvenv) PS C:\Users\USER\djangogirls> git add
(myvenv) PS C:\Users\USER\djangogirls> git commit -m""
(myvenv) PS C:\Users\USER\djangogirls> git push origin ブランチ名
```