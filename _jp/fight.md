---
part: one
title: 議論して、主張して、コミットして！
subtitle: 「チームを前進させるためには、健全な意見の相違を恐れるな！」
---

* TOC
{:toc}

この章は会議をより良いものにするための実践編です。積極的に議論を戦わせてより良い意思決定に到達するやり方について説明します。

## 優秀な人は多様な意見を持っている

本書のはじめにでも説明しましたが、私が最初にエンジニアを雇った時に重要なポイントだったのは、私よりもずっと優秀なプログラマーを見つけるということでした。その後チームが成長していく中で、会社の中のいろいろなポジションでより優秀な人を採用するということが常に私の目標でした。しかし、より良い人を採用する時の最大の問題点は、そのような優秀な人たちはたいてい自分とは異なる意見を持っているということです。しかし、それはいいことです。

## 少数精鋭の優秀な人々が議論を戦わせる

スティーブ・ジョブズ (Steve Jobs) と共にAppleを牽引してきたケン・セガル (Ken Segall) はその著書の中で[^1]、Appleの創業者でありCEOであった故人は、一般的にあまり知られてないかもしれませんが、自分で意思決定をあまりしていなかったということを何度も繰り返し述べています。その代わりに彼は「少数精鋭の優秀な人々」に頼っていたそうです。自分の意思を貫いて、自分の意見を守り通すことを恐れない人々に彼は信頼を置いていました。

エド・キャットマル (Ed Cutmull)[^2] が「トイ・ストーリー」や「ファインディング・ニモ」などで有名なアニメーションスタジオであるPixarをどのように経営しているかを語ったとき、彼は「ブレーントラスト」について言及しました。それはPixarの全ての映画プロジェクトを定期的にレビューする人たちの集まりでした。彼らは映画を試写した後で、その映画に関しての率直な意見を述べます。グループには上下関係もなく、誰もが平等に自分の意見を発言することができます。それは、アーサー王物語に出てくる「円卓の騎士」さながらです[^3]。

このようなグループのメンバーは、それぞれが異ったバックグラウンドを持っていて、異なった視点を提供しなければなりませんが、一方で、同じ価値観を共有している必要があります。お互いに意見を出し合うことに不安がなく、所属している場所での自分の地位についても何らおびえる必要がないということも大切です。

私たちのチームでもこのコンセプトを導入したのですが、それが見事に機能していると言うほかないくらいに私は満足しています。例えば、私たちの「役員」の円卓会議は以下の通りです:

* トム, CTO
* イボナ, サポートVP
* ラファウ, プロダクトVP
* ラデク, エンジニアVP
* ヴァルデマル, ファイナンスVP
* そして私、CEO兼創業者

私は会社のオーナーではありますが、自分一人で大きな決断をすることはありません。皆で話し合います。誰かが何か提案したい時には、その人はそのアイデアをグループ全体に売り込まなければなりません。上記の人たちが私たちの会社の「ブレーントラスト」です。

そして、同じコンセプトが「デザインのブレーントラスト」にも機能します。それはデザインのミーティングに積極的に関与する人々で、NozbeとNozbe Teamsに実装する機能やそのやり方などについて決定しているのもこのグループです。以下の人々です:

* フーベルト, リードデザイナー
* イボナ, サポートVP
* ラファウ, プロダクトVP
* ラデク, エンジニアVP
* レオン, Androidデベロッパー
* そして私、CEO兼創業者

６名、それで十分です。カスタマーサポート、エンジニア、プロダクト、デザイン、そして経営戦略など会社の様々な部署を代表する人々で構成されるグループです。

## 誰もが自由に率直に意見を出し合える。 

当然のことですが、これらのグループのメンバーは、自分の意見を言ったからといって、決して会社を解雇されることはないと分かっています。実際、私たちには「役員」グループがあるので、CEOである私は気まぐれで誰かをクビにすることはできません。もし仮に、ある社員がもはや会社に合わないと私が判断したとしたら、「役員のブレーントラスト」の前でその意見を述べ、彼らの承認を得る必要があります。

製品の機能やデザインについても同じことが言えます。バグの修正や小さな改善や強化に関してエンジニアチームは多くの権限を持ってはいますが、Nozbe PersonalやNozbe Teamsの主要な機能は「デザインのブレーントラスト」を経由しない限りは実現することができません。本書で後ほど紹介するプロセスに従わなければなりません。簡単に言うと、書き出したアジェンダと資料を用意し、週次のデザインチームのミーティングで議論することが要求されます。

もちろん、このような関係を築くには時間がかかります。メンバーのほとんどは長年の付き合いでお互いを良く知っており、会社の中でもある程度のポジションにあり、自分の意見をはっきりと述べることに全く恐れを抱いていません。

さらに、より良い意思決定に到達できるように、次に紹介するいくつかのテクニックも取り入れています

### ワザその１解決策ではなく問題に恋をする

私たちは、アイデアを提案する時には、解決策ではなく問題に焦点を当てるようにしています。ゼネラル・エレクトリック社のCEOであった故ジャック・ウェルチ (Jack Welch) が言った経営の格言があります:。それは*「問題を持ってくるな、解決策を持って来い」*というものです。正直に言って、私にはこれはひどいビジネスアドバイスだと思います。私たちは常に問題から始めるべきです。なぜなら、そこにこそ解決策につながるものがたくさんあるはずだからです。なので、このことを覚えておいてください:

> 問題に恋をする。問題を明確に定義し、その上で解決策を調査する。

