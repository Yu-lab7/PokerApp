# PokerApp

## 概要
このアプリはポーカーを遊ぶことができます。

## インストール方法

1. **リポジトリのクローン**
   ```bash
   git clone https://github.com/Yu-lab7/PokerApp
   cd PokerApp

2. **実行**
   ```bash
   python app.py

## 使い方

1. **起動**

プログラムを実行すると、ウィンドウに「Python Poker Parlor」と書かれたバナーやメッセージが表示される。

2. **ゲームの流れ**

プレイヤーの所持金は最初に$100。ゲームをプレイするたびに10ドルが引かれ、スコアに応じた報酬を獲得できる。

3. **ボタンの操作**

画面には次のボタンが表示される:
Roll Dice: ダイスを振る
Die 1 ~ Die 5: 個別のダイスを選択し、保持や再振りを指定
Score: 現在のスコアを確認
Quit: ゲームを終了し、ウィンドウを閉じる

4. **ダイスの振り直し**

各ラウンドで最大3回までダイスを振ることができ、選択したダイスだけを再度振ることが可能。
ダイスを選択するには Die 1 ～ Die 5 ボタンをクリック。色が変われば選択済み。
Roll Dice ボタンをクリックすると、選択したダイスが再度振られる。

5. **スコアの確認**

3回の振り直し後、または Score ボタンをクリックすると、そのラウンドのスコアが表示される。役に応じて得られるスコアが異なる。

6. **ゲームの終了**

所持金が10ドル未満になるか、Quit ボタンをクリックすると、ゲーム終了。ウィンドウが閉じられる。
