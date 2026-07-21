# 汎用ブラウザツール置き場

ブラウザだけで動く軽量ツールを集めたリポジトリ。外部ライブラリ・ビルド不要、HTML1枚で完結。

## 🛠 ツール一覧

| ツール | 概要 | 起動 |
|---|---|---|
| **キー入力イベントチェッカー** (`keyInputTest.html`) | キーボード・マウス・ホイール・ゲームパッド等の入力イベントを可視化・記録 | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/keyInputTest.html) |
| **テキストエンコード/デコード** (`textCodecTool.html`) | URLエンコード・Base64・Hex・コードポイントへ一括変換(UTF-8/Shift_JIS両対応)・自動判定デコード・文字インスペクタ・文字化けの再現と修復・ファイルの文字コード変換 | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/textCodecTool.html) |
| **単位変換ツール** (`unitConverter.html`) | inch⇔cm等の長さ・重さ(ポンド)・面積(坪/畳)・容量・温度・速度をリアルタイム連動変換。cm/inch対比ものさし・ディスプレイのインチ実寸図(比較機能付き)・電線の太さ(AWG⇔mm)も | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/unitConverter.html) |
| **人生の現在地** (`lifeRemaining.html`) | 生年月日から「食事・睡眠・散髪があと何回できるか」と残り時間をリアルタイム表示。学校・元号・ゲーム機/アーケード/ゲームソフト/漫画/IT史を重ねられる人生年表(学年表記・マイイベント追加対応)、大切な人とあと何回会えるか計算も | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/lifeRemaining.html) |
| **BLE心拍モニター** (`heartRateMonitor.html`) | BLE心拍センサーに接続して、リアルタイム表示、外部ウィンドウで簡易表示もできます。 | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/heartRateMonitor.html) |

### ⚡ 電子工作系

| ツール | 概要 | 起動 |
|---|---|---|
| **オームの法則：抵抗アニメーション** (`ohmGuide.html`) | V/I/Rの計算機・電流の流れアニメ(ショート時は爆発)・直列/並列/分圧回路・抵抗の定格(W)チェック | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/ohmGuide.html) |
| **ダイオード早見表** (`diodeGuide.html`) | ダイオードの種類・用途・入手しやすい型番・違いをまとめた早見表。LED抵抗値計算機・ESP32向け項目・用語解説つき | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/diodeGuide.html) |
| **理想ダイオードのしくみと使い方** (`idealDiodeGuide.html`) | 順/逆アニメ・実物との損失比較・MOSFET実装・専用IC(CH213K/XC8111)・ORing/電池バックアップ・ホットスワップとの違い | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/idealDiodeGuide.html) |
| **トランジスタ(BJT)の使い方** (`bjtGuide.html`) | 電流増幅・動作領域(遮断/活性/飽和)のアニメ・型番プリセット付きベース抵抗計算機(アニメ連動)・基本回路・定番型番・トラブルシューティング | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/bjtGuide.html) |
| **MOSFETの使い方** (`mosfetGuide.html`) | MOSFETの端子・N/P-ch・ロー/ハイサイド・省電力化・発熱計算機・ESP32向け注意点・トラブルシューティング | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/mosfetGuide.html) |
| **NE555タイマー早見表** (`ne555Guide.html`) | NE555の仕様・ピン配置・内部構造・3つの動作モード(非安定/単安定/双安定)・コンパレータ用途・周波数/時間の計算機(逆算・プリセット付き) | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/ne555Guide.html) |
| **LEDチカチカ回路** (`ledBlinkGuide.html`) | マルチバイブレータの作り方(トランジスタ/MOSFET/555/74HC14)・ホタル点滅・LEDチェイサー・点滅頻度の計算機(プリセット・早見表付き) | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/ledBlinkGuide.html) |
| **NFC 13.56MHz コイル共振計算機** (`nfcCoilCalc.html`) | NFCで電池レスLEDを光らせるLC共振タグの設計用。コイル直径・巻き数・線径・コンデンサから共振周波数をリアルタイム計算、13.56MHz一致判定・逆算C・定番レシピ・作り方ガイドつき | [起動](https://htmlpreview.github.io/?https://github.com/unyoooo/misc/blob/master/nfcCoilCalc.html) |

---

## ライセンス

MIT  
@unyoooo