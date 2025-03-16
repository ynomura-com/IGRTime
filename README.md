# _IGRTime_
**IGRTime** は、[岩手銀河鉄道（IGR）](https://igr.jp/)の[時刻表](https://igr.jp/timetable)のうち、短距離運行の電車などを除いて、盛岡〜一戸間を走る列車のみを抽出した時刻表に、次の出発までの時間をカウントダウンする機能が付いたものです。

## 個人用に作ったもの
　私は、盛岡市に住んでいて職場のある一戸町に電車で通勤しているので、そのための時刻表として作成したものです。
 単にスプレッドシートに置き換えるのではなく、カウントダウン機能と、抜粋した時刻表の両方を見られるようにしました。
 盛岡駅、一戸駅と、岩手県立大学のある滝沢駅の時刻も追加しています。

 ## プログレッシブウェブアプリ (PWA) 
  2024年度までは HTML形式の単体ファイルにして、個人サイトにおいていましたが、プログレッシブウェブアプリ (PWA) にすれば、
  パケットを使わずに（通信ができない場合でも）利用できるので、2025年度から **PWA対応** にしてここで公開することにしました。
  （PWA実装の勉強を兼ねて）
  
## 使い方
背景が黒い部分内の下に並んだボタンで、駅（時刻表）を切り替えます。
選択された時刻表と現在時刻で次の便の時刻を選び、残り時間を上部の背景が黒のところに表示します。
また、次の手順でインストールすることで PWA としてネット接続無しでも利用できるようになります。

## スマホのホーム画面へインストール
　https://ynomura-com.github.io/IGRTime/
 にアクセスして、画面が表示されたらホーム画面に登録するだけ。
 PCの場合は、アドレスバーにインストールできるボタンが表示されますので、それを利用してインストール。
 
 !["QR code"](QR_IGRTime.png)　　← WebアプリにアクセスするQRコードです。

 ## 時刻表データ
 この時刻表データは 2025年3月15日改正のものです。
 
## ライセンス
 この作品はCC0 1.0でマークされています 
 <p xmlns:cc="http://creativecommons.org/ns#" >この作品は、<a href="https://creativecommons.org/publicdomain/zero/1.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC0 1.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" でマークされています。 src="https://mirrors.creativecommons.org/presskit/icons/zero.svg?ref=chooser-v1" alt=""></a></p>
 
