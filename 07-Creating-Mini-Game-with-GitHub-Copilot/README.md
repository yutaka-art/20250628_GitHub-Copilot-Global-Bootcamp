<header>

# GitHub Copilot でミニゲームを作ろう

このモジュールでは、GitHub Copilot を使って「じゃんけん」ミニゲームを作成する方法を学びます。このハンズオンプロジェクトは、プログラミングスキルを磨き、Python でのコンソールアプリ開発力を高めることを目的としています。開発環境のセットアップは不要で、GitHub Codespaces を利用します。AIペアプログラマーである GitHub Copilot と一緒に、アプリケーション作成に集中しながら効率的にコーディングしましょう。さあ始めましょう。

</header>

- **対象者**: 開発者、DevOps エンジニア、ソフトウェア開発マネージャー、テスター
- **学べること**: GitHub Copilot を活用したコード生成やコメント追加
- **作成物**: Copilot AI によるコードやコメント提案が含まれる Python ファイル
- **前提条件**: GitHub Copilot は無料で利用できます。 [GitHub Copilot にサインアップ](https://gh.io/copilot)
- **所要時間**: 1時間以内で完了します

このモジュールを終えると、次のスキルが身につきます：

- 開発環境として GitHub Codespaces を体験できる
- Python コンソールアプリで入出力処理を実装できる
- GitHub Copilot をアシスタントとして活用できる

## 事前学習
- [GitHub Copilot で始めるプロンプトエンジニアリング入門](https://learn.microsoft.com/training/modules/introduction-prompt-engineering-with-github-copilot//?WT.mc_id=academic-113596-abartolo)
- [チャレンジプロジェクト - GitHub Copilot と Python でミニゲームを作ろう](https://learn.microsoft.com/training/modules/challenge-project-create-mini-game-with-copilot/?WT.mc_id=academic-113596-abartolo)
- Learn Live: GitHub Copilot でミニゲームコンソールアプリを作成（下記動画）
- [![Learn Live: Build a minigame console app with GitHub Copilot](https://i.ytimg.com/vi/Fi_jl3G7i8Y/maxresdefault.jpg)](https://youtu.be/Fi_jl3G7i8Y?si=v56VPYfTHYBBEX11)
  （上の画像をクリックするとレッスン動画が見られます）

## 必要なもの

- [GitHub Copilot サービスを有効化](https://github.com/github-copilot/signup)

## 💪🏽 演習

**「Open in GitHub Codespaces」ボタンを右クリックして、新しいタブで Codespace を開いてください**
 
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/microsoft/Mastering-GitHub-Copilot-for-Paired-Programming)

すでに GitHub Codespaces と GitHub Copilot の基本的な使い方は学びました。このチャレンジ演習では、GitHub Copilot を使って Python でミニゲームを作成することが目標です。

#### GitHub Codespace の動作確認

1. Codespaces にアクセスし、Visual Studio Code で *app.py* という新しいファイルを作成します。

   **注意:** Python 拡張機能がインストールされていない場合は、インストールが必要です。

2. 次のコメントを入力します。

   ```python
   # write 'hello world' to the console
   ```

3. GitHub Copilot がコードを自動補完し、次のような結果を提案します。

   ```python
   # write 'hello world' to the console
   print('hello world')
   ```

4. ターミナルで *python app.py* コマンドを実行し、次のようなメッセージが表示されるか確認します。

   ```bash
   hello world
   ```

### ゲームロジックの作成

Codespaces と GitHub Copilot の動作確認ができたら、次は Copilot の助けを借りて Python でミニゲームのロジックを作成しましょう。仕様は以下の通りです。

ゲームの勝敗は次の3つのルールで決まります：

- **グー**はチョキに勝つ
- **チョキ**はパーに勝つ
- **パー**はグーに勝つ

#### ゲームのインタラクションについて

コンピューターが対戦相手となり、**グー**、**チョキ**、**パー**のいずれかをランダムに選びます。ゲームのやりとりはコンソール（ターミナル）で行います。

- プレイヤーは「グー」「チョキ」「パー」のいずれかを選択でき、無効な選択をした場合は警告されます。
- 各ラウンドでプレイヤーは選択肢を入力し、勝敗または引き分けが通知されます。
- 各ラウンド終了後、続けてプレイするか選択できます。
- ゲーム終了時にプレイヤーのスコアを表示します。
- ミニゲームはユーザー入力を小文字に変換し、無効な選択肢の場合は通知します。

GitHub Codespaces で、Copilot が理解しやすいコメントやプロンプトを活用しながらミニゲームを作成してください。Copilot はコメントから文脈を把握し、役立つ提案を行います。

#### 動作確認

1. *python app.py* コマンドでミニゲームを実行します。
2. プロンプトで *rock*、*paper*、*scissors* のいずれかを入力します。
3. 勝敗または引き分けが通知されることを確認します。
4. 続けてプレイするか選択します。
5. プロンプトで *screen* を入力します。
6. 無効な選択肢の場合、警告が表示されることを確認します。
7. 2と4を繰り返し、数回プレイした後、終了を選択します。
8. ゲーム終了時にスコア（勝利数とラウンド数）が表示されることを確認します。

お疲れさまでした！GitHub Copilot を使って Python コンソールミニゲームを作成できました。
