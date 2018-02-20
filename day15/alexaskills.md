# Amazon Alexa Skills開発におけるAWSとの連携

## 翔泳社紹介ページ
http://event.shoeisha.jp/devsumi/20180215/session/1638/

## 資料

## 気持ち


## echo背景
- 購買体験，時間短縮
- 結果としてイノベーションを起こす

### amazon go
- Amazon GOをシアトルで体験してもし万が一決済されなかったら、Amazon側の問題なので気にせず去ってください

### amazon倉庫
- pickerは動かなくていい棚が自分で考えて動いてくる

## skills
- 個人なら自由，公開なら申請が必要
- 人間は無意識に音声へのリプライを求める
	- かなり速く返す必要がある
- 開発はfirefoxかchromeが推奨 
- 1個のインテントに対して10個以上の表現を推奨
- 開発環境のシェアができる
- エミュレータもあるよ

- voice interfaceは次の新しい標準になる

### skils 例
- もと画像ー＞s3 -> lambda -> dynamom 
	- s3でのイベントによりlambdaが処理を返す
	- ステートをdynamodbへ
	- 処理結果をs3へ

### スキル種類
- ビルトイン
- alexaskill
	- カスタム
	- スマートホーム
	- フラッシュブリーフィング
	- ビデオスキル

## まとめ
1. 音声ifの設計
	2. 開発者ツール>スキルビルダー
	3. 1つの命令には10個のバリエーションがあった方がいい
2. 処理ロジック
	3. awsで用意してるからカスタムしなさい
3. 1と2を接続
	4. 設定からできる
5. 設定

