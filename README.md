# gitea on Docker-compose
git管理できるサービス．giteaのDockerImageファイルです．
公式のマニュアルを参考にし，作成しました．特に変更は加えていません．環境バックアップ用です．
 
# DEMO
None

# Requirement
 
"gitea on Docker-compose"を動かすのに必要なライブラリなどを列挙する
 
* Docker version 20.10.12, build e91ed57
* docker-compose version 1.25.0, build unknown
* Docker-images:gitea:1.16.0,mysql:8
* baseServer:ubuntuserver20.04.3x64,IntelArc
 
# Installation
 
Requirementで列挙したライブラリなどのインストール方法を説明する
 
```bash
cd gitserver_on_docker
docker-compose up -d
```
http://(host):3000にアクセス<br>
初期設定を確認し，問題がないようだったら，インストール＞ユーザー作成
# Usage
 
利用方法はGitHubと同じ．
 
```bash
mkdir (newfolder)
cd (newfolder)
git init
touch readme.md
git add .
git commit -m 'firstCommit'
git push -u origin main
```
以降，ユーザー作成時に作成した，IDとパスワードを入力する．
 
# Note
ssh ポートの開放は，公式ページは以下のサイトから詳細である．
(https://docs.gitea.io/en-us/install-with-docker/) 
# Author
 
作成情報を列挙する
 
* 作成者:Amembo
* E-mail:(c0b20140d0@edu.teu.ac.jp)
