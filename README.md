<div style="display:flex">
    <img src="assets/inari-icon.svg" width="64">
    <div style="margin-left: 10px">
        <h2 style="display:inline">稻荷 / inari-shiori</h2><br>
        しおりをつくってみようプロジェクト
    </div>
</div>

## これはなに？
伺かゴースト用の SHIORI「稻荷」の開発プロジェクトです。

## ためしてみる
ReleaseのところからデモゴーストやSHIORI本体のdllをダウンロードできます。
VSCode向けのちょっとした拡張機能もあります。

[wikiページ](https://github.com/komoli868aiu-eo/inari-shiori/wiki)に仕様を書き出したガイドなどもありますので、興味があれば見てみてください。

## 利用規約など
配布している inari.dll は伺かゴースト向けのSHIORI・SAORIとして自由に使用・配布いただけます。
ソースファイルのライセンスはまだ定めていないので、個別に許可した場合を除いては個人利用や本プロジェクト参加のための使用にとどめてください。
このプログラムは無保証です。このプログラムによって発生した現象について作者は責任を負いません。

## ビルドにかんして
* リポジトリ内のゴースト(/ssp/*)を起動する場合
  * inari.dll のビルドが必要
* vscode拡張(/vscode-extension/*)をビルドする場合
  * inari-sstp.exe のビルドが必要

inari-shiori.slnをビルドしてください。  
ビルド生成物として、それぞれに必要なファイルが配置されます。
