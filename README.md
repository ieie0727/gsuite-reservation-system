# GSuite Reservation System

Google スプレッドシート、Google カレンダー、Google フォームを活用した予約管理システムです。予約枠の作成、フォーム回答の転記、予約枠の管理を自動化し、スムーズな予約管理をサポートします。

## 機能

- **予約枠の自動作成と管理**  
  Google カレンダー上に予約枠を自動で作成し、調整します。
  
- **フォーム回答のリスト転記**  
  Google フォームで送信された回答を Google スプレッドシートに自動転記します。
  
- **予約管理と更新**  
  希望日時に基づき予約を確定し、予約ステータスを更新します。
  
- **カレンダーとフォームの同期**  
  Google カレンダーと Google フォームの予約枠を同期し、フォーム内の選択肢を最新に保ちます。

## 使い方

1. **リポジトリのクローンまたはダウンロード**  
   このリポジトリをローカルにクローンまたは ZIP ファイルとしてダウンロードします。

2. **Google Apps Script にアップロード**  
   Google Apps Script プロジェクトを作成し、スクリプトファイルをアップロードします。

3. **必要な ID の設定**  
   スクリプト内の以下の箇所に、使用する Google カレンダーとスプレッドシート、フォームの ID を設定します。
   ```javascript
   const RESERVATION_CALENDAR_ID = "your-reservation-calendar-id";
   const RESPONSE_SS_ID = "your-spreadsheet-id";
   const RESERVATION_FORM_ID = "your-form-id";
   ```

4. **スクリプトの実行**  
   必要な関数をトリガーに設定し、自動で予約管理が行われるようにします。

## 関数一覧

- **createReservationSlotAndArrange**: 予約枠を作成し、予約スロットを調整します。
- **onFormSubmited**: フォームの回答をリストに転記し、予約を確定します。
- **bookAvailableSlots**: 予約可能なスロットを確認し、カレンダーに「新規面談」を登録します。
- **updateReservationForm**: Google フォーム内の選択肢をカレンダーの予約枠に基づいて更新します。

## 必要な環境

- Google Workspace アカウント
- Google カレンダー
- Google スプレッドシート
- Google フォーム

## 注意事項

- 本システムは、Google Apps Script 上で動作します。設定や権限の確認を十分に行ってください。
- カレンダーやスプレッドシートの構成に合わせて、スクリプトの一部を調整する必要がある場合があります。
