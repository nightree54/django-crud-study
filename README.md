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

## 📸 画面イメージ

### ■ ユーザー向け画面

![ユーザー画面](https://github.com/nightree54/project-images/blob/main/django_user_page.png)

商品一覧の表示機能を実装。  
CRUD操作（詳細・編集・削除）およびページネーションに対応。

---

### ■ 管理画面（Django Admin）

![管理画面](https://github.com/nightree54/project-images/blob/main/django_admin_page.png)

Django標準のAdmin機能を活用し、商品データの管理機能を実装。  
画像のプレビュー表示にも対応。

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
cd django-crud-study

pip install -r requirements.txt

python manage.py migrate
python manage.py runserver