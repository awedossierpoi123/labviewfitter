# labviewfitter
LabVIEWを使用してのデータ処理ができます。

labviewfitter allow users to process data using LabVIEW.

データのスムージング、ベースライン補正、トリミング、フィッテングが可能です。

Smoothing, baseline correction, trimming, curve fitting of data points can be done.

***Releasesからインストーラーが含まれた
zipファイルをダウンロードできます。
これを用いることにより、LabVIEW開発ソフト無しでも
labviewfitterを利用可能です。***

***From Releases, you can download an
installer for labviewfitter and use it without
installing LabVIEW development system, which in 
some cases not free of charge.***

データ処理に用いたアルゴリズムは以下の通りです。
Here are lists of algorithms used for data processing.

スムージング Smoothing: 移動平均 Moving Average, Savitzky-Golay

ベースライン補正 baseline correction: 平滑化スプライン Smoothing Splines

フィッテング curve fitting: 非線形最小二乗法 non-linear least squares

フィッテングはガウス関数のみ対応しています。

フィッテングにおいて、制約条件を指定することにより

より最適解に収束しやすくすることが可能です。

Only gaussian functions can be used for curve fitting.

It is possible to use constraint conditions so that least squares can be solved efficiently.
