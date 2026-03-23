# Django 商品管理アプリ

## ■ 概要
Djangoを用いて開発した商品管理Webアプリケーションです。  
商品一覧の表示、詳細確認、追加・編集・削除（CRUD機能）を実装しています。
本アプリケーションは基本機能を実装済みであり、今後さらなる機能拡張および改善を予定しています。

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

---

### ■ 管理画面（Django Admin）

![管理画面](https://github.com/nightree54/project-images/blob/main/django_admin_page.png)

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
```

---

## ■ 今後の改善点

- 管理画面における画像サイズの最適化  
  アップロード後に自動でリサイズ処理を行い、表示サイズを適切に調整する。

- 編集画面における画像のデフォルト表示対応  
  既存画像を削除（clear）した場合、再アップロードが行われないときはデフォルトのNoImage画像を表示する。

- 商品名の重複防止機能の実装  
  同一の商品名が登録されないよう、バリデーション処理を追加する。

- staticディレクトリの整備  
  デフォルト画像（NoImage）を管理するため、`/static` フォルダを作成し、画像ファイルを配置する。