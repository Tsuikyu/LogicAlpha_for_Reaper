# LogicAlpha_for_Reaper
Reaper Keyboard Shortcuts like Logic Pro

【試作品】ReaperのショートカットをLogic風にするやつ

---

## 概要
Logic の操作感（キーボードショートカット／マウス挙動）を Reaper に寄せるためのキーマップ／マウスマップ集（試作品）。

単なるツールに過ぎないので、改変と再配布は基本的にOK。  
ただし、あくまでも試作品なので、導入や使用等は自己責任でお願いいたします。

導入や使用等をされる前に、**必ずバックアップを取ってください。**

---

## メタ情報

- **Project:** LogicAlpha_for_Reaper  
- **Author:** Tsuikyu  
- **Version:** 8  
- **公開日:** 2025年3月30日 23:12  

---

## インストール方法（macOS）

### キーマップ

ファイル：
- `LogicAlpha.ReaperKeyMaps`

配置先：
```
Macintosh HD/Users/~/Library/Application Support/REAPER/KeyMaps
```

### マウスマップ

ファイル：
- `LogicAlpha.ReaperMouseMaps`

配置先：
```
Macintosh HD/Users/~/Library/Application Support/REAPER/MouseMaps
```

※ `~` はあなたのホームディレクトリです。

---

## Reaper への適用手順

1. Reaper を起動
2. メニューから以下を実行  
   ```
   アクション
    └ アクションリストを開く
       └ キーマップ
          └ Import shortcuts/custom actions
             └ Import all sections
   ```
3. `LogicAlpha.ReaperKeyMaps` を選択して読み込む

4. 次にマウスコマンドを適用  
   ```
   Settings
    └ 編集動作
       └ マウスコマンド
          └ 読込書出
             └ 全項目のマウスコマンドを読み込む
   ```
5. `LogicAlpha.ReaperMouseMaps` を選択して適用

---

## 注意事項

- 本ツールは**試作品**です  
- 導入・使用は**自己責任**でお願いします  
- 既存のショートカットやマウス設定と競合する可能性があります  
- 必ず事前に `KeyMaps` / `MouseMaps` フォルダのバックアップを取ってください  

---

## ライセンス

単なるツールに過ぎないため、**改変・再配布は基本的にOK**です。  
詳細な条件については、リポジトリに記載されているクリエイティブコモンズ表記を参照してください。

---

## 変更履歴

- **2026年2月6日**  
  Dropbox から GitHub に移動しました。

- **2025年4月2日**  
  スクロールとズームを Logic と同じ挙動に変更。  
  囲みズームや時間選択などのマウスコマンドを追加。  
  Reaper 特有の環境に合わせ、オリジナルマウスコマンドとして  
  `⌘⌥（コマンド＋オプション）+ ドラッグ` でアイテムを作成できるように調整。  
  クリエイティブコモンズを追加。

- **2025年3月31日**  
  公開。
