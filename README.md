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

## Github Projects
### Github Project連携方法
issueが作成されたときに自動でProjectに紐づける方法

1. Projectの右上にある・・・(view more options)を押下
2. Workflowsを押下
3. Default workflowsの「Auto-add to project」を選択
4. filterに条件を入れる
5. workflowを有効化する
