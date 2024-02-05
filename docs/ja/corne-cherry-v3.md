# PCB 準備 for Corne cherry v3

## 組み立てに必要なもの

| 名称                                                | 個数              |
| --------------------------------------------------- | ----------------- |
| Corne cherry v3 PCB                                 | 1 セット (左右分) |
| 表面実装ダイオード ( 1N4148W )                      | 42 個             |
| MX 用 PCB ソケット                                  | 42 個             |
| TRRS ジャック ( PJ-320A )                           | 2 個              |
| OLED 128x32                                         | 2 個              |
| 対応してる MCU                                      | 2 個              |
| MCU 用コンスルーピンまたはピンソケット (高さ 2.5mm) | 4 個              |
| リセットスイッチ用タクトスイッチ (2 ピン )          | 2 個              |

---

以下は必要ですが, Corchim に同梱されています

| 名称                | 個数 |
| ------------------- | ---- |
| OLED 用ピンソケット | 2 個 |
| OLED 用ピンヘッダ   | 2 個 |

### 余談 kailh MX 用ソケットの色について

某所で質問されたので答えておくと、色はなんでも問題ありません。ファッションです ( ケースつけると見えないので特に意味はないかもですけど )。購入先としては

- https://shop.dailycraft.jp/products/keyswitch_socket_transparent
- https://chosfox.com/products/kailh-colorful-hot-swap-socket
- https://ja.aliexpress.com/item/1005003174680450.html

このあたりです。

### compatible MCU

- Elite-C
- Elite-Pi
- key micro

(各種ファームウェアの焼き方は現在 WIP なので近日中にビルドガイドを更新します)

### MCU 用のピンソケット (コンスルーピン) について

USB-C の差込口の関係で, 高さ 2.5mm を推奨としいます。
