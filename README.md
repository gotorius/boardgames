# 🎮 ボードゲーム コレクション

クラシックなボードゲームをオンラインで楽しめるWebアプリケーション集です。

## 🎯 プレイする

**[▶️ ゲームをプレイ](https://gotorius.github.io/boardgames/)**

## 🎲 ゲーム一覧

| ゲーム | 状態 | 説明 |
|--------|------|------|
| 🃏 [フリーセル](./freecell/) | ✅ 公開中 | クラシックなトランプソリティア |
| ⚫ オセロ | 🚧 準備中 | 白と黒の戦略ゲーム |
| ♟️ 将棋 | 🚧 準備中 | 日本の伝統的な戦略ゲーム |
| ♛ チェス | 🚧 準備中 | 世界で愛される戦略ボードゲーム |
| ⭕ 五目並べ | 🚧 準備中 | シンプルで奥深い対戦ゲーム |
| 💣 マインスイーパー | 🚧 準備中 | 論理パズルゲーム |

## ✨ 機能

- 🎮 複数のクラシックゲーム
- 🏆 ランキングシステム
- ⚔️ オンライン対戦（一部ゲーム）
- 📱 レスポンシブデザイン
- 🌐 ブラウザのみで動作

## 🛠️ 技術スタック

- HTML5
- CSS3
- JavaScript (Vanilla)
- Firebase (ランキング・対戦機能)

## 📁 ディレクトリ構成

```
boardgames/
├── index.html          # ホーム画面
├── styles.css          # 共通スタイル
├── freecell/           # フリーセル
│   ├── index.html
│   ├── game.js
│   ├── styles.css
│   └── firebase-config.js
├── othello/            # オセロ（予定）
├── shogi/              # 将棋（予定）
└── chess/              # チェス（予定）
```

## 🚀 ローカルで実行

```bash
git clone https://github.com/gotorius/boardgames.git
cd boardgames
python3 -m http.server 8080
# ブラウザで http://localhost:8080 を開く
```

## 📄 ライセンス

MIT License
