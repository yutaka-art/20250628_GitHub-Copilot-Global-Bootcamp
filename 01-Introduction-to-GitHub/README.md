<header>

# GitHub 入門

このラーニングモジュールでは、AI を搭載した一流の開発プラットフォームである GitHub の基本を掘り下げます。GitHub は共同ソフトウェア開発を促進するプラットフォームです。本モジュールは、新人開発者、GitHub 初心者、学生を対象とし、実際の GitHub リポジトリを操作しながら主要機能を総合的に学べるハンズオン形式になっています。

人々は GitHub を毎日利用して、最先端のテクノロジーを生み出しています。データを可視化したり、新しいゲームを作ったり──GitHub にはそれをさらに効率よく実現できるコミュニティとツールがそろっています。

</header>

- **対象者**: 新人開発者、GitHub を初めて使う方、学生
- **学べること**: リポジトリ、ブランチ、コミット、プルリクエストを紹介します
- **作成するもの**: [プロフィール README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme) として使える短い Markdown ファイル
- **前提条件**: なし。GitHub 初日の導入として最適です
- **所要時間**: 1 時間以内で完了します

このモジュールで学べること:

1. GitHub の主要機能を把握する  
2. リポジトリ管理のベストプラクティスを習得する  
3. ブランチ、コミット、プルリクエストを含む GitHub フローを理解する  
4. Issue や Discussions を通じた GitHub の共同作業機能を体験する  
5. 通知やサブスクリプションを管理する方法を学ぶ  

## 事前学習資料

- [Introduction to GitHub](https://learn.microsoft.com/training/modules/introduction-to-github/?WT.mc_id=academic-113596-abartolo)
- 「What is GitHub?」(以下の動画)

[![What is GitHub](https://img.youtube.com/vi/pBy1zgt0XPc/0.jpg)](https://www.youtube.com/watch?v=pBy1zgt0XPc)

### このコースの始め方

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'introduction-to-github',
  owner: '@me',
  name: 'skills-introduction-to-github',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=yutaka-art&template_name=introduction-to-github&owner=%40me&name=skills-introduction-to-github&description=My+clone+repository&visibility=public)

1. **Start course** を右クリックし、新しいタブで開きます。  
2. 新しいタブでは、ほとんどの入力項目が自動で埋まります。  
   - **Owner** には個人アカウントまたはリポジトリをホストする組織を選択します。  
   - パブリックリポジトリの作成を推奨します。プライベートリポジトリでは [GitHub Actions の実行分課金](https://docs.github.com/ja/billing/managing-billing-for-github-actions/about-billing-for-github-actions?WT.mc_id=academic-113596-abartolo) が発生するためです。  
   - フォーム最下部の **Create repository** ボタンをクリックしてください。  
3. 新しいリポジトリが作成されたら約 20 秒待ち、ページをリフレッシュします。新しいリポジトリの README に記載された手順に従って進めてください。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

ヘルプ: [ディスカッションボードに投稿](https://github.com/orgs/skills/discussions/categories/introduction-to-github) &bull; [GitHub ステータスページを確認](https://www.githubstatus.com/)
