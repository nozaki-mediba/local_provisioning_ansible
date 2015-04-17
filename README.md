# local_provisioning_ansible
ローカルの環境をansibleで管理する


# 概要
自身のMacの環境をansibleを使って管理する。

環境は下記のもの。
```
% sw_vers
ProductName:	Mac OS X
ProductVersion:	10.9.5
BuildVersion:	13F34
```

# 使い方

## 開発環境用

```
% sudo ansible-playbook -i hosts -v dev-setting.yml
```

## プログラム言語用

```
% sudo ansible-playbook -i hosts -v dev-language.yml
```


## ミドルウェア用
```
% sudo ansible-playbook -i hosts -v dev-middleware.yml
```


## その他（ユーティリティ）


# アプリケーション検索
## brew 
```
% brew search
% brew search <word>
```

## brew cask
```
% brew cask search
% brew cask search <word>
```


# 参考

http://mawatari.jp/archives/mac-provisioning-by-homebrew-and-ansible
http://qiita.com/ryurock/items/1432578d364985f6cb06
