## クローン
`git clone --recursive https://github.com/35d/Gist.git`

## サブモジュール追加
`git submodule add [GistのURL] [好きなディレクトリ名]`

## 別 PC で PULL
`git pull -f`

`git submodule update --init --recursive`

## submodule をアップデートした場合
`git submodule foreach git pull origin master`  
サブモジュールを最新のものにアップデートし、親(このリポジトリ)に変更を push すれば良い。
