Jay: 

こんにちは、マサさん。

Hi, Masa.

---

Masa: 

やあ、ジェイ。聞こえますか。

Hi, Jay. Can you hear me?

---

Jay: 

はい、とても良く聞こえますよ。私のパソコンの画面は見えますか？

I can hear you very well. Can you see my screen?

---

Masa:

はい、見えますよ。

Yes, I can.

---

Jay:

よかった。こちらではクムドさんが同席しています。

Good! OK, I have Kumud with me here.

---

Kumud:

こんにちは。

Hi.

---

Masa:

クムドさん、こんにちは。

Hi, Kumud.

---

Jay:

まだチェンさんが来ていませんね。まもなく来ると思うんですが…あっ、チェンさんです。こんにちは、チェンさん。

We're still waiting for Cheng. I hope he'll join the call soon... Oh, there he is. Hi Cheng.

---

Cheng:

皆さんこんにちは。すみません、前のミーティングがずれこんでしまったのです。

Hi all. Sorry, my previous meeting ran late.

---

Jay:

大丈夫ですよ。これで皆さん揃いましたね。

That's OK. We have everybody now.

---

Jay:

日本語の問題に入る前に、現在のプロジェクトの状況について説明したいと思います。

Before we go into Japanese issues, I would like to show you the current project status..

---

Jay:

メッセージ解析に関する作業はほとんど終わりました。特に国際化のところは完了です。

We're done with most of the work related to the message analysis. Especially the internationalization part has been completed.

---

Jay:

ですので、そこをテストする準備はできています。問題は、いつ英語以外の言語モデルができるかです。

So we'are ready to test it. The question is when we can get a non-English language model.

---

Masa:

ジェイ、それについていくつか質問があるのですが。

Jay? I have some questions about that.

---

Jay:

はいどうぞ。

Sure, go ahead.

---

Masa:

スライドにあるテスト項目を見ているのですが、テストデータの量について何も触れていません。

I'm looking at the test items in your slide. I don't see any mention about the volume of test data.

---

Kumud:

そこは今固めようとしています。もう少し時間が必要です。

We're trying to get it nailed down now. We need some more time.

---

Masa:

なにか決まったらすぐに教えてください。

OK, please keep me posted on it.

---

Jay:

では、日本語の問題に移りましょう。マサさん、日本語の言語モデル構築について概要を教えてください。

OK, so let's move on to the Japanese issues. Masa, can you give us an overview of the Japanese language modeling?

---

Masa:

分かりました。先週クムドさんからもらった設計書を見てみましたが、日本語にはワードブレーカーという仕組みが必要です。

OK. I looked at the design document Kumud gave me last week. I found the word breaking process was missing for Japanese.

---

Jay:

ワードブレーカーとはどんなものなんですか？

What's the wordbreaker for?

---

Masa:

日本語は英語のようにスペースで単語を分けることはしません。なので、日本語のテキストを処理する前に、テキストを単語ごとにわけないといけないのです。

Japanese doesn't separate words by spaces like English. So, before we process Japanese text, we need to delimit by words.

---

Kumud:

ワードブレーカのコードはすでにあるんですか？

Do you already have the code for the wordbreaker?

---

Masa:

アジア言語のテキストを処理するサードパーティーのツールがすでにあります。APIを使ってワードブレークすることができます。

We've already got a third-party tool to process Asian text. We can use an API to do the word breaking.

---

Jay:

ではスケジュールの話に移りましょう。まず先ほどのワードブレーカーの実装についてどの程度の時間が必要か、クムドさんとマサさんで相談してください。

Let's move on to the schedules. I would like Kumud and Masa to discuss how long it will take to implement the wordbreaker.

---

Kumud:

承知しました。では後ほど報告します。

All right, Jay. We'll get back to you on that later.

---

Masa:

クムドさん、SDK文書ファイルを共有ドライブに入れおきますので、なにか問題がないか、文書を一通り読んでみてくれますか？

Kumud, I'll put the SDK document file in our shared drive. Can you please go through the doc to see if there are any issues?

---

Kumud:

何かこれといった問題があるのですか？

Do you have any particular issues?

---

Masa:

特に大きな問題はないのですが、言語ごとに特有のパラメーターを設定しないといけないのです。これは後で話をしましょう。具体的な例を見せますので。

Nothing major, but you need to set some language-specific parameters. Let's take this off line. I will give you some concrete examples.

---

Masa:

それともう一つ。うちのチームメンバーの一人がデータに必要な点を一つ指摘しているのですが。

Oh, one more thing. One of my team members came up with one data requirement.

---

Masa:

英語のテストデータを見たところ、カジュアルな会話でのメッセージがほとんどなようですが、どうですか？

I looked at the English test data and found most of the text messages came from casual conversations. Is that correct?

---

Jay:

そうです。

Right.

---

Masa:

日本ではビジネスユーザーが主体なので、ビジネス会話でのメッセージをもっと増やしてもらいたいのですが。

Since the majority of Japanese users are business projessionals, we need more in business conversation messages.

---

Jay:

企業ユーザーによるメッセージをもっと持ってこられないかどうか、データチームに聞いてみるよ。多分大丈夫だと思うけどね。

I'll talk to the data team to see if they can take more messages from enterprise users. I don't think that would be an issue.

---

Masa:

ありがとうございます。

Thank you, Jay.

---

Jay:

他に何か話し合うことはありますか？

Is there anything else we should discuss today?

---

Masa:

これで大丈夫だと思います。

I think we're fine.

---

Jay:

皆さんありがとうございます。後で会議メモを送ります。

Thanks, everyone. I will send you a note later.

---

全員:

ありがとうございました。

Thank you!
