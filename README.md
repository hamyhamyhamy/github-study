## にゃーん


## GitHubの使い方

今日ご説明するもの

- GitとGitHub
- ブランチ
- プルリク
- マージ

## カンタンにGitHubの説明

- Gitというバージョン管理の仕組み
- GitHubはそれの管理をするWebサービス

GitとGitHubは同じものじゃないよ

## 動画とYouTubeは同じものじゃないよ

- 動画は再生するもの
- プレイリストとか検索とか、より動画を扱いやすくするのがYouTube

## GitとGitHubは同じものじゃないよ

- Gitはバージョン管理の仕組み
- プルリクとかイシューとか、よりGitを扱いやすくするのがGitHub
  - プルリクについては後述

## で、Gitって？
- バージョン管理システム
  - 色々出来る編集履歴、という概念
  - 最悪の場合、先祖返りさせる仕組み
  - CMSでいうとリビジョンに近い
    - Googleドキュメントにも編集履歴ある
  - テキストの進化の歴史を作るもの

## バージョン管理出来るもの

- HTML/CSSもテキスト
- プログラムもテキストの仲間
- 画像もOK

## Gitならでは

単純な編集履歴だけでなく、枝分かれができる  

参考: http://k.swd.cc/learnGitBranching-ja/?demo


## 作業内容が枝分かれ

 - Aさんが文章の校閲
 - Bさんが背景色を青にする
 - 普通のテキスト編集だと、Aさんの作業後にBさんの作業をまるごと全部上書きするとNG
 - 2人の作業順を決めて、最新のテキストをお渡しして...と面倒くさい

## ブランチを生やす
- Gitなら、枝分かれ前の部分からの差分だけを見て、あとで再統合できる
 - Aさんが *「fix/typo」ブランチで* 文章の校閲
 - Bさんが *「renewal/bg-blue」ブランチで* 背景色を青にする
 - これ統合しちゃって良いよね？という確認を取る
  - これが「プルリクエスト」
 - 実際にブランチを統合する
  - これが「マージ」

## プルリクエスト

- 統合前にファイルの差分をチェック出来る
- よくプルリクって言ってるやつ
- 実はGitHub上の方言
  - GitHubに似たGitLabというサービスだと「マージリクエスト」

## さぁ手を動かそう

- 慣れればマウスぽちぽち
- デスクトップアプリもあるが、今回はスキップ
  - 大量のファイルを扱うとかならデスクトップアプリでも良いかも
  - でも起動する度に毎回のデータを取ってくるのが面倒くさい

## GitHub実践

時間次第で
