# labviewfitter
LabVIEWを使用してのデータ処理ができます。
データのスムージング、ベースライン補正、

トリミング、フィッテングが可能です。

用いたアルゴリズムは以下の通りです。

スムージング: Savitzky-Golay

ベースライン補正: 重み付平滑化スプライン

フィッテング: 非線形最小二乗法

フィッテングはガウス関数のみ対応しています。

フィッテングにおいて、制約条件を指定することにより

より最適解に収束しやすくすることが可能です。
