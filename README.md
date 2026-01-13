# app-015-falling-catch-complete
```md
# 🎮 Day15 — Falling Catch Game (Complete)
落ちてくるアイテムをキャッチしてスコアを稼ぐ、シンプルな落ち物キャッチゲーム（完成版）です。  
Day15では **タイトル→プレイ→リザルト** の状態管理、**ライフ制**、**爆弾（避ける要素）**、**難易度スケーリング**、**LocalStorageでベスト保存** まで実装し、学習教材として“作り切る”ことを意識しました。

（100日チャレンジ / 100DaysOfCode — Day15）

---

## ✅ デモ（Demo）
GitHub Pages で公開：

```

[https://toy-abz.github.io/app-015-falling-catch-complete/](https://toy-abz.github.io/app-015-falling-catch-complete/)

```

※公開後に、あなたのリポジトリ名に合わせてURLを置き換えてください。

---

## 🌟 特徴（Features）
- Canvas API を使った 2D アニメーション
- ゲーム状態管理（Title / Playing / Result）
- スコア＆ライフ制（ミスで Life -1、0で終了）
- アイテム2種（GOOD / BOMB）
  - GOOD：キャッチで +1
  - BOMB：キャッチで Life -1（避けるゲーム性）
- 難易度スケーリング（時間経過で少しずつ難化）
- モード別ベストスコア保存（LocalStorage）
- 学習向けコメントを多めに記載

---

## 🎮 遊び方（How to Play）
- **← / →**：左右移動  
- **タップ**：タップ位置へ移動（スマホ向け）  
- **Space**：Start / Retry  
- **R**：Retry（リザルト画面）

---

## 🧠 学習ポイント（Learning Points）
- `requestAnimationFrame()` を使ったゲームループ
- `dt`（前フレームとの差分）で速度を安定させる設計
- Canvas 2D描画（背景・プレイヤー・落下物）
- 矩形同士の衝突判定（AABB）
- 配列（items）の管理（生成 / 更新 / 削除）
- 状態管理（scene: title / playing / result）
- LocalStorage によるデータ保存（モード別best）

---

## 🛠 技術スタック（Tech Stack）
- HTML
- CSS
- JavaScript (Vanilla)
- Canvas API

---

## 📦 ファイル構成（File Structure）
```

/app-015-falling-catch-complete
└── index.html   # 完全版ゲーム（単一HTML）

```

---

## 🚀 GitHub Pagesで公開する手順（Deploy）
1. このリポジトリに `index.html` をアップロード  
2. **Settings → Pages** を開く  
3. Source を **Deploy from a branch**  
4. Branch を **main / (root)** にして Save  
5. 表示されたURLからアクセス（反映まで少し待つ）

---

## 📜 ライセンス（License）
学習目的で自由に改変・利用OKです。  
（個人学習・教材化・ブログ紹介などにご活用ください）

---

# 🌍 English Version

## 🎮 Day15 — Falling Catch Game (Complete)
A simple falling catch game where you move left and right to catch items and score points.  
This Day15 “complete” version focuses on **finishing a game properly** with:
- game state management (Title / Playing / Result),
- life system,
- bomb items (avoid them),
- difficulty scaling,
- and best score saving via LocalStorage.

(100 Days of Code — Day15)

---

## ✅ Demo
Deployed on GitHub Pages:

```

[https://toy-abz.github.io/app-015-falling-catch-complete/](https://toy-abz.github.io/app-015-falling-catch-complete/)

```

Replace the URL after deployment if your repo name is different.

---

## 🌟 Features
- 2D animation with the Canvas API
- Game states (Title / Playing / Result)
- Score & Life system (miss = life -1, 0 = game over)
- Two item types (GOOD / BOMB)
  - GOOD: +1 score when caught
  - BOMB: -1 life when caught (avoid!)
- Difficulty scaling over time
- Best score saving by mode (LocalStorage)
- Beginner-friendly comments in the code

---

## 🎮 Controls
- **Left / Right Arrow**: Move
- **Tap**: Move to tap position (mobile)
- **Space**: Start / Retry
- **R**: Retry on result screen

---

## 🧠 Learning Points
- Game loop with `requestAnimationFrame()`
- `dt`-based movement for stable speed
- Canvas drawing (background / player / items)
- AABB collision detection (rect vs rect)
- Managing arrays (spawn / update / remove)
- State management (scene transitions)
- LocalStorage for saving best scores by mode

---

## 🛠 Tech Stack
- HTML
- CSS
- JavaScript (Vanilla)
- Canvas API

---

## 📦 File Structure
```

/app-015-falling-catch-complete
└── index.html

```

---

## 🚀 Deploy (GitHub Pages)
1. Upload `index.html` to this repository  
2. Go to **Settings → Pages**  
3. Set Source to **Deploy from a branch**  
4. Select **main / (root)** and Save  
5. Open the provided URL (may take a minute to go live)

---

## 📜 License
Open for learning and personal use. Feel free to modify and reuse.
```
