# BP_clear_widgets
## 対象バージョン
UE5以降(delay until next tickを使用しています)
## 説明
マクロです。actor等のblueprintから呼ぶことを想定しています。基盤クラスはactorです。
## セットアップ
contentフォルダーに入れてください。
## 内容物
二つのマクロが含まれています
### widgets clear of memory
![Desktop Screenshot 2023 08 05 - 02 25 45 73](https://github.com/aoharudesu/BP_clear_widgets/assets/97249122/653790c0-28c4-49ef-9f89-3e21e300028f) <br>
引数にuser widgetクラスの参照を取ります。remove系の関数で非表示になっているがメモリ上にはあるwidgetsをクリアします
### check widgets
![Desktop Screenshot 2023 08 05 - 02 25 45 732](https://github.com/aoharudesu/BP_clear_widgets/assets/97249122/02ce7863-df6b-43c3-959f-34c5ff01b00d) <br>
引数にuser widgetクラスの参照を取ります。表示します。
