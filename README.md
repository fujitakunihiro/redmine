# 前提
docker desktopをインストール

# redmineをインストール
mkdir redmine
docker run -d -p 3000:3000 redmine:5.1

# アクセス
http://localhost:3000

admin/admin
