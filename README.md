# ゲームプログラミング1年(2025年度入学生)

- [シラバス](https://github.com/datgm25/gp1/blob/main/gp1_2025_syllabus.pdf)
- [Google Meet](https://meet.google.com/bwb-njcm-udh)
- [講義日程](fri.md)
- [URLなどの報告](https://docs.google.com/forms/d/e/1FAIpQLSfXGJvYbiwt1qQLB5GhHJJFp_NxH939IvLUvGuzuWzW6WgUvQ/viewform?usp=dialog)
- [Slack](https://datgm25.slack.com)
- その他
  - [書く教科書の作例](https://github.com/datgm25/csharp-manual)
  - [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)

## 5回目(5/23)

### 話題

- [技術書典18](https://techbookfest.org/)
  - [技術書典. アミューズワンギャラリー](https://techbookfest.org/organization/bgzSCidTdQc0gKCVvM3Ghe)

### 復習問題
「書く教科書」とGitHubの使い方のドキュメントを参照して、以下の手順に従ってVisual C#プロジェクトを作成して、GitHubで公開せよ。

※自分で作成した書く教科書がない場合は[こちら](https://github.com/datgm25/csharp-manual)を参照する。

1. Visual C#の新規プロジェクトを作成して、名前を`fukuv0523`にする
1. GitHubにPublishする
   - 参考 [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
1. フォームに以下のコントロールを作る
   - ラベル(Label)を1つ作って、フォームの中央辺りに置く
   - タイマー(Timer)を1つ作って、有効にする
5. timer1のプログラムに、label1.Leftに10を足す処理を実装する
6. ラベルをクリックしたら、タイマーを止めて、ラベルに自分の氏名を表示する
7. すべて保存して、GitHubに反映させる
   - 参考 [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)

#### おまけ
上記ができて時間が余った人は、以下のようなことにも取り組んでみよう。成果物はGitHubでPushすれば更新される。

- ボタンを1つ作って、クリックしたら、タイマーが有効になるようにする
- 動くたびに、ラベルの表示を変化させる
- その他、思いついたことを試す

### 予定

- 書く教科書の続き
  - 変数の演習7-1から

## 4回目(5/16)

### 復習問題

「書く教科書」とGitHubの使い方のドキュメントを参照して、以下の手順に従ってVisual C#プロジェクトを作成して、GitHubで公開せよ。

※自分で作成した書く教科書がない場合は[こちら](https://github.com/datgm25/csharp-manual)を参照する。

1. Visual C#の新規プロジェクトを作成して、名前を`fukuv0516b`にする
1. GitHubにPublishする
   - 参考 [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
1. フォームに以下のコントロールを作る
   - ラベル(Label)を1つ
   - ボタン(Button)を4つ作って十字に配置
1. ボタンを押した方向に、ラベルを`20`ピクセル移動させる処理を、各ボタンに実装する
2. ラベルをクリックしたら、ラベルに自分の氏名を表示して、ラベルの文字の色を変える。色は黒以外ならなんでもよい
1. すべて保存して、GitHubに反映させる
   - 参考 [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)

![画面例](https://raw.githubusercontent.com/datgm21/gp1/main/image.png)

#### おまけ
上記ができて時間が余った人は、以下のようなことにも取り組んでみよう。成果物はGitHubでPushすれば更新される。

- 動く方向に応じて、ラベルの表示を変化させる
- 動く方向に応じて、ラベルの色を変える
- その他、思いついたことを試す

### 内容

- 書く教科書の続き
  - 計算の続きから


## 3回目(5/9)

### 復習問題

- githubと、googleにログイン
- Slackを開く
  - [招待](https://join.slack.com/t/datgm25/shared_invite/zt-3540jv6nq-4~Q4GvhGrr3Rohnmxq9S0g)
- 指示を待つ

前回作成した「書く教科書」を参照して、以下の手順に従ってVisusl C#プロジェクトを作成して、Visual StudioのスクリーンショットをSlackに貼り付けよ。

※自分で作成した書く教科書がない場合は[こちら](https://github.com/datgm25/csharp-manual/blob/master/01.md)を参照する。

1. 書く教科書の手順に従ってVisual Studioを起動する
1. 新しいC#のプロジェクトを`fukuv0509`という名前で作成する
1. ボタンを2つ置く
1. 1つ目のボタンを押したら、自分の氏名をメッセージボックスで表示
1. 2つ目のボタンを押したら、モニターのシールに`A601-00`というように書かれている文字列を、メッセージボックスで表示

完成したら、以下の要領で、Slackに貼り付けて送信する。

1. [Slack](https://datgm25.slack.com)を開いて、Googleアカウントでログインする
2. プログラムを開始して、1つ目のボタンを押して、メッセージを表示する
3. C#のプログラムが見えるように、メッセージを移動させて、画面のスクリーンショットを撮ってSlackの自分のチャンネルに貼り付ける
4. 2つ目のボタンも同様にスクリーンショットを撮って、Slackに貼り付けて送信する

#### スクリーンショットの撮り方

1. Windowsキー + Shiftキー + Sキーを押してスクリーンショットメニューを表示して、切り取りモードで、**全画面表示**を選択
3. Slackの「#times_自分の名前」を選択する
4. 送信欄をクリックして選択して、Ctrlキー + Vキーで貼り付ける
5. メッセージを送信する

### 内容

- 書く教科書01の復習
  - [書く教科書の作例](https://github.com/datgm25/csharp-manual)
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- 書く教科書の続き
  - プロパティ(Property)～性質、属性～から


## 2回目(4/25)

### 内容

- [unity1week online共有会 #15. Yamasho: 備忘録のススメ](https://www.youtube.com/watch?v=wmF1z5Epr1g&t=2825s)
- 書く教科書
  - 目的
    - あとで自習するための手順を残すこと
    - 習ったことを質問せずに済むようにすること
  - 要点
    - 教員のメモを写す必要はない
    - わかりきっていることは省略してよいし、教員の説明がわかりにくければ自分流に書けばよい
    - 入力例は後ほど公開するので、間に合わなくても気にせずに講義が進みはじめたら講義に集中する
  - 基本操作 / 問題の解消


## 1回目(4/18)

- ガイダンス
  - [プログラミングを学ぶ前に](https://docs.google.com/presentation/d/1mIIrnua1nf2yCiXA6KMkTUOylzPIxiUCeqQEdtHdPhc/)
  - GmailアカウントとGitHubアカウントを作成していない場合は[こちら](https://docs.google.com/document/d/16MW6maMYvt8m-60RM5wU_LzJ5r-3Hm0WTnxoBGDzxIA/)
- [講義メモ](https://docs.google.com/document/d/1BbWuFoV26oZf1qLmnwidejBkR6Wyr6i_lp5TVBzEf5s/)
  - Visual C# / Unity
