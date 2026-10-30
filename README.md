# Bahasa 1000

スマホ向けのインドネシア語1,000語学習PWAです。

## 学習データの保存

学習記録はブラウザの `localStorage` に端末内保存されます。
- 単語ごとの習熟度
- 復習予定
- 連続学習日数
- クイズ成績
- 最終保存時刻

アプリ内のバックアップ機能で進捗JSONを書き出し・復元できます。

## GitHub Pages

このリポジトリには GitHub Pages 用の Actions workflow を含めています。

1. Repository Settings > Pages を開く
2. Build and deployment > Source を **GitHub Actions** にする
3. `main` へのpush後、Actionsの `Deploy to GitHub Pages` が完了すると公開されます

公開URLの形式:
`https://<username>.github.io/<repository>/`

## iPhone

Safariで公開URLを開き、共有メニューから「ホーム画面に追加」を選ぶとPWAとして利用できます。
