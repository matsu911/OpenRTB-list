# OpenRTB関連

## OpenRTB以前
### demand-side platform
+ DataXu
+ MediaMath
+ Trun

### sell-side platform
+ Admeld
+ PubMatic
+ The Rubicon Project

## 関連資料
+ [OpenRTB on Google Groups](http://openrtb.info)
+ [OpenRTB Github Repository](http://github.com/openrtb/OpenRTB/)
+ [Development Community Mailing List](http://groups.google.com/group/openrtb-dev)
+ [User Community Mailing List](http://groups.google.com/group/openrtb-user)

## 用語
- RTB - 個々のインプレッションに対するリアルタイムのbid入札
- Exchange - インプレッションごとにbidder間のオークションを行うサービス
- Bidder - インプレッション獲得のためにリアルタイムオークションで競うエンティティ
- Seat - Bidderを使ってインプレッションを獲得を狙うエンティティ
- Publisher - Site運営者
- Site - 広告のあるコンテンツを含むwebやアプリケーション
- Deal ID - ある契約のもとでのPublisherとSeat間のインプレッション購入に関する事前の契約に関するID

## RTBの基礎
### Transport
HTTPのPOSTとGET

### セキュリティ
SSLは不要で別の手段でセキュリティは確保

### データフォーマット
JSONを推奨
content-typeはフォーマットに応じて適切に設定

