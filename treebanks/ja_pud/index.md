---
layout: base
title:  'UD_Japanese-PUD'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD Japanese PUD

Language: [Japanese](/ja/index.html) (code: `ja`)<br/>
Family: Japanese

This treebank has been part of Universal Dependencies since the UD v2.1 release.

The following people have contributed to making this treebank part of UD: Hans Uszkoreit, Vivien Macketanz, Aljoscha Burchardt, Kim Harris, Katrin Marheinecke, Slav Petrov, Tolga Kayadelen, Mohammed Attia, Ali Elkahky, Zhuoran Yu, Emily Pitler, Saran Lertpradit, Atsuko Shimada, Anna Trukhina, Martin Popel, Daniel Zeman, Hiroshi Kanayama.

Repository: [UD_Japanese-PUD](https://github.com/UniversalDependencies/UD_Japanese-PUD)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/udja_pud22)<br />
Download all treebanks: [UD 2.2](/#download)

License: CC BY-SA 3.0

Genre: news, wiki

Questions, comments?
General annotation questions (either Japanese-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_Japanese-PUD/issues).
If you want to collaborate, please contact [zeman&nbsp;(æt)&nbsp;ufal&nbsp;•&nbsp;mff&nbsp;•&nbsp;cuni&nbsp;•&nbsp;cz].
Development of the treebank happens directly in the UD repository, so you may submit bug fixes as pull requests against the dev branch.

| Annotation | Source |
|------------|--------|
| Lemmas | not available |
| UPOS | annotated manually in non-UD style, automatically converted to UD |
| XPOS | not available |
| Features | annotated manually in non-UD style, automatically converted to UD |
| Relations | annotated manually in non-UD style, automatically converted to UD |

## Description

This is a part of the Parallel Universal Dependencies (PUD) treebanks created
for the [CoNLL 2017 shared task on Multilingual Parsing from Raw Text to
Universal Dependencies](http://universaldependencies.org/conll17/).




There are
1000 sentences in each language, always in the same order. (The sentence
alignment is 1-1 but occasionally a sentence-level segment actually consists
of two real sentences.) The sentences are taken from the news domain (sentence
id starts in ‘n’) and from Wikipedia (sentence id starts with ‘w’). There are
usually only a few sentences from each document, selected randomly, not
necessarily adjacent. The digits on the second and third position in the
sentence ids encode the original language of the sentence. The first 750
sentences are originally English (01). The remaining 250 sentences are
originally German (02), French (03), Italian (04) or Spanish (05) and they
were translated to other languages via English. Translation into German,
French, Italian, Spanish, Arabic, Hindi, Chinese, Indonesian, Japanese,
Korean, Portuguese, Russian, Thai and Turkish has been provided by DFKI and
performed (except for German) by professional translators. Then the data has
been annotated morphologically and syntactically by Google according to Google
universal annotation guidelines; finally, it has been converted by members of
the UD community to UD v2 guidelines.

Additional languages have been provided (both translation and native UD v2
annotation) by other teams: Czech by Charles University, Finnish by University
of Turku and Swedish by Uppsala University.

The entire treebank is labeled as test set (and was used for testing in the
shared task). If it is used for training in future research, the users should
employ ten-fold cross-validation.


## Acknowledgments

# Statistics of UD Japanese PUD

## POS Tags

[ADJ](ja_pud-pos-ADJ.html) – [ADP](ja_pud-pos-ADP.html) – [ADV](ja_pud-pos-ADV.html) – [AUX](ja_pud-pos-AUX.html) – [CCONJ](ja_pud-pos-CCONJ.html) – [DET](ja_pud-pos-DET.html) – [NOUN](ja_pud-pos-NOUN.html) – [NUM](ja_pud-pos-NUM.html) – [PART](ja_pud-pos-PART.html) – [PRON](ja_pud-pos-PRON.html) – [PROPN](ja_pud-pos-PROPN.html) – [PUNCT](ja_pud-pos-PUNCT.html) – [SCONJ](ja_pud-pos-SCONJ.html) – [SYM](ja_pud-pos-SYM.html) – [VERB](ja_pud-pos-VERB.html)

## Features

[NumType](ja_pud-feat-NumType.html)

## Relations

[acl](ja_pud-dep-acl.html) – [advcl](ja_pud-dep-advcl.html) – [advmod](ja_pud-dep-advmod.html) – [amod](ja_pud-dep-amod.html) – [appos](ja_pud-dep-appos.html) – [aux](ja_pud-dep-aux.html) – [case](ja_pud-dep-case.html) – [cc](ja_pud-dep-cc.html) – [ccomp](ja_pud-dep-ccomp.html) – [compound](ja_pud-dep-compound.html) – [cop](ja_pud-dep-cop.html) – [csubj](ja_pud-dep-csubj.html) – [dep](ja_pud-dep-dep.html) – [det](ja_pud-dep-det.html) – [fixed](ja_pud-dep-fixed.html) – [iobj](ja_pud-dep-iobj.html) – [mark](ja_pud-dep-mark.html) – [nmod](ja_pud-dep-nmod.html) – [nsubj](ja_pud-dep-nsubj.html) – [nummod](ja_pud-dep-nummod.html) – [obj](ja_pud-dep-obj.html) – [obl](ja_pud-dep-obl.html) – [punct](ja_pud-dep-punct.html) – [root](ja_pud-dep-root.html)

<h2>Tokenization and Word Segmentation</h2>


<ul>
<li>This corpus contains 1000 sentences and 26709 tokens.</li>
</ul>

<ul>
<li>This corpus contains 26701 tokens (100%) that are not followed by a space.</li>
</ul>

<ul>
<li>This corpus does not contain words with spaces.</li>
</ul>

<ul>
<li>This corpus contains 37 types of words that contain both letters and punctuation. Examples: 、と, ドナルド・トランプ, B.C, 、という, 、を, G.D.P, HerFatherDidn't, Z.A, Zettel’sTraum, 、の, 」な, ウォルト・ディズニー, エル・グレコ, オート・ガロンヌ, オードリー・ヘプバーン, カサ・サンタ・マルタ, カステルフランコ・ヴェネト, サン・ゴーダン, シガー・ロス, シー・オブ・ジ・アンティレス, ジョン・ディ・ドメニコ, スティーラーズ・ホイール, ストレンジャー・シングズ, トーキング・デッド, ド・ゴール, ハーバード・ビジネス・スクール, バハ・カリフォルニヤ, ヒラリー・クリントン, フェデリコ・フェリーニ, フランツ・ヨーゼフ, プンタ・デル・エステ, プンタ・ラサ, マラー/サド, メラニア・トランプ, ラッセ・ハルストレム, ル・コント, ルーカス・クラナッハ</li>
</ul>

<ul>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 15 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>NOUN</a>, <a>NUM</a>, <a>PART</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>SYM</a>, <a>VERB</a></li>
<li>This corpus does not use the following tags: INTJ, X</li>
</ul>

<ul>
<li>This corpus contains 10 word types tagged as particles (PART): か, かどうか, さ, ね, 最大, 最高, 第, 紀元前, 約, 翌</li>
</ul>

<ul>
<li>This corpus contains 26 lemmas tagged as pronouns (PRON): あなた, いずれ, かれら, ここ, これ, これら, そこ, その他, それ, それぞれ, それら, どこ, どちら, どれ, みなさん, よそ, 君たち, 彼, 彼ら, 彼女, 我々, 皆, 私, 私たち, 私達, 誰</li>
</ul>

<ul>
<li>This corpus contains 4 lemmas tagged as determiners (DET): あの, この, その, どの</li>
</ul>

<ul>
</ul>

<ul>
<li>This corpus contains 47 lemmas tagged as auxiliaries (AUX): ある, いく, いる, う, うる, える, おる, かける, かもしれる, くれる, させる, しまう, しめる, すぎる, する, せる, そうだ, た, たい, たら, たろ, だ, できる, でした, ない, なければ, なさる, なら, なる, べし, ます, やすい, ゆく, よい, ようだ, らしい, らす, られる, れる, 出す, 化, 始める, 来る, 終える, 続ける, 良い, 行く</li>
</ul>

<ul>
<li>Out of the above, 16 lemmas occurred sometimes as AUX and sometimes as VERB: ある, いく, いる, かける, する, せる, できる, なさる, なる, 出す, 化, 始める, 来る, 終える, 続ける, 行く</li>
</ul>

<ul>
<li>This corpus does not use the VerbForm feature.</li>
</ul>

<h3>Nominal Features</h3>








<h3>Degree and Polarity</h3>





<h3>Verbal Features</h3>







<h3>Pronouns, Determiners, Quantifiers</h3>



<ul>
  <li><a>NumType</a></li>
</ul>

<ul>
  <li>Card
    <ul>
      <li>NUM: 1, 2, 3, 一, 10, 4, 6, 20, 二, 億</li>
    </ul>
  </li>
</ul>







<h3>Other Features</h3>


<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 1 lemmas as copulas (<a>cop</a>). Examples: だ.</li>
</ul>

<ul>
<li>This corpus uses 46 lemmas as auxiliaries (<a>aux</a>). Examples: た, する, だ, いる, れる, こと, ない, ます, ようだ, う, られる, せる, なる, おる, 来る, できる, たい, べし, 始める, かもしれる, しまう, なければ, 続ける, すぎる, える, たら, いく, かける, くれる, させる, そうだ, でした, 出す, 化, うる, しめる, たろ, なさる, なら, やすい, ゆく, らしい, らす, 終える, 良い, 行く.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB--NOUN-ADP(が) (350)</li>
      <li>VERB--NOUN-ADP(だけ)-ADP(が) (1)</li>
      <li>VERB--NOUN-ADP(など)-ADP(が) (3)</li>
      <li>VERB--NOUN-ADP(の)-ADP(が) (2)</li>
      <li>VERB--NOUN-ADP(は) (388)</li>
      <li>VERB--NOUN-ADP(まで)-ADP(も)-ADP(が) (1)</li>
      <li>VERB--PRON-ADP(が) (30)</li>
      <li>VERB--PRON-ADP(は) (143)</li>
      <li>VERB--PRON-ADP(も)-ADP(が) (1)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB--NOUN-ADP(だけ)-ADP(を) (1)</li>
      <li>VERB--NOUN-ADP(など)-ADP(を) (2)</li>
      <li>VERB--NOUN-ADP(の)-ADP(を) (2)</li>
      <li>VERB--NOUN-ADP(を) (701)</li>
      <li>VERB--NOUN-ADP(を)-ADP(はじめ) (1)</li>
      <li>VERB--NOUN-ADP(を)-ADP(も) (1)</li>
      <li>VERB--PRON-ADP(を) (18)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
      <li>VERB--NOUN-ADP(だけ)-ADP(に) (1)</li>
      <li>VERB--NOUN-ADP(に) (497)</li>
      <li>VERB--NOUN-ADP(に)-ADP(しか) (1)</li>
      <li>VERB--NOUN-ADP(に)-ADP(は) (68)</li>
      <li>VERB--NOUN-ADP(に)-ADP(も) (7)</li>
      <li>VERB--NOUN-ADP(のみ)-ADP(に) (2)</li>
      <li>VERB--NOUN-ADP(まで)-ADP(に) (8)</li>
      <li>VERB--NOUN-ADP(まで)-ADP(に)-ADP(は) (2)</li>
      <li>VERB--PRON-ADP(に) (20)</li>
      <li>VERB--PRON-ADP(に)-ADP(は) (3)</li>
      <li>VERB--PRON-ADP(に)-ADP(も) (2)</li>
    </ul>
  </li>
</ul>




<h3>Relations Overview</h3>

<ul>
<li>This corpus does not use relation subtypes.</li>
<li>The following 13 relation types are not used in this corpus at all: <a>xcomp</a>, <a>vocative</a>, <a>expl</a>, <a>dislocated</a>, <a>discourse</a>, <a>clf</a>, <a>conj</a>, <a>flat</a>, <a>list</a>, <a>parataxis</a>, <a>orphan</a>, <a>goeswith</a>, <a>reparandum</a></li>
</ul>
