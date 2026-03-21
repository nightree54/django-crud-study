# Django 商品管理アプリ

## ■ 概要
Djangoを用いて開発した商品管理Webアプリケーションです。  
商品一覧の表示、詳細確認、追加・編集・削除（CRUD機能）を実装しています。

---

## ■ 主な機能
- 商品一覧表示
- 商品詳細表示
- 商品の新規登録
- 商品情報の編集
- 商品の削除
- 管理画面（Django Admin）

---

## ■ 使用技術
- Python
- Django
- HTML / CSS
- SQLite

---

## ■ セットアップ方法

```bash
git clone https://github.com/nightree54/django-crud-study.git
cd django-product-crud

pip install -r requirements.txt

python manage.py migrate
python manage.py runserver