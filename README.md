# food-packaging(competition)
SIGNATE「食品パッケージ画像解析チャレンジ」

「drink」 or 「food」の2値分類

評価指標：AUC

交差検証法を用いて、それぞれのfoldごとでモデルの学習を行いました。

それぞれのfoldごとに学習したモデルから予測確率を算出し、その平均値を最終的な予測確率としました。
