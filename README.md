# py-vscode-template
Visual Studio Code(以下、VSCode)を用いてPython開発環境を整える為のリポジトリ

## Python extension for Visual Studio Code のインストール
 - VSCodeのMarketplaceで`ms-python.python`と検索し、インストール・有効化を行う

## リポジトリのクローン&チェックアウト
 - `$ git clone https://github.com/kyosawa/py-vscode-template.git`
 - `$ cd py-vscode-template`
 - `$ git checkout -b develop remotes/origin/develop`

## pipenvによるPython仮想環境の構築
 - `$ pipenv --python 3.7`
 - `$ pipenv install`
 - `$ pipenv install --dev`
 