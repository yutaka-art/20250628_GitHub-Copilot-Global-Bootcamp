<header>

# GitHub Codespaces 入門

GitHub Codespaces の世界へようこそ──クラウドベースのコーディングへのゲートウェイです。このモジュールでは、瞬時に起動するクラウドホスト型開発環境の革新的な力を探り、コーディングのアプローチを一新します。GitHub Codespaces は、必要な言語・ツール・ユーティリティをすべて備えたコンテナを提供し、シームレスかつ統合された開発体験を実現します。

学習を進めながら、Codespaces のライフサイクル全体を理解し、好みや要件に合わせて環境をカスタマイズする方法を身につけます。理解を深めるために、モジュールの最後には GitHub Codespaces 環境でスキルを実践的に試すハンズオン演習が用意されています。

インターネット接続さえあればどのコンピューターからでもアクセスできる、完全に構成された開発環境を想像してみてください。GitHub Codespaces を使えば、協調的で柔軟な新しいコーディング時代を切り開けます。さあ、一緒にクラウドベース開発の可能性を最大限に引き出しましょう!

</header>

- **対象者**: 開発者、DevOps エンジニア、エンジニアリング マネージャー、プロダクト マネージャー  
- **学べること**: Codespace の作成、Codespace からのコードのプッシュ、カスタム イメージの選択、Codespace のカスタマイズ  
- **作成するもの**: `devcontainer.json` を含む Codespace と各種カスタマイズ・パーソナライズ設定  
- **前提知識**:  
  - Visual Studio Code の利用経験 — [Visual Studio Code Docs](https://code.visualstudio.com/docs)  
  - GitHub の基本操作、または前モジュール [GitHub 入門](https://github.com/WirelessLife/Mastering-GitHub-Copilot-for-Paired-Programming/blob/main/01-Introduction-to-GitHub/README.md?WT.mc_id=academic-113596-abartolo) の修了  
- **所要時間**: 1 時間以内で完了可能  

このモジュールを終えると、次のことができるようになります。

1. GitHub Codespaces を説明できる  
2. GitHub Codespaces のライフサイクルを理解し、各ステップを実行できる  
3. GitHub Codespaces で設定可能なカスタマイズ項目を説明できる  

## 事前学習資料  

- [GitHub Codespaces でコーディングする](https://learn.microsoft.com/training/modules/code-with-github-codespaces/?WT.mc_id=academic-113596-abartolo)  
- 「What is GitHub Codespaces?」(以下の動画プレイリスト)  
- [![What is Codespaces](https://img.youtube.com/vi/ozuDPmcC1io/0.jpg)](https://www.youtube.com/watch?v=ozuDPmcC1io&list=PLmsFUfdnGr3wTl-NCblzcrEv2lFSX975-)  

### コースの始め方

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'code-with-codespaces',
  owner: '@me',
  name: 'skills-code-with-codespaces',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=yutaka-art&template_name=code-with-codespaces&owner=%40me&name=skills-code-with-codespaces&description=My+clone+repository&visibility=public)

1. **Start course** を右クリックし、新しいタブで開きます。  
2. 新しいタブでは、ほとんどの入力欄が自動で入力されます。  
   - **Owner** に、個人アカウントまたはリポジトリをホストする組織を選択します。  
   - パブリック リポジトリの作成を推奨します。プライベート リポジトリでは [GitHub Actions の実行分課金](https://docs.github.com/ja/billing/managing-billing-for-github-actions/about-billing-for-github-actions?WT.mc_id=academic-113596-abartolo) が発生するためです。  
   - フォーム最下部の **Create repository** ボタンをクリックします。  
3. リポジトリが作成されたら約 20 秒待ち、ページをリロードして README に記載された手順に従ってください。  

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

ヘルプ: [ディスカッションボードに投稿](https://github.com/orgs/skills/discussions/categories/introduction-to-github) &bull; [GitHub ステータスページを確認](https://www.githubstatus.com/)
