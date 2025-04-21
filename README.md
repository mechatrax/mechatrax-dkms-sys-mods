#  mechatrax-dkms-sys-mods
armhf 環境で dkms を使用する際に必要な設定を行います。

## 提供ファイル
次のファイルがパッケージに含まれています。

### /usr/share/doc/mechatrax-dkms-sysmods/changelog.gz
パッケージの変更履歴を記録したファイルです。

### /usr/share/doc/mechatrax-dkms-sysmods/copyright
著作権とライセンスを記載したファイルです。

## 設定
インストール時に次のファイルが変更されます。

### /boot/firmware/config.txt
次のエントリが追記されます。
```
arm_64bit=0
```
