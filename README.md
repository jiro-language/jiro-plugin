# Jiro Plugin

二郎言語をIntelliJで使用する際に、Syntax Highlight、補完が出来るようになります。

## Import
`File > Import Settings...`を選択し、`jiro-plugin.jar`をimportします。  
`Preferences`で`Colors & Fonts`、`Live Template`、`File Types`に二郎っぽいファイルが追加されていることが確認できたら、完了です。  
（`jiro-plugin.jar`以外のファイルは個々の設定ファイルです。全部入れたくなければそれを使ってくださいな。）

## Example
`switch`or`ニンニク入れますか？`or`ninnikuiremasuka`を入力すると、以下が出力されるようになります。
```
ニンニク入れますか？ (var) {
  ニンニク value1:
  ヤサイ value2:
  アブラ value3:
  カラメ value4:
  そのままで:
}
```
