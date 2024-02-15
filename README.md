# labviewfitter
LabVIEWを使用してのデータ処理ができます。

データのスムージング、ベースライン補正、

トリミング、フィッテングが可能です。

***Releasesからインストーラーが含まれた
zipファイルをダウンロードできます。
これを用いることにより、LabVIEW開発ソフト無しでも
labviewfitterを利用可能です。***

***From Releases, you can download an
installer for labviewfitter and use it without
installing LabVIEW development system, which in 
some cases not free of charge.***

データ処理に用いたアルゴリズムは以下の通りです。

スムージング: Savitzky-Golay

ベースライン補正: 重み付平滑化スプライン

フィッテング: 非線形最小二乗法

フィッテングはガウス関数のみ対応しています。

フィッテングにおいて、制約条件を指定することにより

より最適解に収束しやすくすることが可能です。
