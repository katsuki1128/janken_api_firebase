# じゃんけんfirebase_chatGPT気合いAPI

## DEMO

  - デプロイしている場合はURLを記入（任意）

## 紹介と使い方

  - じゃんけんの勝率をfirebaseに保存
  - コンピューターが出す手はランダム、勝ち負けを判断
  - 勝率はfirebaseから引っ張ってきている
  - 勝率を見て次に出す手を強戦国武将風に強引にchatGPTに答えさせている

## 工夫した点

  - 勉強中なのでjQueryは使わずjavascriptで実装
  - 機能はシンプルに

## 苦戦した点

  - firebaseとの連携がなかなかできず、結果updateDocはtype="module"のスコープの問題だったことが判明した

## 参考にした web サイトなど

  - https://firebase.google.com/docs?hl=ja