これが私たちの仕事です。Nozbeは世界中に何十万人ものユーザーがおり、私たちは毎日たくさんのリクエストをもらいます。そして、*「こんな機能を追加して欲しい」* という要望をしばしばいただきます。すると私たちは次のようにお願いしています。*「その機能でどのような問題が解決できるかを教えてください。実例でお願いします」* そのようにして、問題の根本原因を突き止めていきます。全てのユーザーに共通するような一般的な問題からまずは解決していきたいと考えています。製品に無数の機能を追加して、その結果、他のユーザーを混乱させてしまっては本末転倒ですから。

### ワザその２強固な意見こそ弱腰で

ある問題を徹底的に調査し、分析し、解決策を提案した時、人はそれに対してとても強い思いを抱くのではないでしょうか。自分の時間や労力をたくさん注いだので、それに自信を持っている状態なのです。

その時こそが「強固な意見を弱腰で」のフレームワークを適用する瞬間です[^4]。

あなたが問題を研究し、自分の直感に基づいて解決策を選択すると、あなたはその仮説にとても強気になります。しかし、それがチームから間違っていると証明されます。すると、あなたはその仮説を間違っていたと認める必要があるのです。自分で強固に裏付けた仮説にしがみつくことなく、柔軟に変えていく姿勢を取るのです。

また、アイデアを提案したあなたは、積極的に他の人にその考えを否定できるかどうかということに挑戦してもらわなければなりません。さらに、あなたが入念に用意したものが「あなたの」解決策であるという固執を捨てなければなりません。あなたのエゴを方程式から外すということです。そのことも常に忘れないでください。それは「ただ１つの提案」であって、周りの賢い人たちが同意してくれるのであれば、ただそれでいいというだけのことなのです。

数え切れないほど経験したことですが、私が自分で正しいと確信したアイデアを持って会議に参加したけれども、それが完全に間違っていることが証明され、最終的には、完全に反対の主張が支持されたということは本当に何度もあります。時には、自分のアイデアが死んでいくのを見るのはとても心が痛みますが、それは新しくてより優れた解決策を見つけていくプロセスであり、実はとても喜ばしいものなのです。

### ワザその３反論しコミットする (Disagree and Commit)

この言葉を私は何年もAmazonのジェフ・ベゾス (Jeff Bezos) が唱えたものと思っていましたが、そのコンセプトはもっと古いものだということが分かりました[^5]。

もしこのコンセプトに出会っていなければ、私たちはほとんど何も成し遂げることはなかったとも言えるでしょう。たとえ「ブレーントラスト」グループを作って議論する場ができたとしても、そこでは意見の異なる人が集まっているだけにすぎず、一つの解決策に同意するまでに至るのが難しいという問題が浮上してきます。

しかし、私たちは前に進んでいかなければなりません。では、どうすればいいでしょうか？

投票です。

どの解決策が勝ったとしても、全員でそれを支持していきます。全員でです。例外はありません。反対した人でも積極的に支持に回ります。

*「私は支持するけど、それはもともと私のアイデアじゃないから、もし失敗しても私は責任を負わないよ」* というのとは違います。そんなことは全くありません。あなたが反対の意見を持っていたとしても、皆で決めた解決策を成功させることに全力を尽くすのです。

それは言うほど簡単ではなく、理解するのに時間がかかりますが、チームがそのような決定からのプロセスをいくつか経験すると、意味が分かってくるのです。辛らつに批判していた人でさえも、選ばれた解決策を成功させるために注力するようになります。

なぜなら、１つの解決策の成功というよりも、そこにはチーム全体の成功というもっと大きなものがかかっているからです。

## 議論を戦わせるのを学ぶには時間がかかる

私たちはこれまで何度も白熱した会議をしてきましたが、そのような情熱的な意見の食い違いが私たちは大好きです。自分の意見を主張し、他の人を説得しようと努力し、自らの立場を守ろうと苦労し、途中で考えを変えたり、わざと反対意見を言って問題の全ての側面を検証したりしながら人々は切磋琢磨していきます。

そのようなプロセスに慣れるのには時間がかかるというのも事実です。ここでは謙虚さがとても大切になります。自分のエゴを抑制することを学ぶ必要があります。お互いを尊重することを忘れてはいけません。私たちは相手自身を攻撃することは決してしないようにし、アイデアに対してのみ疑問を投げかけます。私たちは人間です。誰もが感情を持っています。そして時には傷つくこともあります。

このような環境では、私たちは常に試されます。自分のコンフォートゾーンから抜け出ることを強いられたり、緊張感が増してイライラしてしまうこともしばしばです。しかし最終的には、自分たちの仕事をもっと好きになっているはずです。これまで考えたこともないような視点や、自分では考え付かない視点に気づき、人としてもチームとしても成長できるのです。

## １つのキーポイント: 議論はより良い判断につながる

チームとして私たちは「集団思考」や、リーダーに盲目的に従うことを避けなければなりません。反対に、避けてはならないことは、健全な意見の相違や情熱的な議論です。このことをチームは肝に銘じ、それに慣れていかなければなりません。チームがより良い意思決定をするために。

この章で私はいくつかの本について触れましたが、エド・キャットマル (Ed Cutmull) 著「Creativity Inc.」を私は一番にお勧めします。

[^1]: [ケン・セガル (Ken Segall):「Insanely Simple」](https://kensegall.com/books/)

[^2]: [エド・キャットマル (Ed Cutmull):「Creativity Inc.」](https://www.creativityincbook.com)

[^3]: [円卓の騎士 Knights of The Round Table](https://ja.wikipedia.org/wiki/%E5%86%86%E5%8D%93%E3%81%AE%E9%A8%8E%E5%A3%AB)

[^4]: [ポール・サフォー (Paul Saffo)  -「strong opinions, weakly held」フレームワークの著者](http://www.saffo.com/about-paul-saffo/)

[^5]: [Disagree and Commit についてのWikipediaのページ](https://en.wikipedia.org/wiki/Disagree_and_commit)
