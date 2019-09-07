# ansible_sample
Wordpress作成用のサンプルPlaybookとして2つのPlaybookを用意しています。

common.yml
パッケージディレクトリのアップデートやnginxのインストール、初期設定といった共通内容を記載
wordpress.yml
wordpressをインストールし初期設定を実施
以下のコマンドを実行すると、それぞれのPlaybookを実行できます。

`ansible-playbook -i inventory common.yml`
common.ymlの実行が終わったあと、wordpress.ymlを実行します。

`ansible-playbook -i inventory wordpress.yml`