# Change Log

## [Unreleased](https://github.com/sakura-editor/sakura/tree/HEAD)

[Full Changelog](https://github.com/sakura-editor/sakura/compare/v2.3.2.0...HEAD)

**Implemented enhancements:**

- ファイルの場所を管理者としてコマンドプロンプトを開く、に対応する [\#608](https://github.com/sakura-editor/sakura/issues/608)
- 「エクスプローラーで開く」、「コマンドプロンプトを開く」等のコマンドのアイコンを対応する [\#607](https://github.com/sakura-editor/sakura/issues/607)
- `ファイルの場所をコマンドプロンプトで開く`、および、`ファイルの場所をPowerShellで開く` を検討する [\#556](https://github.com/sakura-editor/sakura/issues/556)
- Windows Imaging Component を使って背景画像を読み込み、透過描画対応 [\#683](https://github.com/sakura-editor/sakura/pull/683) ([beru](https://github.com/beru))
- コマンドアイコンの追加 [\#680](https://github.com/sakura-editor/sakura/pull/680) ([berryzplus](https://github.com/berryzplus))
- 「ファイルのプロパティ」ダイアログのエディットコントロールにTabStopを付ける [\#670](https://github.com/sakura-editor/sakura/pull/670) ([beru](https://github.com/beru))
- `ファイルの場所を powershell で開く` に対応する [\#623](https://github.com/sakura-editor/sakura/pull/623) ([m-tmatma](https://github.com/m-tmatma))
- 管理者としてコマンドプロンプトを開くメニュー項目を追加 [\#618](https://github.com/sakura-editor/sakura/pull/618) ([m-tmatma](https://github.com/m-tmatma))
- コマンドプロンプトを開くためのメニューを実装 [\#603](https://github.com/sakura-editor/sakura/pull/603) ([m-tmatma](https://github.com/m-tmatma))
- 「ファイルの場所をエクスプローラーで開く」追加 [\#549](https://github.com/sakura-editor/sakura/pull/549) ([berryzplus](https://github.com/berryzplus))
- ターゲットwindowsをwindows7に上げる [\#548](https://github.com/sakura-editor/sakura/pull/548) ([berryzplus](https://github.com/berryzplus))
- ツールバーの表示ON/OFFを行うとちらつく現象への対策 [\#533](https://github.com/sakura-editor/sakura/pull/533) ([beru](https://github.com/beru))

**Fixed bugs:**

- Alt+F1 \(ヘルプ\) するとサクラエディタが落ちる [\#643](https://github.com/sakura-editor/sakura/issues/643)
- 通常のソリューションのコンパイル前に tests\build-and-test.bat でビルドするとコンパイルエラーになる [\#561](https://github.com/sakura-editor/sakura/issues/561)
- マウスクリックによるキャレット移動が出来なくなる [\#547](https://github.com/sakura-editor/sakura/issues/547)
- Texのファイルで落ちます。 [\#539](https://github.com/sakura-editor/sakura/issues/539)
- マウスクリックによるキャレット移動が出来なくなる不具合の解消 [\#574](https://github.com/sakura-editor/sakura/pull/574) ([beru](https://github.com/beru))
- Fix \#539 「Texのファイルで落ちます。」 [\#553](https://github.com/sakura-editor/sakura/pull/553) ([ds14050](https://github.com/ds14050))
- 英語windowsでメッセージがおかしい件に対処する [\#534](https://github.com/sakura-editor/sakura/pull/534) ([berryzplus](https://github.com/berryzplus))

**Closed issues:**

- 「ファイルのプロパティ」ダイアログのエディットコントロールにTabStopを付ける [\#667](https://github.com/sakura-editor/sakura/issues/667)
- キーワードヘルプのフォントが Yu Gothic UI 72pt の時にポップアップ表示の文字が欠けて表示される [\#639](https://github.com/sakura-editor/sakura/issues/639)
- HTML ヘルプ中に記載のあるビルドに必要なものが古い [\#598](https://github.com/sakura-editor/sakura/issues/598)
- tmpファイルがいっぱいあるのですが・・・ [\#589](https://github.com/sakura-editor/sakura/issues/589)
- `if %ERROR\_RESULT% neq 0` を `if errorlevel 1` にするか検討する [\#586](https://github.com/sakura-editor/sakura/issues/586)
- 「バージョン情報」のURL部分にマウスカーソルを持っていったときの背景色が長い [\#563](https://github.com/sakura-editor/sakura/issues/563)
- インストーラで拡張子の関連づけをするか検討する [\#562](https://github.com/sakura-editor/sakura/issues/562)
- 開く\(ドロップダウンメニュー\)に「履歴の管理」を追加して欲しい [\#550](https://github.com/sakura-editor/sakura/issues/550)
- アウトライン解析の「更新」のアイコンが「Windows」マークなのは直感的じゃないので変えて欲しい [\#543](https://github.com/sakura-editor/sakura/issues/543)
- appveyorビルドがpythonのエラーで失敗してしまう [\#541](https://github.com/sakura-editor/sakura/issues/541)
- doxygen コメントの @file に関して [\#532](https://github.com/sakura-editor/sakura/issues/532)

**Merged pull requests:**

- 「このファイルのパス名をコピー」 をタブメニューにも追加する [\#666](https://github.com/sakura-editor/sakura/pull/666) ([m-tmatma](https://github.com/m-tmatma))
- 縦スクロール時に不必要にルーラーの再描画がされないように対策 [\#660](https://github.com/sakura-editor/sakura/pull/660) ([beru](https://github.com/beru))
- スクロールバーの再描画を常には行わないように変更 [\#657](https://github.com/sakura-editor/sakura/pull/657) ([beru](https://github.com/beru))
- 辞書Tipの描画改善、およびHighDPI対応 [\#647](https://github.com/sakura-editor/sakura/pull/647) ([berryzplus](https://github.com/berryzplus))
- フォントラベルのHighDPI対応 [\#645](https://github.com/sakura-editor/sakura/pull/645) ([berryzplus](https://github.com/berryzplus))
- 関数ポインタの値ではなくてアドレスをテーブルに登録するように修正 [\#644](https://github.com/sakura-editor/sakura/pull/644) ([beru](https://github.com/beru))
- 分割線ウィンドウクラスの処理で使用している各数値をDPI設定に応じて調整 [\#641](https://github.com/sakura-editor/sakura/pull/641) ([beru](https://github.com/beru))
- 独自拡張プロパティシートの「設定フォルダ」ボタンの位置調整処理でDPIを考慮 [\#638](https://github.com/sakura-editor/sakura/pull/638) ([beru](https://github.com/beru))
- googletest を更新 [\#636](https://github.com/sakura-editor/sakura/pull/636) ([m-tmatma](https://github.com/m-tmatma))
- `ファイルの場所を コマンドプロンプトを開く` で 管理者ではないときに 32bit アプリから 64bit OS上で起動したときに 32bit で起動してしまうのを修正 [\#627](https://github.com/sakura-editor/sakura/pull/627) ([m-tmatma](https://github.com/m-tmatma))
- 設定データ読み込み処理において言語設定切り替え後にMRUエントリが無い場合は新規インストール後とみなし false を返すように変更 [\#620](https://github.com/sakura-editor/sakura/pull/620) ([beru](https://github.com/beru))
- reST 用の拡張子 \(.rst\) を関連付け用の設定に追加 [\#612](https://github.com/sakura-editor/sakura/pull/612) ([m-tmatma](https://github.com/m-tmatma))
- PR \#599 の不備を修正 [\#609](https://github.com/sakura-editor/sakura/pull/609) ([m-tmatma](https://github.com/m-tmatma))
- HTML Help でビルド方法に関する説明で build.md を参照するように変更 [\#606](https://github.com/sakura-editor/sakura/pull/606) ([m-tmatma](https://github.com/m-tmatma))
- HTML Help で ビルドに必要な条件を更新 [\#605](https://github.com/sakura-editor/sakura/pull/605) ([m-tmatma](https://github.com/m-tmatma))
- Windows 10 でユーザーが手動でサクラエディタに対して関連付けを行えるようにする \(part2\) [\#602](https://github.com/sakura-editor/sakura/pull/602) ([m-tmatma](https://github.com/m-tmatma))
- Windows 10 でのファイルの関連付けに関する説明を HTML Help に追加 [\#599](https://github.com/sakura-editor/sakura/pull/599) ([m-tmatma](https://github.com/m-tmatma))
- Windows 10 でユーザーが手動でサクラエディタに対して関連付けを行えるようにする [\#596](https://github.com/sakura-editor/sakura/pull/596) ([m-tmatma](https://github.com/m-tmatma))
- テストコードで\_swprintf\_pの利用をやめる [\#593](https://github.com/sakura-editor/sakura/pull/593) ([berryzplus](https://github.com/berryzplus))
- Build and run tests on MinGW environment. [\#591](https://github.com/sakura-editor/sakura/pull/591) ([ds14050](https://github.com/ds14050))
- URLリンクの改善 [\#566](https://github.com/sakura-editor/sakura/pull/566) ([berryzplus](https://github.com/berryzplus))
- doxygen の設定ファイルと実行用のバッチファイルを追加 [\#565](https://github.com/sakura-editor/sakura/pull/565) ([m-tmatma](https://github.com/m-tmatma))
- MinGWビルドのエラーに対処する [\#559](https://github.com/sakura-editor/sakura/pull/559) ([berryzplus](https://github.com/berryzplus))
- アウトライン解析の更新アイコンを変更する [\#558](https://github.com/sakura-editor/sakura/pull/558) ([berryzplus](https://github.com/berryzplus))
- sakura.hhの参照を変更 [\#555](https://github.com/sakura-editor/sakura/pull/555) ([berryzplus](https://github.com/berryzplus))
- Fix \#509 「Ctrl+左ボタンダウンからの左ボタンドラッグによる単語選択がちょっとおかしい」 [\#552](https://github.com/sakura-editor/sakura/pull/552) ([ds14050](https://github.com/ds14050))
- ドロップダウンメニューに履歴の管理を追加 [\#551](https://github.com/sakura-editor/sakura/pull/551) ([berryzplus](https://github.com/berryzplus))
- doxygen コメントの @file をつける [\#535](https://github.com/sakura-editor/sakura/pull/535) ([m-tmatma](https://github.com/m-tmatma))

## [v2.3.2.0](https://github.com/sakura-editor/sakura/tree/v2.3.2.0) (2017-05-02)
[Full Changelog](https://github.com/sakura-editor/sakura/compare/v2.3.1.0...v2.3.2.0)

## [v2.3.1.0](https://github.com/sakura-editor/sakura/tree/v2.3.1.0) (2016-08-13)
[Full Changelog](https://github.com/sakura-editor/sakura/compare/v2.3.0.0...v2.3.1.0)

## [v2.3.0.0](https://github.com/sakura-editor/sakura/tree/v2.3.0.0) (2015-10-12)
[Full Changelog](https://github.com/sakura-editor/sakura/compare/v2.2.0.1...v2.3.0.0)

## [v2.2.0.1](https://github.com/sakura-editor/sakura/tree/v2.2.0.1) (2015-03-01)
[Full Changelog](https://github.com/sakura-editor/sakura/compare/v2.2.0.0...v2.2.0.1)

## [v2.2.0.0](https://github.com/sakura-editor/sakura/tree/v2.2.0.0) (2015-02-22)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*