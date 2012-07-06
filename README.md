# Sapporo RubyKaigi 2012 Call For Lightning Talks

## English

At [Sapporo RubyKaigi 2012][sprk2012], we will be using the same style for
submitting lightning talk proposals as [full presentation proposals][sprk2012cfp] and [EuRuKo2012][euruko2012].
We are reusing the text from EuRuKo2012 for the English instructions.
Thanks for providing us a great reference.
Please refer to the instructions below, and send us a pull request if you want to apply.

* Every talk is exactly 5 minute long.
* Lightning talks will be held on Saturday, September 15.
* __Lightning talk speakers must [have a ticket for Sapporo RubyKaigi 2012][ticket], unlike full-presentation speakers. If you don't already have a ticket, you cannot submit the proposal.__
* Write lightning talks proposals as a [YAML][yaml] document. Please check if the file is valid before submitting. ```ruby -ryaml -rpp -e "pp YAML.load_file('proposal.yml')"``` will help you (and us).

For the comment in the pull request, write whatever you would like.

By submitting a proposal, you give permission to Sapporo RubyKaigi 2012 to record, edit, and publish audio and/or video of your presentation. If you do not wish to abide these conditions, please refrain from submitting a proposal.

1. Fork this repository
2. Copy the sample folder `example/` to `your_name-talk_name`
3. Edit the `your_name-talk_name/proposal.yml` file and type a good description about your talk and about yourself
4. Create a pull request of your fork

You can add any type of assets to support your proposal inside your folder. When a talk gets accepted we will press the lovely green merge button.

## 日本語

[札幌Ruby会議2012][sprk2012] では、[一般発表][sprk2012cfp] と同様、[EuRuKo 2012 style][euruko2012] でライトニングトークを募集します。
応募される方は、以下の要領で GitHub の pull request をお送りください。

* 発表時間は5分間です。
* ライトニングトークは9月15日(土)に実施します。
* __ライトニングトーク発表者は一般発表者と異なり [チケットの購入][ticket] が必要です。応募はチケットを入手済みの方に限ります。__
* ライトニングトークの proposal は [YAML][yaml] ドキュメントとして記述をお願いします。提出前にファイルが valid であることをご確認ください。```ruby -ryaml -rpp -e "pp YAML.load_file('proposal.yml')"``` がお役に立ちます。

発表に応募すると、講演の写真撮影、動画の中継、録画の配信に同意したものと見なします。同意されない方のご応募はご遠慮下さい。

1. このリポジトリを fork してください。
2. `example/` にある例を `[あなたの名前]-[発表のタイトル]` （半角英数）という名前のディレクトリにコピーしてください。
3. `[あなたの名前]-[発表のタイトル]/proposal.yml` を編集し、プレゼンテーションとあなたのプロフィールについて記載してください。
4. pull request を送ってください。

必要な資料等があれば、あなたのフォルダの中に配置してください。
あなたの発表が採択された場合は、ブランチをマージします。

pull request へのコメントもご自由に行ってください。

  [sprk2012]: http://sapporo.rubykaigi.org/2012
  [euruko2012]: https://github.com/euruko2012/call-for-proposals
  [sprk2012cfp]: https://github.com/sprk2012/sprk2012-cfp
  [ticket]: http://sapporo-rubykaigi.doorkeeper.jp/events/1441
  [yaml]: http://yaml.org/
