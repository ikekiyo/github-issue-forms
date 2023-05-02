# github-issue-forms

GitHub issue forms の使い方とテンプレート集

## 使い方

issue 作成ページから対象の issue 種別を選択する

https://github.com/ikekiyo/github-issue-forms/issues/new/choose

## テンプレートの作成方法

1. .github/ISSUE_TEMPLATE に yaml ファイルを作成する
2. テンプレートのヘッダーを記載する

```yaml
name: 不具合報告
description: 不具合の報告
title: "🐛 Bug: "
labels: ["bug"]
assignees:
  - octocat
```

3. テンプレートの body を記載する
   書き方は公式ドキュメントを参照

   https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms
