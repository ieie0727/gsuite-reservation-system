## 概要
このプロジェクトは、Google カレンダー、Google フォーム、Google スプレッドシートを活用した予約管理システムです。自動で予約枠の調整やフォームの更新を行い、予約の手間を省くことを目的としています。

## 主要機能
- **予約枠の作成と管理**: 指定された日時に基づき、Google カレンダー上に予約枠を自動生成。
- **フォーム更新機能**: 最新の予約枠をGoogleフォームに反映し、ユーザーが選択できるよう自動調整。
- **予約確定処理**: フォームからの回答をもとに、リストに記録し、対応する予約枠を確定。
- **スプレッドシート記録**: 予約済みデータの記録と更新をスプレッドシート上で行い、必要な情報を集約。

## 実際のデモ
- **フォームリンク**: [予約フォーム](https://docs.google.com/forms/d/e/1FAIpQLSfMzRGx8dZRRZBbHF2YIM0G3unfJ0buGevljIzsaPDCDlpbhQ/viewform)
- **スプレッドシートリンク**:  [予約データ管理用のスプレッドシート](https://docs.google.com/spreadsheets/d/14Tmpp6AVqg7R4aa1U3kV-pYgWPeA1aEURhHRWQebXDo/edit?gid=1243878587#gid=1243878587)
- **Google カレンダーリンク**: [予約カレンダー](https://calendar.google.com/calendar/u/0?cid=OWU0YmFlMTg0MjU2MGUzM2YyNTI0NDNjZDU4ZjcwOTgzNjBiMDBiODMzZDFlMDQyODQ2ZWMyMzEzYzMyYWRhYUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t)　[代表カレンダー](https://calendar.google.com/calendar/u/0?cid=MjI0MDEyYWRjZmNjN2UwM2NiZjY0YTRhZDZjMzEzNWMzODkyY2MwMmFhYmI0NGJmZjcwNzdjN2NlYmJjMDE2MUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t)

> ※各リンクはポートフォリオ閲覧用に設定しているため、編集権限がありません。データの閲覧と操作のみご覧いただけます。

## スクリーンショット
- **フォーム画面例**: 最新の予約枠選択画面
- **スプレッドシート画面例**: 自動で転記・更新される予約記録
- **カレンダー画面例**: 予約枠と確定予約の表示

## システム構成図
このプロジェクトは、Google Apps Scriptによりフォーム・スプレッドシート・カレンダーが自動連携するよう構成されています。

### 使用技術
- Google Apps Script
- Google スプレッドシート
- Google フォーム
- Google カレンダー
