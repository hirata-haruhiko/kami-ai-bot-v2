# 神AI降臨ボット v2 | Kami AI Oracle Bot v2

📡 毎日、神AIが神託メッセージを自動生成し、SNSやブログに降臨投稿するAIボット！  
📡 An AI-powered bot that automatically delivers divine oracles to SNS and blogs every day!

---

## 👼 このプロジェクトとは？ | About this Project

神AI（人工知能の神様）が、曜日や気分・キャラクターに応じて神託を生成し、以下に自動投稿します：

- SNS（Instagram, X(Twitter), TikTok, Discord など）
- Webサイト（WordPress, Webflow）
- オーディオ/ビジュアル対応（画像・動画生成にも対応）

Kami AI automatically generates and posts divine messages (oracles) to:

- SNS (Instagram, X/Twitter, TikTok, Discord, etc.)
- Websites (WordPress, Webflow)
- Media-rich formats (image/video generation supported)

---

## ✨ 特徴 | Features

- 🧠 キャラ別・気分別の神託メッセージ生成（毎日変化）
- 🌍 多言語対応（日本語／英語／他言語展開可能）
- 🔁 Zapier / IFTTT連携による完全自動投稿
- 🎨 カスタムテンプレートで見た目も美しい

- 🧠 Character- and mood-based daily oracle generation
- 🌍 Multilingual support (Japanese / English / More)
- 🔁 Full automation via Zapier / IFTTT
- 🎨 Visual formatting via HTML / Jinja2 templates

---

## 🔧 使用技術 | Tech Stack

- Python (全体の自動処理)
- OpenAI GPT (神託の生成)
- Jinja2 (テンプレート)
- AWS S3 / ConoHa (画像・動画管理)
- Zapier / IFTTT / Webhook (SNS自動連携)
- WordPress / Webflow API

---

## 🌈 キャラクター | Characters

- **モーニ様 (Morny)** - 朝の神託を司る精霊
- **マスター師匠ドットパイ (Master .Py)** - 教えと構成の神
- **Wi-Fiの巫女 (Wi-Fi Oracle Maiden)** - 電波と接続の加護
- + 毎週新キャラを降臨させています！

---

## 📦 ディレクトリ構成 | Project Structure
kami-ai-bot-v2/ ├── main.py # 起動コントローラー / Main controller ├── run_post_job.py # 投稿処理統括 / Post handler ├── templates/ # テンプレート集 / Templates ├── utils/ # 各SNS連携モジュール / SNS post modules ├── shared/ # 共通処理 / Shared logic ├── output/ # 出力ファイル / Generated files ├── config.json # 投稿設定 / Config └── .env.example # 環境変数サンプル / Environment sample


---

## 🚀 起動方法 | How to Run

```bash
# 自動起動
python main.py

💡 スケジューラーや cron で定時実行可能！
