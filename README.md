# AC (AtCoder) ライブラリ

AC Library は、[AtCoder](https://atcoder.jp/home) の公式ライブラリです。このリポジトリでは、AC Library の内容を管理しています。

詳細については、以下のリンクをご参照ください。

- [AtCoder での発表](https://atcoder.jp/posts/518)
- [Codeforces での発表](https://codeforces.com/blog/entry/82400)
- [練習コンテスト](https://atcoder.jp/contests/practice2)
- [AC Library ドキュメント (英語)](https://atcoder.github.io/ac-library/production/document_en/)
- [AC Library ドキュメント (日本語)](https://atcoder.github.io/ac-library/production/document_ja/)

master ブランチのドキュメントは以下のとおりです。

- [AC Library ドキュメント (英語, master)](https://atcoder.github.io/ac-library/master/document_en/)
- [AC Library ドキュメント (日本語, master)](https://atcoder.github.io/ac-library/master/document_ja/)

## 方針

このプロジェクトの目標は、次のとおりです。

- **すべての AtCoder ユーザー** が **PC の学習を最小限に抑えて** このライブラリを使用できるようにする
- **競技プログラミングでの使用** に最大限の利便性を提供する。他の用途は完全に無視します。
- バグがない。これは幻想ですが、私たちはこれを追求しています。

この方針により、C++ のいくつかの作法を意図的に無視しています。例えば、

- `size_t` は使用せず、`int` を使用します。
- Segtree は、関数オブジェクトではなく、関数ポインタを扱います。
- など...

## このプロジェクトの今後

このライブラリのコンテンツを増やすかどうかについては、賛否両論あるため、まだ決定していません。
このトピックにご興味のある方は、[Codeforces での発表](https://codeforces.com/blog/entry/82400) で議論にご参加ください。

今のところ、新機能の追加は予定しておらず、このリポジトリは次の目的でのみ使用します。

- 問題の収集
- 変更履歴の記録
- リリースのバージョン管理

## 貢献

問題/PR は **AtCoder ユーザーからのみ** 受け付けています。

タイプミスのような間違いや、さらに重要なバグを報告していただけると幸いです。

上記のように、私たちはまだどちらの方向に進むか決めていません。そのため、今のところ機能リクエストは受け付けておらず、問題はクローズされます。

## リリース

AC Library の最新バージョンは、[AtCoder での発表](https://atcoder.jp/posts/518) ページでご覧いただけます。

また、すべてのバージョンは [リリース](https://github.com/atcoder/ac-library/releases) ページでご覧いただけます。

## ライセンス

このライブラリは、`/document_(en|ja)/lib` ディレクトリにあるサードパーティライブラリを除き、[CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode) でリリースされています。詳細については、[/document_en/lib/LICENSE.md](./document_en/lib/LICENSE.md) を参照してください。
