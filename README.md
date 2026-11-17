# 会議、全消し。｜Calendar Breakout

会議を壊して定時退社を勝ち取るカレンダー型ブロック崩し。

- スマホ：下の操作エリアをタップで発射、スライドでバー移動
- PC：マウス・左右キーで移動、Spaceで発射、Xで必殺技
- 会議の分裂、追加招集、上司の妨害、有給の防御壁、金曜のボス会議
- 長押し選択抑止・ファビコン・iPhoneホーム画面用PNGアイコン

## 公開

https://k-yumoto-ist.github.io/calendar-breakout/

GitHub Settings → Pages → Build and deployment → Sourceで **GitHub Actions** を選択してください（初回のみ）。

以後は `main` へのpushで `.github/workflows/pages.yml` が実行され、JavaScript構文チェック後にGitHub Pagesへ自動公開されます。Actionsタブの「Deploy GitHub Pages」から手動実行も可能です。失敗した場合は設定変更後に「Re-run all jobs」で再実行してください。

## ローカル起動

`python3 -m http.server 8000`

HTML / CSS / JavaScriptのみで動作。スコアはlocalStorageに保存し、実際のカレンダーとは連携しません。
