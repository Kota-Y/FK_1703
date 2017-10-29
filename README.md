# Grandea ～広げるアイデア～

### Mobile App : https://github.com/jphacks/FK_1703  
  
### Server : https://github.com/jphacks/FK_1703_2  
  
[![Grandea](https://raw.github.com/GabLeRoux/WebMole/master/ressources/WebMole_Youtube_Video.png)](https://www.youtube.com/channel/UC4PtjOfZTbVp9DwtJv82Lzg)

## 製品概要
話し合っていることを認識してアイデア出しを手助けするモバイルアプリケーション

### Idea × Tech

### 背景（製品開発のきっかけ、課題等）
アイデア出しって楽しいけど難しい、、、。  
アイデア出しと言うと堅苦しく感じますが、近年、新規企画やハッカソンなどのイベント、  
また旅行の計画などの日常の中にもアイデア出しは行われています。  
そんな頻繁に行われているアイデア出しを楽しく・円滑に行いたい！  
そうした思いから今回の開発に至りました。

### 製品説明（具体的な製品の説明）
Grandeaは、アイデア出しをする際のミーティング中に起動しておくだけで、アイデア出しの補助を行ってくれるモバイルアプリケーションです。また、話した内容・要約・ミーティングのキーワードをまとめた議事録も作成してくれます。

![システムフロー](/flow.png)

### 特長

#### 1. リアルタイムストリーミング音声認識  

#### 2. こだわりのアイデアマップ  

#### 3. 自動で議事録作成  

### 解決出来ること
* アイデア出しの停滞防止  
話し合っていることに関連するキーワードを提供することにより、アイデア出しの停滞を防ぎます。  
* 共通認識の欠如防止  
話し合っている内容やキーワードを示すことにより、共通認識を持てます。  
* 議事録作成の手間の削減  
話し合った内容を認識し、自動で議事録を作成することにより、議事録作成の手間を削減します。  

### 今後の展望
* WebRTCによる遠隔ビデオ通話ミーティング上での実装  
* 音声データから特徴量を抽出し、話者識別をするニューラルネットモデルの作成  
* 音声認識した文章の補完  
* Raspberry Piを用いてガジェット化  
* 高集音性マイクを用いて集音性の向上  

## 開発内容・開発技術
### 活用した技術
#### API・データ
* Google Cloud Speech API
* Google Cloud Translation API
* Google Knowledge Graph Search API
* Google Suggest API
* gooラボ キーワード抽出API
* 自動要約API

#### フレームワーク・ライブラリ・モジュール
* Android Studio
* XAMPP
* CherryPy
* asyncio(非同期I/Oライブラリ)
* Project Tyrus(Java API for WebSocketのリファレンス実装)
* Amazon Web Services
* さくらのレンタルサーバ

#### デバイス
* Android(Android 5.0以上)

<!--
### 研究内容・事前開発プロダクト（任意）
ご自身やチームの研究内容や、事前に持ち込みをしたプロダクトがある場合はこちらに実績なども含め記載をして下さい。
-->

### 独自開発技術（Hack Dayで開発したもの）
#### 2日間に開発した独自の機能・技術
* サーバ・クライアント間のリアルタイムストリーミング通信  
* アイデアマップの作成
* 2つのAPIを用いての関連キーワード取得 [(Code)](https://github.com/jphacks/FK_1703_2/blob/master/relation_char.php "relation_char.php")  
<!--
* 独自で開発したものの内容をこちらに記載してください
* 特に力を入れた部分をファイルリンク、またはcommit_idを記載してください（任意
-->
