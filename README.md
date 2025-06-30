# Revit 模様生成ツール（FillPattern Generator）

この Revit アドインは、ユーザー定義のパラメータに基づいて、タイル・ブリック・六角形などの**モデル塗りつぶしパターン（Fill Pattern）**を生成できるツールです。視覚的なプレビューと簡潔な UI により、独自の仕上げ模様を Revit プロジェクトへ簡単に作成・登録することが可能です。

---

## 🛠️ 使用技術
- C#（.NET Framework）
- Windows Forms UI
- Autodesk Revit API
- GDI+ によるリアルタイム描画処理
- 幾何演算による図形配置ロジック

---

## 📷 ユーザーインターフェース例

![image](https://github.com/user-attachments/assets/83d9659b-5366-47f3-921a-510b563e9fa9)

![image](https://github.com/user-attachments/assets/0f075b01-6a52-428d-9b57-dd21f6cfa6ce)

---

## 🚀 主な機能
- タイル・ブリック・六角形の3種パターンに対応（目地・スケール可変）
- 入力値に基づく即時プレビュー表示（GDI+）
- 任意スケール（mm単位）を Revit モデル単位（feet）へ自動変換
- Revit API による FillPattern / FillGrid の自動生成とプロジェクト登録
- 図案のカスタム命名と直接編集もサポート

---

## 📂 プロジェクト構成（抜粋）

| フォルダ / ファイル名 | 説明 |
|----------------------|------|
| `Form8.cs`           | メインフォーム・描画処理・FillPattern生成 |
| `Form9.cs`           | 自定義モードのサブウィンドウ（※実装による）|
| `README_ja.md`       | このREADMEの日本語版                       |

---

## 💼 担当範囲と学び
このプロジェクトは UI 設計、幾何描画、Revit API 操作など、BIM モデリングとプログラミングのスキルを融合した開発の実践例です。  
Revit におけるカスタム塗りつぶしパターンの業務効率化を目的に、**一人で全機能を設計・開発しました。**
