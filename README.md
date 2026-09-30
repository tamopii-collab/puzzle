# 落ちものパズル

ブラウザで遊べる落ちものパズルゲームです。PC（キーボード）とスマホ（タッチ操作・縦画面）に対応しています。

プログラミング学習のために作った非営利の作品です。

- ゲーム本体: [`game/indexyo001.html`](game/indexyo001.html)
- トップの `index.html` は、ゲーム本体へ自動で移動するためのページです。

## GitHub Pages で公開する手順

1. GitHub で新しいリポジトリを **Public** で作成します（例: `puzzle`）。README などの初期ファイルは追加しないでください。
2. このフォルダで次のコマンドを実行し、ファイルを push します。

   ```bash
   git remote add origin https://github.com/<ユーザー名>/<リポジトリ名>.git
   git push -u origin main
   ```

3. GitHub のリポジトリ画面で **Settings → Pages** を開きます。
4. **Build and deployment** の **Source** を「Deploy from a branch」にし、Branch を `main`、フォルダを `/ (root)` にして **Save** を押します。
5. 1〜2分ほど待つと、次の URL で遊べるようになります。

   ```
   https://<ユーザー名>.github.io/<リポジトリ名>/
   ```

更新するときは、変更を commit して `git push` するだけで自動的に反映されます。

## 操作方法

| 操作 | キーボード | スマホ |
| --- | --- | --- |
| 移動 | ← → | 左右にスワイプ ／ ◀ ▶ ボタン |
| ゆっくり落下 | ↓ | 下にドラッグ ／ ▼ ボタン |
| 一気に落下 | Space | 下にすばやくスワイプ ／ ⤓ ボタン |
| 右回転 | ↑ / X | タップ ／ ⟳ ボタン |
| 左回転 | Z | ⟲ ボタン |
| ホールド | C / Shift | 上にすばやくスワイプ ／ HOLD ボタン |
| 一時停止 | P / Esc | Ⅱ ボタン |
| 音の ON/OFF | M | 🔊 ボタン |
