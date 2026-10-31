# 1周年記念AR — iPhone / Android 共通モード

## 公開方法
1. GitHub `katasin-180926/aiwebup` の Add file → Upload files を開く。
2. `marker-ar.html` をリポジトリのルートへアップロードし、Commit changes。
3. https://katasin-180926.github.io/aiwebup/marker-ar.html を Safari（iPhone）または Chrome（Android）で開く。
4. カメラへのアクセスを許可する。
5. 別の画面に https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png を表示するか印刷し、スマホのカメラを向ける。
6. ボックスが見えたら「プレゼントを開ける」を押す。

## 注意
- この版は「Hiro」マーカーを基準に位置合わせするマーカーARです。床面認識型ARとは異なります。
- 元の `index.html` は変更しないため、Android用WebXRは従来のURLで引き続き利用できます。
- HTTPSとカメラ許可が必要です。AR.js/A-FrameのCDN読み込みにはネット接続が必要です。
- iPhone/Android実機での動作はまだ未検証です。
- 個人写真はまだ入れていません。
