---
name: "[Copilot対応] 機能リクエスト-md"
about: Copilotを利用してプロジェクトに対する新しい機能を追加する
title: "[CU-XXXX] 機能名"
labels: enhancement, copilot-task
assignees: ''
---

### 🤖 Copilotへの指示事項（システムルール）
- **ガイドラインの遵守**: `.github/copilot-instructions.md` に準拠すること。
- **ターゲットブランチ**: `xxxx` ブランチに対して実装・修正を行うこと。
- **言語設定**: Pull Request内の説明、コミットメッセージ、コード内のコメントはすべて「日本語」で記述すること。
- **ブランチ命名規則**: ブランチを作成する際は、必ず `CU-XXXX` （Issueタイトルのプレフィックスと一致）の名称で作成すること。

---

### 📖 背景と目的（コンテキスト）
- **現状の課題**: 
- **機能の目的**: 

### ✨ 仕様と期待する動作（要件定義）
1. 
2. 
3. 

### ✅ 受け入れ条件（Acceptance Criteria）
- [ ] 
- [ ] 
- [ ] 

---

### 📂 対象モジュールとファイル情報
#### 対象モジュール
| 選択 | モジュール | 用途 | ディレクトリ例 |
|:----:|-----------|------|---------------|
| [ ] | default | ホーム画面、エラーハンドリング | `/default/` |
| [ ] | login | 認証、パスワード管理 | `/login/` |
| [ ] | admission | 入学手続き管理 | `/admission/` |
| [ ] | student | 学籍情報管理 | `/student/` |
| [ ] | lesson | 履修・カリキュラム・シラバス管理 | `/lesson/` |
| [ ] | cuext | 公開学習（エクステンション） | `/cuext/` |
| [ ] | system | システム管理（お知らせ、イベント等） | `/system/` |

#### 実装対象・参照ファイル
- **新規作成・変更するファイル**:
  - 
  - 
- **参考にすべき既存実装（コーディングパターン）**:
  - Controller: `例: controllers/admission/Admission_StatusController.php`
  - Model: `例: models/admission/Admission_StatusModel.php`
  - Template: `例: smarty/templates/admission/status/status.html`

---

### ⚠️ 制約事項・非機能要件 (任意)
- 

### 📎 追加情報 (任意)
-