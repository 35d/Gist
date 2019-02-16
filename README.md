## サブモジュール追加

`git submodule add [GistのURL] [好きなディレクトリ名]`

submodule をアップデートした場合は、
```
git submodule foreach git pull origin master
```
でサブモジュールを最新のものにアップデートし、親(このリポジトリ)に変更をpushすれば良い。
