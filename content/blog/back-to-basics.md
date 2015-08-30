+++
date = "2015-08-30T23:28:32+09:00"
description = "CSS の基本に立ち返ろうという、そんな勉強会に参加してきた。"
tags = "dev"
title = "Back to Basics"

[menu]
  [menu.global]
    parent = "blog"

+++

「[CSSイベント「Back to Basics」 | Peatix](http://peatix.com/event/105960)」という勉強会に参加してきた。

で、この記事書いてる途中にイベントの様子がトゥギャられてた。

- [CSSイベント「Back to Basics」2015/08 | togetter](http://togetter.com/li/867476)

今回の勉強会の発表資料とかそれ関連のリンクとかつぶやきとかが適当に集まってる。発表資料や勉強会の様子は後日別の形でもどこかにまとめられるかもしれない。ブログとか。

さて、自分なりに勉強会を振り返ってみると、月並みだけど普段当たり前に使ってる CSS のことでも知らないことだらけだったなーという感想。

一部の LT を除いて、発表を聞くまで知らなかったプロパティとか用語はほとんど出てこなかった。でも、発表の内容を聞けば聞くほど、それは言葉だけを知っていただけで中身を全然理解できて無かったんだなーって少し悲しくなった。（僕も CSS と触れ合ってきた時間はそれなりに長くなってきたからね）

あと、仕様書に目を通しておくことの大切さも各セッションで言われていた。

仕様で決められた型や役割があって、それを踏まえた上でブラウザ側での実装がある（中には都合上仕様通りに実装されてないものもある）。ときには誰も予期せぬバグなんてのがあるけれど、仕様書を読み解くことで目の前の表示崩れの原因が分かることも多い。

一つの問題が発生した時、それに対して表層的に対処するのは簡単だ。CSS でスタイルングしたサイトの見た目が崩れたのならば、それを綺麗に整えるのは無茶をすればいくらでもできる。要素をいくつも重ねて、プロパティを何度も上書きして、誰も理解できないセレクタで指定して... 。

ただ、**根本的な原因を理解していれば、もっと楽に、スマートに解決できる**んじゃないかな。その根本的な原因を理解するには**仕様書を読む**のが確実で手っ取り早いって話だと思う。

一人 30分の発表ではこちらの理解が追いつかなくて、今はちょいちょい登壇者の方のスライド見返してたりする。発表の中にデモを取り入れてるものが多いのが救い。

---

ブログをお休みしながら書いてると一つの記事書くだけで大変、Oh !!! 大変 !!! ってなる。適当に短く簡潔に済ませたいんだけど、時間はかかるし文章はまとまらないしで、マジ苦労。