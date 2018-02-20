# スタートアップなエンジニアLT！〜スタートアップはどんな技術を駆使して開発を行っているのか？〜

## 翔泳社紹介ページ
http://event.shoeisha.jp/devsumi/20180215/session/1649/

## 気持ち

# studist 快適なマニュアル作成・共有を支えるSite Reliability Engineering
https://speakerdeck.com/katsuhisa91/kuai-shi-namaniyuaruzuo-cheng-gong-you-wozhi-erusite-reliability-engineering?slide=1

- 伝えることをもっと簡単に
- マニュアルの作成と共有を簡単に

## 問題
- Ops不可高い
- モニタリング設計が貧弱
	- サービスの状況が把握しきれない

## 解決策 SRE導入
- SREチームってのがある
	- googleが導入
- 定形作業を自動化
	- gem導入など

## toil削減
- 手作業の運用業務
- プロダクトに対する価値を産まない
- 基本的には無駄

## toil削減とその優先度

## モニタリング
- アラート、チケット、ロギングを見ればよい

# abeja
- 機械学習docker
- 機械学習は学習と推論の2種がある
- kubernetesのクラスタgpuの＾どいっぱい
- 推論はecs aws batch

# jx通信
https://speakerdeck.com/yamitzky/sabaresuwohuo-yong-siteshao-shu-jing-rui-dekai-fa-suruniyusuapuri-number-devsumi

- サーバレスアーキテクチャ
- 配信はサーバレス
- それ以外はdcoker ログ基盤など
- サーバレスでやるとインフラエンジニアいらず

サーバレスでGraph QL APIを提供
パフォーマンスは金でスケール
サーバレス化前は手動でスケール
サーバレスで乗り越えられなかった話もある

# cloudworks
https://speakerdeck.com/hideki/chatops-history-of-crowdworks
## Botが14体
	- 重要度の高い機能と低い機能が混在

## Botを分割
- bot重要なことと便利系を分けた
- 重要botをさらに分けたメインサービス用の機能を分離
- さらに環境で分けた

## Botの連携
BotからBotへ連携
Slackで＠

# cacoo html5で変わった
https://cacoo.com/diagrams/5SNHdnrh8hFGBLcv#0CBD0

- indexedDB
- APIサービス

ぶっちぎりの速さのために
特定の技術だけでパフォーマンスを上げるのは難しい
ベンチマークをもとにした技術比較選定
データ構造の見直し
メモリの最適化
技術+工夫が必要

# go仮想通貨
https://speakerdeck.com/sonatard/goyan-yu-tojia-xiang-tong-huo

- 並列処理が容易にできる
- GAE osの管理が楽

仮想通貨技術の説明
プロダクト開発に集中したい
そのために環境づくり
GAE/Go

# agurige^to
- it使っても生産性の向上につながらない
- この現状を変える環境づくりをしている
未来に「おいしい」をつなぐインフラの創造を支えるITの存在意義 〜農業の課題と可能性〜
農業の課題と可能性
食農業界でITを活用しても生産性が向上しない
データは集約されていない
データ量が膨大
流通量が増えているにもかかわらず、値段が上がっている
SPAのフード版で、SPF
生産から販売までも一気通貫でやる