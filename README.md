# Apple VAS デモガイド


[Apple VAS SDK 1.0 Demo](https://techdocs.zebra.com/nfc-vas/1-0/guide/demo/)

ECP1.0/2.0テクノロジーを使用して、Apple VAS にZebra Android デバイスが対応していることを証明するデモとなります。具体的にはiPhone Wallet 内のNFCパスをZebra デバイスで受信するものとなります。
        </br>


![Alt text](image.png)



## 端末の準備

1. デモ用端末を用意する。


   a. 下記機能を有するApple iPhone
      - Apple Wallet 
      - NFC 通信機能
  
   b. Zebra Android 端末*  

      \* A-VAS SDK に対応しているもの

    </br>

## Apple Passのインストール

1. iPhoneをインターネット接続できる状態にする
   
2. カメラで下記QRコードをスキャンする。
   
    <img src="https://techdocs.zebra.com/nfc-vas/1-0/guide/demo/qrcode.jpg" width="30%">

3. URLが表示されたら、選択。
   
4. 画面表示のガイドの通り処理を進め、Apple Passの登録をする。

    </br>

## Zebra VAS Demo ソフトのインストール

1. "Apple VAS SDK package"をダウンロードし、解凍する。
   
    [Apple VAS Package ダウンロード](https://www.zebra.com/us/en/support-downloads/software/developer-tools/value-added-services-sdk.html)

2.  下記apkをZebra デバイスにインストールする。

    - ZebraVasService-release-V-x.x.x.apk
    - Demo-app-release.apk
  
    </br>

## デモ手順

1. Zebra デバイスでNFC Ticket Demo アプリを起動する。
   <img src="https://techdocs.zebra.com/nfc-vas/1-0/guide/demo/app-main-screen.png" width="30%">

    </br>

2. iPhone で Apple Walletを起動し、デモ用にインストールしたパスを表示する。

    <img src="https://techdocs.zebra.com/nfc-vas/1-0/guide/demo/ios-demo-1.jpg" width="30%">

    </br>

3. iPhoneをZebra端末のNFCリーダとバンプさせる。

   1. 読み取り成功時の画面。

        <img src="https://techdocs.zebra.com/nfc-vas/1-0/guide/demo/read-success.png" width="30%">
        <img src="https://techdocs.zebra.com/nfc-vas/1-0/guide/demo/ios-demo-2.jpg" width="23%">

        </br>

    1. 読み取り失敗時の画面。
   
        <img src="https://techdocs.zebra.com/nfc-vas/1-0/guide/demo/read-fail.png" width="30%">

