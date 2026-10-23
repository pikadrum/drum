# CLAUDE.md（ドラム側：pikadrum/drum）

## 作業を始める前に読むもの
1. `docs/ドラム側の引き継ぎ.md`（このリポジトリ）
2. `同期の仕様.md`（このリポジトリ。同期の正式な約束ごと）
3. 鍵盤側の引き継ぎ：https://raw.githubusercontent.com/pikadrum/keys/main/docs/鍵盤側の引き継ぎ.md
   - まだ無いときや読めないときは、そのことを伝えて作業を続ける。

## 作業の決まり
- 返事は日本語。
- PC版 `drum-practice.html` とスマホ版 `drum-practice-mobile.html` の両方に入れる。
- 機能を変えたら、配布ページ `index.html` と、ソフトの「このソフトについて」の説明も直す。
- 直したら `<script>` を取り出して `node --check` で構文を確かめ、Playwright のスクリーンショットで画面を確かめる。
- 1行のコードの中のコメントは `/* */` で書く。
- 設定のいちばん下の「ビルド YYYY/MM/DD HH:MM」を日本時間（`TZ=Asia/Tokyo date`）で更新する。
- ファイルは「出して」と言われたときだけ渡す。
- GitHub に上げる前に、返事の最後に文章で聞く（確認の画面は出さない）。上げたら、返事に配布ページ https://pikadrum.github.io/drum/ を書く。

## 終わるとき
- 変えたことがあれば `docs/ドラム側の引き継ぎ.md` を更新する。
- 同期の約束ごとを変えたら `同期の仕様.md` を直し、引き継ぎにも書く。
- 鍵盤側のリポジトリのファイルは書き換えない。
