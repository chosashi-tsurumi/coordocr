# 座標OCR（COORDOCR）

PDFの座標表を切り抜き、PC内のAIで読み取り、確認・修正してSIMAデータへ出力するWindows用アプリです。

**v1.0 正式版／使用期限なし**

## ダウンロード

**[COORDOCR-v1.0.zip（約2.12GB）](https://github.com/chosashi-tsurumi/coordocr/releases/download/v1.0/COORDOCR-v1.0.zip)**

[公式配布ページ・操作案内](https://chosashi-tsurumi.jp/coordocr)

GitHubの「Source code」ではなく、上記の配布ZIPを選んでください。

## 主な機能

- 複数PDFから座標表を切り抜き、PNG・JPEG画像も追加
- 対象画像を選んでOCRし、原画像と見比べながら点名・座標を修正
- 点名へのプリフィクス付与・連番への変更、SIMA出力
- CPU・CUDA・Vulkanの選択、日本語／英語の表示切り替え

## 動作環境

Windows 11 64bit（x64）、RAM16GB以上を想定。ZIPと展開先を合わせて空き容量6GB以上に加え、作業データの保存領域が必要です。

初期設定はCPUです。GPU利用には対応ドライバーが必要です。書き込み可能な場所へ展開すれば、通常は管理者権限なしで起動できます。ダウンロード後のOCR・SIMA出力はオフラインで利用できます。

## 使い方

1. ZIPを「すべて展開」し、`座標OCR.exe`を起動します。
2. PDFから座標表を切り抜き、対象画像を選んでOCRします。
3. 元資料と照合して修正し、**「修正を反映」**を押します。
4. SIMAのファイル名と保存先を指定して出力します。

画像や座標一覧は配布フォルダ内の`data`へ保存されます。更新・バックアップ時は、このフォルダを保管してください。

## 注意事項

- 読取・出力結果は必ず元資料と照合し、業務上重要な判断をアプリの結果だけで行わないでください。
- 利用環境や資料によって、正常に動作しない、または処理に時間がかかる場合があります。
- EXEは未署名のため、Windowsで警告が表示される場合があります。

## 質問・不具合報告

[座標OCR専用Googleフォーム](https://docs.google.com/forms/d/e/1FAIpQLScKcNl2N-g1etGMZigus0Ck8GP5lEX3IcysscK9PXw_t1vo-Q/viewform?usp=header)へお寄せください。

配布元：[土地家屋調査士 鶴見事務所](https://chosashi-tsurumi.jp/)

このリポジトリは配布用です。アプリのソースは非公開です。同梱ソフトウェア・モデルのライセンスはZIP内の`licenses`をご確認ください。
