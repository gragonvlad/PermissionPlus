PermissionPlus
==============

PermissionPlusはPMMP専用のプラグインです。
Omattyao氏が作成したプラグインを1.4向けに移植しました。
Omattyao氏のブログから引用：
プレイヤーにそれぞれGUEST, TRUST, ADMINの権限を割り当てる事によって、権限毎に使えるコマンドを制限できるプラグイン

プレイヤーに権限を割り当てたい時は
```
/ppplayer [プレイヤー名] [権限]
```
をコンソールか看板から実行してください。
例えば「/ppplayer Omattyao admin」でOmattyaoにAdmin権限を付与する事ができます。[権限]の部分はGuest, Trust, Admin(それぞれg, t, aでもOK)のどれかが入ります。
権限を持っていないプレイヤーには自動的にGuestを割り当てます。

権限の設定は保存され次回以降の起動時にも反映されます。現在の権限の設定を確認したい時は
```
/ppplayer
```
をコンソールから実行してください。

プレイヤーに権限を割り当てたい時は
```
/ppplayer [プレイヤー名] [権限]
```
をコンソールか看板から実行してください。
例えば「/ppplayer Omattyao admin」でOmattyaoにAdmin権限を付与する事ができます。[権限]の部分はGuest, Trust, Admin(それぞれg, t, aでもOK)のどれかが入ります。
権限を持っていないプレイヤーには自動的にGuestを割り当てます。

権限の設定は保存され次回以降の起動時にも反映されます。現在の権限の設定を確認したい時は
```
/ppplayer
```
をコンソールから実行してください。

更新履歴
* 1.0.0
    * リリース

* 1.0.1
    * プレイヤーがワールドに居ないときに/ppplayerを使うとサーバがクラッシュするバグの修正

* 1.0.2
    * 不具合修正

* 1.0.3
    * 1.3.xをサポート

* 1.0.4
    * ppcommandを追加

* 1.0.5
* 1.0.6
* 1.0.7
    * 他のプラグインからのコマンドを拒否（このコードを無効化：$this->api->console->run("ppplayer steve admin", "console");)
    * 不具合修正

* 1.0.8
    * configに新しいコマンドを追加

* 1.0.9
    * 不明

//Omattyao氏のリリースここまで
<br><hr><br>
//Hmy2001氏のリリースここから
* テストバージョン
    * 一部の鯖主のみ公開
* 1.1.0
    * テストバージョンでの不具合修正
    * 移植版リリース(一般公開)

* 1.2.0
    * コマンドパーミッション関連の修正

* 1.3.0
    * コマンドパーミッションでもコマンド規制実装
    * aliasコマンドも規制実装
    * コマンドパーミッション関連修正
    * command.ymlを最新コマンド一覧に差し替え

* 1.3.1
    * aliasの規制が初期化されない不具合修正
    * インポート対応<br>(1.3版のパーミッションプラス設定ファイルに対応。バージョンが古いと、インポートできません。)
    * コンソール上による権限表示に対するエラーの修正
    * バグ報告などがなければこれが最後のバージョンです。

* 1.4.0
    * 最適化
    * 権限を削除した場合その権限になっていたプレイヤーはゲストへ変更するように。
    * 前のconfigフォーマット形式に戻した
    * githubへのソース掲載

* 1.4.1
* 1.4.2
* 1.4.3
    * 不具合修正

* 1.4.4
    * ソースコード整理(rain318さん)
    * ppcmdした後PernameがoffにもかかわらずsetNameをする不具合修正
    * 大幅に翻訳(設定により選択することが可能&一部翻訳はしていません)

* 1.5.0
    * コードの最適化
    * PocketMine-MP-1.5に対応

* 1.5.1
    * プレイヤーに権限を設定する処理を改善

* 1.5.2
    * 正しく動作しない不具合を修正

* 1.5.3
* 1.5.4
    * php7環境でエラーを吐く不具合を修正

* 1.5.5
    * 最新のGenisysの場合に、コマンドリストを更新するように

* 1.5.6
    * コマンドリスト更新機能削除、APIを更新

* 1.5.7
    * APIを更新

Omattyao氏ThankYou!