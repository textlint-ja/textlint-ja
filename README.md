# textlint-ja

[textlint](http://textlint.github.io/ "textlint")の日本語コミュニティ

textlintの日本語関係のルールのリポジトリを置いたり、ルールの作り方やこういう事をチェックしたいという話を扱う場所です。

## Gitter

Gitterに自由にチャットできるチャンネルがあります。
日本語で問題ないので、気軽に書き込んでください。

[![Join the chat at https://gitter.im/textlint-ja/textlint-ja](https://badges.gitter.im/textlint-ja/textlint-ja.svg)](https://gitter.im/textlint-ja/textlint-ja)

## リポジトリをこのOrganizationへ置きたい

リポジトリの設定から"Transfer"をしてください。

- [GitHubのリポジトリを別のOwnerに引き渡す - Qiita](http://qiita.com/do7be/items/fa845240bc58b2153a44 "GitHubのリポジトリを別のOwnerに引き渡す - Qiita")

その時に、Organizationの権限がある人がAcceptする必要があるので[New Issue](https://github.com/textlint-ja/textlint-ja/issues/new)からIssueを立てるか、
[Gitter](https://gitter.im/textlint-ja/textlint-ja)に書き込んでください。

Transfer後は以下のように手順でREADME.mdなどの書き換えを行ってください。

- [GitHubで個人リポジトリからOrganizationリポジトリにしてやったこと一覧 - Qiita](http://qiita.com/yu1ro/items/5da82882647b4c400559 "GitHubで個人リポジトリからOrganizationリポジトリにしてやったこと一覧 - Qiita")

また、[transfer-github-owner](https://github.com/azu/transfer-github-owner "transfer-github-owner")を使うことで、READMEやpackage.jsonの書き換えを半自動で行う事ができます。

```js
npm install -g transfer-github-owner
transfer-github-owner --from <your-name> --to textlint-ja
```
