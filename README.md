# GitHubについて

最近ソースコードの流出等で、「GitHub」を耳にするの増えてくるも。プログラマーじゃないけど、GitHubについて理解できるのか。

## 0. 概要

1. [バージョン管理システム](#1-vcs)
2. [Gitとは](#2-git)
   1. [Repository](#i-repository)
   2. [Commit](#ii-commit)
   3. [Branch](#iii-branch)
   4. [Tag](#iv-tag)
3. [GitHubとは](#3-github)
   1. [Issue](#i-issue)
   2. [Pull request](#ii-pull-request)
      1. [Review](#a-review)

## 1. VCS バージョン管理システム

バージョン管理及びバージョン履歴はソースコードだけでなく、Excel、PowerPoint、Word等のファイルバージョンも利用される場面が多々ある。

![Sheets Version History](img/sheets-version-history.png)

[Git](https://ja.wikipedia.org/wiki/Git)はバージョン管理ソフトウェアの一つ。Gitの他にもMercurialがあるが、対応してたBitbucketが2020年7月からサポート終了との発表があった。更に前では、SVN（Subversion）が一般的に利用されていた。現在はほぼGitの1択になっている。

## 2. Gitとは

Linuxカーネルを開発されたリーナス・トーバルズ氏が、Linuxカーネルの開発のために作ったバージョン管理システムである。

### i. Repository (リポジトリ)

Gitのバージョン管理対象にする**フォルダー**を指す。

### ii. Commit (コミット)

リポジトリ内で、記録している修正を指す。

複数ファイル、フォルダーの修正を記録させることもできる。

### iii. Branch (ブランチ)

1つのコミットに向かせる事ができる。

### iv. Tag (タグ)

ブランチとほぼ一緒が、ブランチの場合、コミットを追加することができ、タグはコミットを追加することができない。

1つのコミットに向かせて、固定すること。その向きは変更できない。

## 3. GitHubとは

Gitのバージョン管理ソフトを使って、サービスとして提供しているプラットフォーム。

Gitだけでは、自分の端末内のみで機能して、別で公開されない限り、他の人に共有することができない。GitHubがGitで管理したプロジェクトを簡単に公開することができるようにされている。

Linuxカーネルのリポジトリは[git.kernel.org](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/)に公開されている。Gitが出てくる前は、FTPサーバとPatchファイルで管理されていたと言われている。

Gitではないが、コミュニケーション取りやすくするために、GitHubが提供している機能も。

### i. Issue (イシュー)

### ii. Pull request (プルリクエスト)

#### a. Review (レビュー)
