<header>

# GitHub Copilot 入門

この学習モジュールでは、規模に応じて動作する初の AI 開発者ツールである GitHub Copilot を使用する利点を探ります。Copilot はテスト、リファクタリング、説明、コード提案などのタスクを支援し、コーディング体験を向上させます。

GitHub Copilot は AI を活用したコーディング アシスタントであり、より少ない労力で素早くコードを書くことを支援し、問題解決やコラボレーションにより多くの時間とエネルギーを割けるようにします。

モジュールの終わりには、GitHub Copilot の概要とその利点を説明できるようになるだけでなく、個人および企業向けの提供形態を理解できます。また、GitHub Copilot の将来について洞察を得て、Visual Studio Code での実践演習を通じて Copilot の活用方法を習得します。

Copilot を活用することで、開発者は生産性を向上させ、ソフトウェア開発を加速させています。さらに詳しくは GitHub Blog の記事「Research: [Quantifying GitHub Copilot’s Impact on Developer Productivity and Happiness](https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness)」をご覧ください。

**注意:** このモジュールでは [Codespaces](https://github.com/codespaces) を使用していますが、GitHub Copilot は Visual Studio Code など他の環境でも使用できます。

</header>

- **対象者**: 開発者、DevOps エンジニア、ソフトウェア開発マネージャー、テスター  
- **学べること**: Codespace への Copilot インストール、コード提案の受け入れ、コメントからの提案の受け入れ  
- **作成するもの**: Copilot AI によるコード・コメント提案が反映された JavaScript ファイル  
- **前提条件**: GitHub Copilot は無料で利用できます。こちらから登録してください → [GitHub Copilot](https://gh.io/copilot)  
- **所要時間**: 1 時間以内で完了可能  

このモジュールを終えると、次のことができるようになります。

- GitHub Copilot が何か、そしてその利点を説明できる  
- 個人および企業向けに提供される GitHub Copilot の利用形態を理解できる  
- GitHub Copilot の今後について説明できる  
- GitHub Copilot の導入と一般的な設定方法を学べる  
- Visual Studio Code で GitHub Copilot を使用して開発できる  

## 事前学習資料
- [Introduction to GitHub Copilot](https://learn.microsoft.com/en-us/training/modules/introduction-to-github-copilot/?WT.mc_id=academic-113596-abartolo)  
- 「What is GitHub Copilot?」(下記動画プレイリスト)  
- [![What is GitHub Copilot](https://img.youtube.com/vi/QG1E0SCqqW8/0.jpg)](https://learn.microsoft.com/shows/introduction-to-github-copilot/what-is-github-copilot-1-of-6/?WT.mc_id=academic-113596-abartolo)  

### コースの始め方

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'copilot-codespaces-vscode',
  owner: '@me',
  name: 'skills-copilot-codespaces-vscode',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=yutaka-art&template_name=getting-started-with-github-copilot&owner=%40me&name=skills-getting-started-with-github-copilot&description=Exercise:+Get+started+using+GitHub+Copilot&visibility=public)

1. **Start course** を右クリックして新しいタブで開きます。  
2. 新しいタブでは、ほとんどの入力項目が自動で入力されます。  
   - **Owner** には個人アカウントまたはリポジトリをホストする組織を選択します。  
   - パブリック リポジトリの作成を推奨します。プライベート リポジトリでは [GitHub Actions の実行分課金](https://docs.github.com/ja/billing/managing-billing-for-github-actions/about-billing-for-github-actions) が発生するためです。  
   - フォーム最下部の **Create repository** ボタンをクリックします。  
3. リポジトリが作成されたら約 20 秒待ち、ページをリロードして README に記載された手順に従ってください。  

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

ヘルプ: [ディスカッションボードに投稿](https://github.com/orgs/skills/discussions/categories/code-with-copilot) &bull; [GitHub ステータスページを確認](https://www.githubstatus.com/)
