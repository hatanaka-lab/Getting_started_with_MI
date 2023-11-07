# すぐできるマテリアルズ・インフォマティクス <br> －材料×機械学習の融合－　

## 本レポジトリについて
本レポジトリでは、第24回慶應科学技術展 KEIO TECHNO-MALL2023のプレイベント[基礎科学チュートリアル『すぐできるマテリアルズ・インフォマティクス～材料×機械学習の融合～』](https://www.kll.keio.ac.jp/ktm/pre/500/)における演習課題のサンプルプログラムとデータを提供する。

## 講義資料
- [Day1](基礎科学チュートリアル2023_Day1_配布資料.pdf)　
- [Day2](基礎科学チュートリアル2023_Day2_配布資料.pdf)　
## サンプルプログラム
- **演習[1]**　主成分分析(PCA)とデータの可視化 <br>
  TaSi<sub>17</sub>クラスターの構造(Ta-Si距離)とエネルギーの関係を考察しよう
  + [演習用ファイル：Ex1_PCA.ipynb](notebook_exercise/Ex1_PCA.ipynb)
  + [データファイル：TaSi17.csv](data/TaSi17.csv)
  + [閲覧用ページ](notebook/Ex1_PCA_forView.ipynb)　<br>
    
- **演習[2]**　はじめての教師あり学習 <br>
  Bostonの住宅価格を予測するモデルを構築しよう <br>
  * [演習用ファイル：Ex2_Boston.ipynb](notebook_exercise/Ex2_Boston.ipynb)
  * [データファイル：Boston.xlsx](data/Boston.xlsx)
  * [閲覧用ページ](notebook/Ex2_Boston_forView.ipynb)　<br>
  
- **演習[3]**　RDKitを用いる分子の特徴量の作成  <br>
  SDFやSMILES形式で書かれた分子の情報を特徴量に変換し、各分子の毒性を予測するモデルを構築しよう <br>
  * [演習用ファイル：Ex3_RDKit_Tox21.ipynb](notebook_exercise/Ex3_RDKit_Tox21.ipynb)
  * [データファイル(Structure-Data File)：nr-ar.sdf](data/nr-ar.sdf)
  * [データファイル(SMILES 記法)：smiles_data.csv](data/smiles_data.csv)
  * [閲覧用ページ](notebook/Ex3_RDKit_Tox21_forView.ipynb)　<br>
  
- **演習[4]**　誘導体のSMILESの作成  <br>
  指定した母骨格に対し、様々な置換基を持つ誘導体のSMILESを作成しよう <br>
  * [演習用ファイル：Ex4_SMILES.ipynb](notebook_exercise/Ex4_SMILES.ipynb)
  * [閲覧用ページ](notebook/Ex4_SMILES_forView.ipynb)　<br>
