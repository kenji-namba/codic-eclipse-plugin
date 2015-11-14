# Codic Eclipse Plugin

[codic](https://codic.jp/)のネーミング生成をEclipseから使うプラグインです。利用するには、codicのアカウントが必要です。

##インストール
1. Eclipseを起動し、メニューの"ヘルプ" >> "新規ソフトウェアのインストール" で、以下のアップデートサイトからインストールします。

  `http://kenji-namba.github.io/codic-eclipse-plugin/updates`
  
2. プロジェクトのプロパティを開き、"codic" タブより、アクセストークンを設定し、ネーミングに使うプロジェクト辞書を選択します。アクセストークンは、[codic](https://codic.jp/)にログイン後、APIステータスのページより取得できます。

## スクリーンショット
![codic eclipse plugin](https://codic.jp/external/github/eclipse_plugins.png)

## 使い方
1. 任意のエディタ上で Ctrl+D （または右クリック「codic」「クイックルック」）でネーミング生成します。
2. 日本語で検索するとネーミング生成、英語で検索すると英和（Codic English Dictionary) 検索します。
4. フィードバックには対応していません。Webから行ってください。

## 注意事項
- このプラグインは、[codic API](https://codic.jp/docs/api)を使っているため、一定時間内のアクセス回数に制限があります。制限を超えたら、APIステータスのページでリセットしてください。

## Change log

#### 1.0.1
- ケースオプションにハイフネーションを追加しました。

### その他
バグなどがありましたら、[Issue](https://github.com/kenji-namba/codic-eclipse-plugin/issues)へ登録してください。
