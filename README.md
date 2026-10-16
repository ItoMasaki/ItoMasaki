# 伊藤 昌樹 | ITO Masaki

**世界モデル・強化学習・ロボティクス**を軸に、機械学習の研究とシステム開発に取り組んでいます。大学院では世界モデルを用いたロボットの物体把持を研究し、現在は制御・ロボット学習・3D点群処理へと対象を広げています。

## 経歴

| 年 | 所属・経歴 |
| :--- | :--- |
| 2018年 | 立命館大学 入学 |
| 2022年 | 立命館大学大学院 情報理工学研究科 入学 |
| 2024年 | 株式会社ウェザーニューズ 入社 |
| 2026年 | 株式会社中央エンジニアリング 入社 |

## 大学・大学院での研究と活動

### 大学院：世界モデルを用いたロボットの物体把持

立命館大学大学院 情報理工学研究科では、**世界モデルとロボットによる物体把持**を研究しました。観測から環境の表現を学習し、その表現をロボットの制御につなげることで、少ないデータから行動を学習する手法に関心を持って取り組みました。

- 生成モデルによる環境・状態の表現学習
- 学習した表現を用いたロボット制御と物体把持
- 国際会議 **SII（IEEE/SICE International Symposium on System Integration）**での論文採択

#### 関連リポジトリ：NewtonianVAE

[**NewtonianVAE**](https://github.com/ItoMasaki/NewtonianVAE) は、物理的な構造を持つ潜在表現を学習し、画像からの制御につなげる手法の実装です。データ収集・モデル学習に加え、潜在表現の相関や制御への利用を確認するスクリプトを公開しています。

<p align="center">
  <img src="https://raw.githubusercontent.com/ItoMasaki/NewtonianVAE/main/docs/NewtonianVAE_srcnn_anime_noise1.gif" alt="NewtonianVAEリポジトリに掲載している制御実験のアニメーション" width="560">
</p>

<p align="center"><sub>NewtonianVAEの公開実装に掲載している制御実験</sub></p>

<details>
<summary>潜在表現の評価画像</summary>

![NewtonianVAEの潜在表現の相関評価](https://raw.githubusercontent.com/ItoMasaki/NewtonianVAE/main/docs/correlation.png)

</details>

### RoboCup：家庭支援ロボットの開発

**Toyota Human Support Robot（HSR）**を用いた家庭支援ロボットの開発に取り組み、RoboCupではチームで**準優勝**を経験しました。ロボットを実際に動かす中で、研究手法だけでなく、システムとして動作させるための実装・統合・検証の重要性を学びました。

| 項目 | 内容 |
| :--- | :--- |
| 活動 | RoboCupへの参加・家庭支援ロボットの開発 |
| ロボット | Toyota Human Support Robot（HSR） |
| 成績 | チームで準優勝 |

#### 関連リポジトリ：ROS2Docker

[**ROS2Docker**](https://github.com/ItoMasaki/ROS2Docker) では、Dockerを用いたROS2開発環境を公開しています。ロボティクスの共同研究・開発において、環境の再現性を確保し、開発環境を共有しやすくするための基盤です。

## ウェザーニューズでの取り組み

2024年に**株式会社ウェザーニューズ**へ入社し、海運事業に関わる社内システムの開発・改修に取り組みました。

- 海運サービスの運用を支える業務ツールの開発・改善
- 定型作業の自動化と、手作業を減らすための業務フローの改善
- 現場の要望をソフトウェアの要件・実装へ落とし込む開発

業務と並行して、世界モデルや強化学習などの学習・実装も継続してきました。

## 現在の研究・開発

2026年に**株式会社中央エンジニアリング**へ入社しました。現在取り組んでいる研究・開発と、継続して調査・検証しているテーマを以下にまとめています。

### 強化学習による制御・シミュレーション

シミュレーション上での制御方策の学習と、学習の安定性・評価方法を検討しています。

- PPOや再帰型方策による連続制御
- 行動模倣（Behavior Cloning）から強化学習への移行
- Python・C++・ROS2・JSBSimを用いた実験環境の構築
- マルチエージェントの学習・協調

### 世界モデル・ロボット学習

大学院での研究を出発点に、知覚・目標・行動を学習モデルでつなぐ方法を検討しています。

- 世界モデルと予測に基づく表現学習
- 画像と言語を組み合わせた目標表現
- ロボットアームの模倣学習
- Action Chunking・Flow Matchingなどの行動生成手法の調査・検証

### 3D点群の意味理解・地形抽出

森林などの点群から、地形の把握や図面作成に必要な情報を取り出す処理を研究・開発しています。

- OpenScene系の蒸留特徴とCLIPによる、テキストに基づく点群分類
- 地表面・低草・樹木などの識別と地表面の抽出
- 地表面抽出からTIN・DEM・等高線生成までの処理
- 公開済みモデルの評価と、対象環境に適応させるための課題整理

## 継続的な研究実装・オープンソース

### PixyzRL：確率的生成モデルに基づく強化学習フレームワーク

[**PixyzRL**](https://github.com/ItoMasaki/PixyzRL) は、確率的生成モデルライブラリPixyzを基盤とする強化学習フレームワークです。モデルや損失関数を組み合わせ、強化学習の実験を組み立てやすい実装を目指しています。

<p align="center">
  <img src="https://github.com/user-attachments/assets/577b9d4b-30d0-493d-95fc-b83a2f292c28" alt="PixyzRLのプロジェクトロゴ" width="360">
</p>

- PPO・A2C・SACの実装
- Replay Buffer・Rollout Bufferなどの学習用データ管理
- Gymnasium環境との連携
- 学習・評価・ログ記録のためのユーティリティ

### 公開リポジトリ一覧

| リポジトリ | テーマ |
| :--- | :--- |
| [**NewtonianVAE**](https://github.com/ItoMasaki/NewtonianVAE) | 物理的な潜在表現の学習と画像に基づく制御 |
| [**ROS2Docker**](https://github.com/ItoMasaki/ROS2Docker) | 再現性のあるROS2開発環境 |
| [**PixyzRL**](https://github.com/ItoMasaki/PixyzRL) | 確率的生成モデルを基盤とする強化学習 |

## 技術・開発環境

| 分野 | 技術・ツール |
| :--- | :--- |
| 言語 | Python・C++・Shell |
| 機械学習 | PyTorch・Pixyz・強化学習・世界モデル・模倣学習 |
| ロボティクス・シミュレーション | ROS2・Gymnasium・JSBSim |
| 3D認識 | 点群セグメンテーション・OpenScene・CLIP・地形処理 |
| 開発基盤 | Docker・Azure・学習パイプライン・実験評価 |

## 連絡先

公開しているコードや活動は [GitHub / ItoMasaki](https://github.com/ItoMasaki) からご覧いただけます。
