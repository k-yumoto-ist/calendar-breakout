# 会議、全消し。｜Calendar Breakout

会議を壊して定時退社を勝ち取るカレンダー型ブロック崩し。

- スマホ：下の操作エリアをタップで発射、スライドでバー移動
- PC：マウス・左右キーで移動、Spaceで発射、Xで必殺技
- 会議の分裂、追加招集、上司の妨害、有給の防御壁、金曜のボス会議
- 長押し選択抑止・ファビコン・iPhoneホーム画面用PNGアイコン

## 公開

https://k-yumoto-ist.github.io/calendar-breakout/

GitHub Settings → Pagesで「Deploy from a branch」、`main` / `/(root)` を指定します。
ビルド不要。mainの変更はGitHub Pagesに自動反映されます。

## ローカル起動

`python3 -m http.server 8000`

HTML / CSS / JavaScriptのみで動作。スコアはlocalStorageに保存し、実際のカレンダーとは連携しません。
