# stack-chan-tester-SCS0009
Takao Akakiさんの https://github.com/mongonta0716/stack-chan-tester をマイクロSDカードを使わなくて済むように(=市価1000円程度をケチって)内蔵flashメモリ(LittleFS)に変更したものです。

ここでは設定ファイルの各種パラメーターはCORE2+SCS-0009が前提です。これ以外の組み合わせではテストしていません。
必要に応じて/data/yaml/SC_BasicConfig.yamlなどを書き換えてみてください。

/data/yaml/SC_BasicConfig.yamlファイルはPlatformIOの"PROJECT TASKS"メニュー配下の"Upload Filesystem Image"などからｽﾀｯｸﾁｬﾝ本体のflashメモリに転送してください。

オリジナルにあった、ボタンC長押しによるパラメータ保存機能は削除しています。

Takao AkakiさんオリジナルのREADMEは [README.org.md](https://github.com/osamusg/stack-chan-tester-scs0009/blob/main/README.org.md) を参照してください。

# Acknowledgements
Takao Akaki https://github.com/mongonta0716
ししかわ https://protopedia.net/prototyper/meganetaaan

# Author of the this revised edition
@sasurai_osamu

# Lisence
Following original edition, MIT