# Vipelar Quake-Info

Vipelar Quake-Info は、APIから取得した地震データを表示するウェブアプリケーションです。現在のバージョンでは、地震の発生日時、震源の深さ、マグニチュード、最大震度のデータを提供します。

## 特徴

- 自動的に（1 秒ごと）地震データを取得して表示します。
- 自動更新が止まった際など、ユーザーが地震データを手動で更新することもできます。

## 使い方

1. [Vipelar Quake-Info](https://vipelar-team.web.app/quake-info/index.html) にアクセスする。
2. 地震情報が表示されます。
3. 万が一自動更新が止まっても、地震データは手動で更新することができます。「手動更新」ボタンをクリックしてください。
4. 地震情報をご覧ください。なお、上位APIの仕様等で、表示されるデータは最新ではない可能性がありますのでご注意ください。

## 技術情報

- 地震データは [nTool Earthquake API](https://ntool.online/apidoc/earthquakeapi) から取得しています。
- エラーメッセージの表示には [SweetAlert2](https://sweetalert2.github.io/) を使用しています。
- フォントは [BIZ UDPGothic](https://fonts.google.com/specimen/BIZ%2BUDPGothic) を使用しています。
- リンク等で使用しているアイコンには [FontAwesome](https://fontawesome.com) を使用しています。
- データの取得に ajax を使用しています。詳細は [こちら](https://developer.mozilla.org/ja/docs/Web/Guide/AJAX) 。
- その他様々な処理に [jQuery](https://jquery.com/) を使用しています。
- HTML、CSS、JavaScript を使用して公開されています。

## 免責事項

このアプリケーションは地震データの提供を目的としていますが、データの正確性や完全性については保証できません。また、情報の更新が遅くなる可能性があります。正確で素早い地震情報の確認や被害状況の把握には、気象庁等の政府機関や、信頼できる関連機関が提供する情報を利用してください。なお、開発者はこのアプリを使用したことによるいかなる損害も負わないものとします。

## ライセンス

このプロジェクトは MIT ライセンスのもとで公開されています。詳細については [LICENSE](LICENSE) ファイルを参照してください。

## その他

LICENSE ファイルの正式版は英語、この README ファイルの正式版は日本語とし、それ以外の言語では効力を持たないものとします。

Copyright &copy; 2023 Vipelar. All rights Reserved.