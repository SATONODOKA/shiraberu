# shiraberu
# 🔍 Shiraberu - ローカルAI検索アプリ

**完全無料・完全ローカル** なAIチャット + Web検索アプリケーション

![Status](https://img.shields.io/badge/status-Working-green)
![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/python-3.9%2B-blue)

## ✨ 主な機能

- 🤖 **ローカルLLMチャット**: Ollama (Gemma2 2B) 対応
- 🔍 **Web検索統合**: DuckDuckGo検索のリアルタイム統合  
- 💬 **リアルタイムUI**: Server-Sent Events (SSE) ストリーミング
- 🎨 **モダンUI**: HTMX + Tailwind CSS
- 🚀 **高速API**: FastAPI + Uvicorn
- 📱 **レスポンシブ**: モバイル対応UI

## 🚀 クイックスタート

### 1. インストール
```bash
git clone https://github.com/SATONODOKA/shiraberu.git
cd shiraberu
pip install -r requirements.txt
```

### 2. 起動
```bash
python server.py --port 8001
```
ブラウザで http://127.0.0.1:8001 にアクセス

### 3. Ollama セットアップ（任意）
```bash
# https://ollama.com/ からインストール
ollama pull gemma2:2b
ollama serve
```

## 📁 プロジェクト構成

```
shiraberu/
├── server.py          # FastAPIサーバー
├── index.html         # メインUI
├── chat_module.py     # AI チャット機能
├── search_module.py   # Web検索機能
├── requirements.txt   # Python依存関係
└── README.md         # このファイル
```

## 📊 実績

✅ **Ollama完全セットアップ成功**  
✅ **gemma2:2bモデルで実際のAI応答動作確認済み**  
✅ **Web検索連携動作確認済み**  
✅ **UI改善・グラデーションアバター完了**  
✅ **PowerShell安定動作・エラー修正完了**  

## 🔧 使用方法

1. **質問入力**: メッセージボックスに質問を入力
2. **🔍 Web検索**: チェックボックスでWeb検索ON/OFF
3. **モデル選択**: gemma2:2b / tinyllama選択
4. **リアルタイム応答**: ストリーミングでリアルタイム表示

## 🛠️ 技術スタック

- **Backend**: FastAPI + Uvicorn
- **Frontend**: HTML + HTMX + Tailwind CSS  
- **AI**: Ollama (Gemma2 2B)
- **Search**: DuckDuckGo API
- **Language**: Python 3.9+

---
*Developed with ❤️ by SATONODOKA* 
