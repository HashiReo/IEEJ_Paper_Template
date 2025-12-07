# 修士論文 (Master Thesis)

## 最新版ダウンロード
[![Build Thesis PDF](https://github.com/HashiReo/master-thesis/actions/workflows/build.yml/badge.svg)](https://github.com/HashiReo/master-thesis/actions/workflows/build.yml)

[📥 最新のPDFをダウンロード (main.pdf)](https://github.com/HashiReo/master-thesis/releases/download/latest/main.pdf)

## 概要
極値統計を用いた電力需要の確率的予測および需要削減手法の開発に関する研究です。

## 著者
Reo Hashiba

# このテンプレートの使いかた
このリポジトリと同じ設定(Docker + Vs code + GitHub Actions)で修士論文執筆環境を構築する手順です。

## ！注意！
- このリポジトリを Clone しないでください。
- 必ず **[Use this template]** ボタンから自分のリポジトリを作成して作業してください。
- 直接このリポジトリの Clone と Push をしないでください。


## 1. 前提条件
以下のソフトウェアをインストールしておいてください。
- [Docker Desktop](https://www.docker.com/ja-jp/get-started/)
- [Visual Studio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code)
- Vs Code 拡張機能: [Dev Containers]
- Vs Code 拡張機能: スマートグリッド研究室のWikiを参考に拡張機能を入れておいてください

## 2. リポジトリの作成
1. このリポジトリのページ上部にある **[Use this template]** をクリックし、 **[Create a new repository]** を選択します。
2. 自分のGitHubアカウントに新しいリポジトリを作成します。(ex: "my-thesis")。

## 3. 環境の起動
1. Vs Codeを開いて、「ctrl + shift + p」 を押してコマンドパレットを開きます。
2. **[Dev Containers: Clone Repository in Container Volume]** を選択します。
3. 作成したリポジトリを選択してください(ここでもし、「sign in to GitHub」と出たらサインインして許可してください)
4. [select a branch...]と聞かれたら、"main"を選択してください。
5. しばらく時間をおいて修士論文執筆用の環境が作られ、執筆に移れます。
6. エラーが出たら ChatGPT or Gemini に聞いてください。
