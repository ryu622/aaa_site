#タイトル aaa_site (あああの勉強法解説サイト）

#概要・背景 
私が受験生時代に欲しかった情報（勉強法やおすすめ参考書など）について解説するサイトを作成しました。お問い合わせフォームからサイトを見た人の要望などを私のGメールに送信する機能を実装し、
見た人の意見を参考にできるようにしました。メールアドレスやパスワードは環境変数に設定することで秘匿しています。以下がRenderにてデプロイした際のURLです。https://flask-aaa-site.onrender.com

#インストール方法 
git clone https://github.com/ryu622/aaa_site.git 
cd aaa_site 
pip install -r requirements.txt

#使用方法 
１．サイト自体はWebサイトとなっています。
２．お問い合わせフォームに必要事項を記入し送信すると製作者のメールアドレスに内容が送信されるようになっています。

#機能一覧 
・Webサイト機能（HTMLとCSSを使用）
・お問い合わせ機能(FlaskでFORM機能を実装）

#開発環境・技術スタック 
Python,Flask,HTML,CSS

#ライセンス 
MIT License

#作成者 
https://github.com/ryu622
