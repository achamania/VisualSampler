VisualSampler v1.0.1 FREE
for SP-404MK2
============================================================

Sample Your City. Remix Your Reality.

【1. VisualSamplerとは】

VisualSamplerは、Roland SP-404MKIIを使って静止画像を演奏する、
macOS向けのビジュアルサンプラーです。

音楽をサンプリングするように、街の風景や日常の写真をサンプリング。
16個のPADを使って画像を切り替え、リアルタイムの映像表現を楽しめます。

好きな写真を入れて、PADを叩くだけ。
あなたの日常を、映像のサンプルに。

【2. 動作環境】

・対応OS：macOS（同梱ランタイムの最低要件は11.0。OS別の動作保証は未完了）
・対応Mac：Apple Silicon搭載Mac（Mシリーズ）
・コントローラー：Roland SP-404MKII
・接続：USB MIDI
・Processingをベースに制作
・配布アプリにはJavaランタイムを同梱（通常は別途インストール不要）

※本配布版はApple Silicon搭載Mac専用です。Intel MacおよびWindowsには対応していません。

【3. アプリの配置と起動】

1. 配布ZIPを解凍します。
2. SP-404MKIIをUSBでMacに接続し、電源を入れます。
3. SP-404MKIIのMIDI設定を確認します（下記参照）。
4. VisualSampler.appを起動します。
5. SP-404MKIIのPADを押して画像を切り替えます。

SP-404MKIIの必須MIDI設定：
  SHIFT + PAD 13（UTILITY）→ SYSTEM → MIDI
  ・MIDI Mode：A
  ・PAD Note Out：ON

※この2項目はVisualSamplerの操作に必須です。
  MIDI ModeがBの場合、PADのMIDIノート／チャンネル割り当てが
  VisualSamplerの想定と異なり、正常に操作できません。
  PAD Note OutがOFFの場合、PAD操作のMIDI信号が送信されません。
※MIDI EXT Src（TOGGLE / GATE / THROUGH）は、VisualSamplerの
  操作において特定の設定を必須としていません。

Banksフォルダは、VisualSampler.appと同じ階層に置くと分かりやすくなります。
起動時にBanksの場所を聞かれた場合は、BankAとBankBを含む親の「Banks」を選びます。
選んだ場所は保存され、次回以降の起動にも使われます。
保存した場所が見つからなくなった場合は、再び選択画面が表示されます。
キャンセルや選択間違いの後は、アプリ画面でRキーを押して選び直せます。
Banks/BankAとBanks/BankBには、それぞれ01〜16の画像を揃えてください。

正しい配置例：

VisualSampler_v1.0.1_macOS_AppleSilicon/
├── VisualSampler.app
├── Banks/
│   ├── BankA/
│   │   ├── 01.jpg
│   │   ├── 02.jpg
│   │   └── ... 16.jpg
│   └── BankB/
│       ├── 01.jpg
│       ├── 02.jpg
│       └── ... 16.jpg
├── README_JP.txt
├── README_EN.txt
├── README_ES.txt
├── README_ZH_CN.txt
└── README_KO.txt

※フォルダ名は「Banks」「BankA」「BankB」です。
  「BANK_A」「BANK_B」などに変更しないでください。
※Banksを.appの内部に移動しないでください。

【初回起動：プライバシーとセキュリティ】

本配布版はDeveloper ID署名・Appleの公証を受けていません。
そのため、初回起動時にAppleが安全性を検証できない旨の警告が出ることがあります。
以下は、入手元を信頼でき、ファイルが改ざんされていないと確認した場合の手順です。

1. ZIPを展開し、VisualSampler.appを一度開きます。
2. Appleがマルウェアの有無を検証できない旨の警告が出たら、警告を閉じます。
3. Appleメニューから「システム設定」を開きます。
4. 「プライバシーとセキュリティ」を選び、「セキュリティ」の項目まで下へ移動します。
5. VisualSamplerのブロック通知にある「このまま開く」を押します。
6. 認証や確認を求められたら内容を確認し、起動を続ける場合は「開く」を選びます。
7. アプリが起動したら、必要に応じてBanksフォルダを選択します。

通常、許可は保存され、次回からはダブルクリックで開けます。
更新版では再び許可を求められる場合があります。

「このまま開く」が見つからない場合は、アプリを一度開こうとした直後に
設定画面を確認してください。会社や学校の管理下にあるMacでは操作できない場合があります。

「壊れている」「Macに損害を与える」「マルウェアを検出」などの警告が出た場合は、
この手順だけで進めず、公式配布元とダウンロードファイルを確認してください。
「応答しない」と出た場合も、繰り返し起動せず、一度終了してから再確認してください。

Apple公式の説明：
https://support.apple.com/ja-jp/102445


【4. BANKについて】

VisualSampler v1.0.1 FREEで使用できるのは、BANK AとBANK Bのみです。
各BANKに16枚、合計最大32枚の画像を割り当てられます。

BANK A：東京の日常風景を撮影した写真16枚（初期収録）
BANK B：BANK Aの写真をモチーフにした2色のマンガ風画像16枚（初期収録）

BANK C以降に画像を配置しても、FREE版では読み込まれず表示されません。
将来のVisualSampler PRO版では、使用可能なBANKを増やす予定です。
※PRO版の仕様・公開時期は未定で、変更される場合があります。

【5. 自分の画像を使う】

1. VisualSamplerを終了します。
2. Banks/BankA または Banks/BankB を開きます。
3. 既存画像をバックアップし、好きな画像と入れ替えます。
4. VisualSamplerを再起動して確認します。

対応画像形式：
  .jpg   （優先順位 1）
  .jpeg  （優先順位 2）
  .png   （優先順位 3）

