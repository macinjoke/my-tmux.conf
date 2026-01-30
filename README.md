# my-tmux.conf
自分用のtmux.conf

# SETUP

clone this repository, then run `migrate.sh`

# git-crypt テスト

全くこのリポジトリに関係ないが、git-cryptの動作確認できるようにしている。

```shell
git-crypt lock  # ロックする
git-crypt unlock .git-crypt-shared-secret.key  # アンロックする
```

メモ: lock時、 .git/git-crypt/keys/default にあるキーは消える

