# Q-JUMP 疑問文ジャンプ

中1英語「be動詞・can の疑問文と答え方」を練習するブラウザゲームです。
index.html 1ファイルで動きます（サーバー側の処理は不要）。

## GitHub Pages での公開手順

1. GitHub で新しいリポジトリを作成（例：`q-jump`、Public）
2. このフォルダの中身（index.html / README.md / .nojekyll）をアップロード
   - ブラウザの場合：「Add file」→「Upload files」にドラッグ＆ドロップ
     （.nojekyll は隠しファイルなので、見えない場合は無くても動きます）
3. 「Settings」→「Pages」→ Source を「Deploy from a branch」、
   Branch を `main` / `/(root)` にして Save
4. 1〜2分後に `https://<ユーザー名>.github.io/q-jump/` で開けます

既存のリポジトリ（方程式マスターなど）にまとめる場合は、
`q-jump/index.html` のようにフォルダごと置けば
`https://<ユーザー名>.github.io/<リポジトリ名>/q-jump/` で開けます。

## 動作環境

- マイク判定：Chrome（PC・Android）、iPhone の Safari
  - iPhone は「設定」→「一般」→「キーボード」→「音声入力」をオンに
  - 初回はマイクの許可を求められるので「許可」
- 進み具合（星・紙ミッション）はその端末のブラウザに保存されます

## 保護者用設定

マップ画面下の「マイク必須」を2秒長押しでオン／オフ。
マイクが使えない端末で進めなくなったときに使います。