拡張子の大文字・小文字は区別しません。

ファイル名のルール：
・PAD 01〜16に対応する「01」〜「16」で始めます。
・番号のみ、または「番号_任意の名前」を使用できます。
・例：01.jpg / 01_tokyo.jpg / 16_night.png
・「01tokyo.jpg」のように、番号の直後にアンダースコアが
  ない名前は対象外です。

同じPAD番号に複数の候補がある場合の優先順位：
  1. 拡張子：.jpg → .jpeg → .png
  2. 同じ拡張子なら、拡張子を除くファイル名が短いもの
  3. 同じ長さなら、ファイル名のアルファベット順（大文字小文字を無視）

例：01.jpg / 01_city.jpg / 01_tokyo.png がある場合、
    01.jpg が読み込まれます。

混乱を避けるため、1つのPAD番号につき画像1ファイルを推奨します。

【6. 推奨画像の画角・容量】

アプリの基準ウィンドウは 768 × 1024 px（横：縦 = 3：4）です。
画面比率に合わせて素材を制作するなら、縦長の3：4を目安にしてください。

推奨例：768 × 1024 px、または 1536 × 2048 px 程度。
※これらは制作上の目安であり、必須条件ではありません。
※画像の表示方法によって、トリミング・余白・変形の見え方が
  異なる場合があります。実際の表示を確認してください。

画像のファイルサイズや解像度が大きくなるほど、起動時に
BANK画像を読み込む時間が長くなる場合があります。
起動画面からメイン画面へ移るまでに時間がかかる場合は、
画像を適切なサイズに縮小・圧縮してください。

【7. Macキーボードでのウィンドウサイズ変更】

Shift + 1 ：384 × 512 px（50%）
Shift + 2 ：576 × 768 px（75%）
Shift + 3 ：768 × 1024 px（100%）

※画像ファイルそのもののサイズではなく、
  アプリのウィンドウサイズを切り替える操作です。
※キー配列や入力設定によって動作が異なる場合があります。

【8. ビジュアルエフェクト】

搭載エフェクト：
・GLITCH    ：デジタルノイズや映像の乱れ
・CRT       ：ブラウン管テレビ風の表現
・PIXELATE  ：粗いピクセル状の表現
・RGB SPLIT ：RGBの色ずれによる表現

SP-404MKIIでの操作：
・CTRL 1：エフェクトの選択
・CTRL 2・CTRL 3：選択したエフェクトの効果を調整
・EXT SOURCEを2度押し：エフェクトをリセット

※エフェクトの見え方や調整内容は、選択中の種類によって異なります。

【9. トラブルシューティング】

画像が表示されない場合：
・起動時の選択画面では、BankAやBankB単体ではなく親のBanksを選択
・選択をやり直す場合は、案内画面でRキーを押す
・保存した場所のBanksが存在し、読み取れるか確認
・「Banks/BankA」「Banks/BankB」の名前が正しいか確認
・画像が01〜16の命名規則と対応形式を満たしているか確認
・BANK C以降に画像を置いていないか確認
・画像を入れ替えた後、アプリを再起動したか確認

起動に時間がかかる場合：
・画像の解像度や容量を小さくして再試行してください。

SP-404MKIIで操作できない場合：
・USB接続と本体の電源を確認してください。
・SYSTEM → MIDIで「MIDI Mode：A」を確認してください。
・同じ画面で「PAD Note Out：ON」を確認してください。
・アプリを再起動して確認してください。

【10. 利用上の注意・商標】

VisualSamplerは個人制作のソフトウェアです。
環境によっては正常に動作しない場合があります。
本ソフトウェアの使用に伴う損害について、制作者は法律で認められる
範囲で責任を負いません。

画像を差し替える際は、著作権・肖像権などを守ってください。
ライブ配信や動画公開の際も、使用素材の権利にご注意ください。

VisualSamplerはRoland Corporationとは無関係の独立した制作物であり、
同社による開発・承認・後援を受けたものではありません。
RolandおよびSP-404MKIIは、Roland Corporationの商標または登録商標です。

【11. Credits / 制作者情報】

VisualSampler v1.0.1 FREE
Created by：achamania
Concept / Design / Development：achamania

© 2026 achamania. All rights reserved.

YouTube：achamania
https://www.youtube.com/@achamania

X（Twitter）：@achamania
https://x.com/achamania

デモンストレーションや制作活動については、上記SNSをご覧ください。

【12. Message from achamania】

あなたの作品を見せてください！

VisualSamplerを使って動画を制作・公開したら、
ぜひ僕のYouTubeチャンネルのコメント欄で教えてください！

ライブパフォーマンス、ミュージックビデオ、
街の風景を使った映像作品など、どんな使い方でも大歓迎です。

みなさんがVisualSamplerでどんな作品を生み出すのか、
とても楽しみにしています！

Show me what you've sampled!

YouTube：https://www.youtube.com/@achamania

Sample Your City. Remix Your Reality.

【v1.0.1の変更・確認状況】
・ダウンロード後のmacOS隔離実行で外部Banksを見失う問題に対応。
・Banks選択、選択場所の保存、選び直しに対応。
・アプリアイコンを更新。
・同梱Javaあり。Processingや追加Javaのインストールは通常不要。

2026-10-15、開発に使用したApple Silicon MacでGitHubからの再取得、
macOSの起動許可、Banksの読込・選択復旧、実機MIDI・BANK・FX・CTRL操作を確認しました。
全32画像・PAD処理は自動試験でも確認しています。
別Mac・長時間運転・全パラメータの全組合せは未検証です。
アプリの既存起動画面にはVer. 1.00と表示されますが、本パッケージはv1.0.1です。
