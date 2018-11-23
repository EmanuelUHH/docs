---
layout: base
title:  'UD_Irish-IDT'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD Irish IDT

Language: [Irish](/ga/index.html) (code: `ga`)<br/>
Family: Indo-European, Celtic

This treebank has been part of Universal Dependencies since the UD v1.0 release.

The following people have contributed to making this treebank part of UD: Teresa Lynn, Jennifer Foster.

Repository: [UD_Irish-IDT](https://github.com/UniversalDependencies/UD_Irish-IDT)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/udga_idt22)<br />
Download all treebanks: [UD 2.2](/#download)

License: CC BY-SA 3.0

Genre: news, fiction, web, legal

Questions, comments?
General annotation questions (either Irish-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_Irish-IDT/issues).
If you want to collaborate, please contact [teresa&nbsp;•&nbsp;lynn&nbsp;(æt)&nbsp;adaptcentre&nbsp;•&nbsp;ie; jennifer&nbsp;•&nbsp;foster&nbsp;(æt)&nbsp;dcu&nbsp;•&nbsp;ie].
Development of the treebank happens outside the UD repository.
If there are bugs, either the original data source or the conversion procedure must be fixed.
Do not submit pull requests against the UD repository.

| Annotation | Source |
|------------|--------|
| Lemmas | annotated manually in non-UD style, automatically converted to UD, with some manual corrections of the conversion |
| UPOS | annotated manually in non-UD style, automatically converted to UD, with some manual corrections of the conversion |
| XPOS | assigned by a program, with some manual corrections, but not a full manual verification |
| Features | annotated manually in non-UD style, automatically converted to UD, with some manual corrections of the conversion |
| Relations | annotated manually in non-UD style, automatically converted to UD, with some manual corrections of the conversion |

## Description

A Universal Dependencies 1020-sentence treebank for modern Irish.



The Irish UD Treebank is a conversion of the Irish Dependency Treebank
(IDT).

IDT development was part of a PhD research project by Teresa Lynn at Dublin City University, Ireland (Lynn, 2016). The IDT data has
been released on [GitHub] (https://github.com/tlynn747/IrishDependencyTreebank). The Treebank
contains 1020 sentences taken from the New Corpus of Ireland-Irish
(NCII), with text from books, newswire, websites and other media. These sentences are a subset of a gold-standard POS-tagged corpus for Irish.

The conversion from the IDT annotation scheme to the UD annotation scheme was designed by Teresa Lynn and Jennifer Foster at Dublin City University, Ireland. The mapping to UD is reported in Lynn et al., (2016)

The UD Treebank is split into three sets as follows:

* 454 trees (test)
* 445 trees - 11,533 tokens (dev)
* 121 trees - 3425 tokens (train)

Note: the split was formerly 150- test, 150-dev, 720-train, but have split as above for the 2017 CoNLL shared task on dependency parsing.

## Acknowledgments

We wish to thank all of the contributors to the original IDT annotation, including Elaine Uí Dhonnchadha for her gold POS-tagged corpus and linguistic advice. We would also like to acknowledge linguistic advice offered by Kevin Scannell in the conversion to UD effort.

This research is partially supported by Science Foundation Ireland through the ADAPT Centre for Digital Content Technology. The ADAPT Centre for Digital Content Technology is funded under the SFI Research Centres Programme (Grant 13/RC/2106)
and is co-funded under the European Regional Development Fund.



# Statistics of UD Irish IDT

## POS Tags

[ADJ](ga_idt-pos-ADJ.html) – [ADP](ga_idt-pos-ADP.html) – [ADV](ga_idt-pos-ADV.html) – [AUX](ga_idt-pos-AUX.html) – [CCONJ](ga_idt-pos-CCONJ.html) – [DET](ga_idt-pos-DET.html) – [INTJ](ga_idt-pos-INTJ.html) – [NOUN](ga_idt-pos-NOUN.html) – [NUM](ga_idt-pos-NUM.html) – [PART](ga_idt-pos-PART.html) – [PRON](ga_idt-pos-PRON.html) – [PROPN](ga_idt-pos-PROPN.html) – [PUNCT](ga_idt-pos-PUNCT.html) – [SCONJ](ga_idt-pos-SCONJ.html) – [SYM](ga_idt-pos-SYM.html) – [VERB](ga_idt-pos-VERB.html) – [X](ga_idt-pos-X.html)

## Features

[Abbr](ga_idt-feat-Abbr.html) – [Case](ga_idt-feat-Case.html) – [Definite](ga_idt-feat-Definite.html) – [Degree](ga_idt-feat-Degree.html) – [Dialect](ga_idt-feat-Dialect.html) – [Foreign](ga_idt-feat-Foreign.html) – [Form](ga_idt-feat-Form.html) – [Gender](ga_idt-feat-Gender.html) – [Mood](ga_idt-feat-Mood.html) – [NounType](ga_idt-feat-NounType.html) – [Number](ga_idt-feat-Number.html) – [NumType](ga_idt-feat-NumType.html) – [PartType](ga_idt-feat-PartType.html) – [Person](ga_idt-feat-Person.html) – [Polarity](ga_idt-feat-Polarity.html) – [Poss](ga_idt-feat-Poss.html) – [PrepForm](ga_idt-feat-PrepForm.html) – [PronType](ga_idt-feat-PronType.html) – [Reflex](ga_idt-feat-Reflex.html) – [Tense](ga_idt-feat-Tense.html) – [VerbForm](ga_idt-feat-VerbForm.html) – [Voice](ga_idt-feat-Voice.html)

## Relations

[acl:relcl](ga_idt-dep-acl-relcl.html) – [advcl](ga_idt-dep-advcl.html) – [advmod](ga_idt-dep-advmod.html) – [amod](ga_idt-dep-amod.html) – [appos](ga_idt-dep-appos.html) – [case](ga_idt-dep-case.html) – [case:voc](ga_idt-dep-case-voc.html) – [cc](ga_idt-dep-cc.html) – [ccomp](ga_idt-dep-ccomp.html) – [compound](ga_idt-dep-compound.html) – [compound:prt](ga_idt-dep-compound-prt.html) – [conj](ga_idt-dep-conj.html) – [cop](ga_idt-dep-cop.html) – [csubj:cleft](ga_idt-dep-csubj-cleft.html) – [csubj:cop](ga_idt-dep-csubj-cop.html) – [det](ga_idt-dep-det.html) – [discourse](ga_idt-dep-discourse.html) – [fixed](ga_idt-dep-fixed.html) – [flat](ga_idt-dep-flat.html) – [flat:name](ga_idt-dep-flat-name.html) – [list](ga_idt-dep-list.html) – [mark](ga_idt-dep-mark.html) – [mark:prt](ga_idt-dep-mark-prt.html) – [nmod](ga_idt-dep-nmod.html) – [nmod:poss](ga_idt-dep-nmod-poss.html) – [nsubj](ga_idt-dep-nsubj.html) – [nummod](ga_idt-dep-nummod.html) – [obj](ga_idt-dep-obj.html) – [obl](ga_idt-dep-obl.html) – [obl:prep](ga_idt-dep-obl-prep.html) – [obl:tmod](ga_idt-dep-obl-tmod.html) – [parataxis](ga_idt-dep-parataxis.html) – [punct](ga_idt-dep-punct.html) – [root](ga_idt-dep-root.html) – [vocative](ga_idt-dep-vocative.html) – [xcomp](ga_idt-dep-xcomp.html) – [xcomp:pred](ga_idt-dep-xcomp-pred.html)

<h2>Tokenization and Word Segmentation</h2>


<ul>
<li>This corpus contains 1020 sentences and 23964 tokens.</li>
</ul>

<ul>
<li>This corpus contains 2516 tokens (10%) that are not followed by a space.</li>
</ul>

<ul>
<li>This corpus does not contain words with spaces.</li>
</ul>

<ul>
<li>This corpus contains 204 types of words that contain both letters and punctuation. Examples: d', b', fho-alt, (a), (b), a', m', (c), Co., 'n, Uimh., s', t-am, &quot;, O', a'm, n', n-a, n-oibreacha, n-áirítear, nua-aimseartha, t-airgead, t-ábhar, (d), (i), (ii), Anne-Marie, Ard-Chomhairle, Ard-Mhúsaem, I.R., J., P., bhfo-alt, h-Íde, mb', meán-suidhte, n-athair, n-éireoidh, nea-mbrí, t-eolas, t-ionad, 's, (W), (e), (f), (iii), (iv), (vi), -e, .i.</li>
</ul>

<ul>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 17 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>INTJ</a>, <a>NOUN</a>, <a>NUM</a>, <a>PART</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>SYM</a>, <a>VERB</a>, <a>X</a></li>
</ul>

<ul>
<li>This corpus contains 34 word types tagged as particles (PART): Mac, Mc, Mhic, Nic, O', Uí, a, a', ab, an, ar, ba, d', de, do, faoina, go, gur, ina, inar, is, le, lena, lenar, n', n-a, nach, ná, nár, ní, níor, o, trasna, Ó</li>
</ul>

<ul>
<li>This corpus contains 28 lemmas tagged as pronouns (PRON): cad, ceachtar, cibé, cé, céard, ea, eisean, féin, iad, ise, iúd, mise, muid, mé, pé, seisean, seo, siad, sibh, sin, sinn, siúd, sé, sí, tusa, tú, é, í</li>
</ul>

<ul>
<li>This corpus contains 21 lemmas tagged as determiners (DET): a, an, aon, cad, cibé, cé, do, eile, gach, gach_uile, iomaí, leath, mo, na, s, seo, sin, siúd, uile, ár, úd</li>
</ul>

<ul>
<li>Out of the above, 6 lemmas occurred sometimes as PRON and sometimes as DET: cad, cibé, cé, seo, sin, siúd</li>
</ul>

<ul>
<li>This corpus contains 9 lemmas tagged as auxiliaries (AUX): ar, cad, cé, is, má, ní, seo, sin, sé</li>
</ul>

<ul>
<li>Out of the above, 1 lemmas occurred sometimes as AUX and sometimes as VERB: ar</li>
</ul>

<ul>
<li>There are 4 <a href="../feat/VerbForm.html">(de)verbal forms:</a></li>
</ul>

<ul>
  <li>Cop
  <ul>
    <li>AUX: is, ba, gur, ní, nach, b', gurb, níor, ar, gurbh</li>
    <li>SCONJ: más, dar, ós, Sular, murab</li>
    <li>X: Caidé</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Inf
  <ul>
    <li>NOUN: fáil, bheith, chur, dhéanamh, rá, dul, thabhairt, cur, tabhairt, bhaint</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Part
  <ul>
    <li>ADJ: déanta, bunaithe, imithe, leagtha, ráite, scríofa, tugtha, Aontaithe, bailithe, briste</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Vnoun
  <ul>
    <li>NOUN: dul, faire, obair, teacht, éirí, déanamh, iarraidh, brath, cur, breathnú</li>
  </ul>
  </li>
</ul>

<h3>Nominal Features</h3>


<ul>
  <li><a>Gender</a></li>
</ul>

<ul>
  <li>Fem
    <ul>
      <li>ADJ: mhaith, mhór, bheag, chéanna, iomlán, poiblí, óg, fada, inrátaithe, luachmhar</li>
      <li>ADP: uirthi, ina, di, aici, á, inti, dá, léi, chuici, léithe</li>
      <li>DET: na, a</li>
      <li>NOUN: chuid, leith, bhliain, áit, uair, bliain, gcuid, cuid, aghaidh, gceist</li>
      <li>PRON: sí, í, ise, hí</li>
      <li>PROPN: Gaeilge, hÉireann, Éirinn, Ghaeilge, Mháire, Fraince, nGaeilge, Éire, Meiriceá, Máire</li>
      <li>X: open</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Masc
    <ul>
      <li>ADJ: mór, éigin, beag, chéanna, fada, óg, ard, bán, deireanach, eachtraigh</li>
      <li>ADP: ann, air, ina, leis, aige, á, dá, dó, chuige, lena</li>
      <li>AUX-Cop: Sé</li>
      <li>DET: a</li>
      <li>NOUN: rud, duine, fear, lá, daoine, chéile, alt, am, ceann, measc</li>
      <li>PRON: sé, é, seisean, eisean, hé</li>
      <li>PROPN: Átha, Bhaile, Seán, mBaile, Phádraig, Bhreandán, Chill, Chorcaí, Eoin, Fianna</li>
      <li>VERB: Tá's</li>
      <li>X: fá, Kill</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Number</a></li>
</ul>

<ul>
  <li>Plur
    <ul>
      <li>ADJ: beaga, éagsúla, difriúla, aisteacha, deonacha, lansacha, maithe, móra, poiblí, príomhúla</li>
      <li>ADP: acu, ina, orthu, dóibh, leo, sna, againn, dúinn, á, díobh</li>
      <li>DET: na, a, ár</li>
      <li>NOUN: daoine, dhaoine, tíortha, blianta, rudaí, rialacha, scrúduithe, Ballstáit, scéalta, seirbhísí</li>
      <li>PRON: iad, siad, muid, hiad, siadsan, sibh, sinn, sinne, iadsan</li>
      <li>PROPN: mBaile, Eorpach, Mumhan, gCill, hIceadha, Éireannaigh, Comharsain, Doirí, Fíoncheannaithe, Gaeil</li>
      <li>VERB: Táimid, bhíodar, Amharcaigí, Bhíomar, Casaimid, Chaitheamar, Chuamar, Chuiridís, Creidimidne, Fuaireamar</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sing
    <ul>
      <li>ADJ: éigin, mór, chéanna, mhaith, mhór, óg, fada, beag, iomlán, ard</li>
      <li>ADP: sa, ann, den, ina, air, san, leis, ón, don, á</li>
      <li>AUX-Cop: Sé, Cén</li>
      <li>DET: an, na, a, mo, do, m', a', 'n, cén, d'</li>
      <li>NOUN: bith, níos, rud, duine, chuid, fear, féidir, lá, leith, oiread</li>
      <li>PRON: sé, é, sí, mé, í, tú, cén, mise, ea, seisean</li>
      <li>PROPN: Gaeilge, Átha, Bhaile, Seán, hÉireann, Éirinn, Ghaeilge, Mháire, nGaeilge, Éire</li>
      <li>VERB: féach, bíodh, déan, bhíos, cuir, rabhas, Tabhair, faigh, glacaim, leanas</li>
      <li>X: fá, dein, Bhraitheas, Kill, chuireas, domhsa, open</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Case</a></li>
</ul>

<ul>
  <li>Dat
    <ul>
      <li>NOUN: gcrích, cionn, Tigh, láimh, chionn, chois, gcionn, leabhair, mbliana, ndíg</li>
      <li>PROPN: Éirinn, hÉirinn</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Gen
    <ul>
      <li>ADJ: beaga, eachtraigh, mhóir, speisialta, éagsúla, Caitlicí, Ultacha, bána, cháilithigh, deonacha</li>
      <li>DET: na</li>
      <li>NOUN: airgid, cinn, tíre, bliana, cathrach, chloig, hoíche, teanga, Fómhair, Gaeltachta</li>
      <li>NOUN-Inf: Fiosraithe, bhreithnithe, chleachta, claonta, cosanta, craptha, dhéanta, dumpála, eagraithe, fuaraithe</li>
      <li>PROPN: Gaeilge, Átha, Bhaile, hÉireann, mBaile, Fraince, Chill, Mumhan, hEorpa, Chaoin</li>
    </ul>
  </li>
</ul>

<ul>
  <li>NomAcc
    <ul>
      <li>ADJ: éigin, mór, chéanna, mhaith, mhór, óg, beaga, fada, beag, iomlán</li>
      <li>NOUN: rud, chuid, duine, fear, lá, leith, bhliain, áit, daoine, uair</li>
      <li>PROPN: Seán, Ghaeilge, Gaeilge, Mháire, nGaeilge, Éire, Bhreandán, Chorcaí, Fianna, John</li>
      <li>VERB: Tá's</li>
      <li>X: Kill, open</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Voc
    <ul>
      <li>NOUN: Chapaillín, Dhochtúir, Oideachais, bhithiúnaigh, chúil, dhaoine, fheara, ghrá, naofacht, pheaitín</li>
      <li>PROPN: Dhoráid, Mháiréad, Phádraig, Pháidín, Sheáin, Tom</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Definite</a></li>
</ul>

<ul>
  <li>Def
    <ul>
      <li>DET: an, na, gach, chuile, a', a, 'n, ngach, iomaí</li>
      <li>NOUN: fear, bhliain, saol, leabhar, lá, hoíche, áit, bliana, chloig, méid</li>
      <li>NUM: dá, dhá</li>
      <li>PROPN: Gaeilge, hÉireann, Ghaeilge, hEorpa, Coileánach, Afraic, Bheilg, Breathnach, Ceallach, Chaitlín</li>
      <li>X: achan</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>NOUN: láimh, Criosanna, dlíthe, gnóthaí, oibre, uibheacha</li>
    </ul>
  </li>
</ul>

<h3>Degree and Polarity</h3>


<ul>
  <li><a>Degree</a></li>
</ul>

<ul>
  <li>Cmp,Sup
    <ul>
      <li>ADJ: mó, fearr, fhearr, mhó, déanaí, báine, caoile, ceolmhaire, ciallmhaire, daoire</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pos
    <ul>
      <li>ADJ: amháin, maith, léir, mór, áirithe, fada, mó, beag, céanna, náisiúnta</li>
      <li>NOUN: ceart</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Polarity</a></li>
</ul>

<ul>
  <li>Neg
    <ul>
      <li>AUX-Cop: ní, nach, níor, nár, níorbh, nárbh</li>
      <li>PART: ní, nach, níor, ná, nár, n'</li>
      <li>VERB: raibh, níl, bheidh, bhfuil, fhaca, bhain, chuireann, dhéanfadh, mbeidh, thugann</li>
      <li>X: chan, cha, dein, ná</li>
    </ul>
  </li>
</ul>


<h3>Verbal Features</h3>



<ul>
  <li><a>Mood</a></li>
</ul>

<ul>
  <li>Cnd
    <ul>
      <li>AUX-Cop: Ba, mba</li>
      <li>VERB: bheadh, mbeadh, dtiocfadh, dhéanfadh, rachadh, bhféadfadh, bhféadfaí, chuirfeadh, dtuigfí, fhéadfadh</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Imp
    <ul>
      <li>PART: ná</li>
      <li>VERB: bhíodh, féach, bíodh, déan, cuir, dhéanadh, Tabhair, faigh, mbínn, mbíodh</li>
      <li>X: dein</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>VERB: bhí, tá, raibh, atá, bhfuil, bheidh, beidh, thug, tháinig, mbeidh</li>
      <li>X: dhein, Bhraitheas, chuireas, deineadh</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Int
    <ul>
      <li>AUX-Cop: nach, an, Cén, cad, nár</li>
      <li>PART: nach</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sub
    <ul>
      <li>PART: go</li>
      <li>VERB: Roinne, chroma, n-imí, raibh, shéide</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Tense</a></li>
</ul>

<ul>
  <li>Fut
    <ul>
      <li>VERB: bheidh, beidh, mbeidh, caithfidh, déanfaidh, cuirfidh, déanfar, féadfaidh, féadfidh, measfaidh</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Past
    <ul>
      <li>AUX-Cop: ba, b', gur, níor, gurbh, mba, nár, ab, níorbh, ar</li>
      <li>PART: gur, níor, ar, nár</li>
      <li>SCONJ: Sular, murab</li>
      <li>SCONJ-Cop: Sular, murab</li>
      <li>VERB: bhí, raibh, thug, tháinig, chuir, dúirt, bhíodh, cuireadh, rinneadh, rinne</li>
      <li>X: dhein, chuireas, deineadh</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pres
    <ul>
      <li>AUX-Cop: is, gur, ní, nach, gurb, an, ar, sea</li>
      <li>VERB: tá, atá, bhfuil, níl, deir, bhaineann, dar, adeir, chuireann, cuirtear</li>
      <li>X: Bhraitheas</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Voice</a></li>
</ul>

<ul>
  <li>Auto
    <ul>
      <li>VERB: cuireadh, rinneadh, cuirtear, deonadh, dhéantar, dtagraítear, déanfar, déantar, faightear, shonraítear</li>
      <li>X: deineadh</li>
    </ul>
  </li>
</ul>


<h3>Pronouns, Determiners, Quantifiers</h3>


<ul>
  <li><a>PronType</a></li>
</ul>

<ul>
  <li>Art
    <ul>
      <li>ADP: sa, den, san, ón, don, faoin, sna, fén, ins</li>
      <li>AUX-Cop: Cén</li>
      <li>DET: an, na, a, a', 'n</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Dem
    <ul>
      <li>AUX-Cop: Seo, Sin</li>
      <li>DET: seo, sin, eile, úd, s', siúd</li>
      <li>PRON: sin, seo, siúd, shin, san, in, iúd, súd</li>
      <li>X: san, so</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Emp
    <ul>
      <li>ADP: againne, agamsa, agatsa, domsa, leatsa, liomsa, airsean, dósan, leosan, tríothusan</li>
      <li>PRON: mise, seisean, eisean, ise, siadsan, sinne, iadsan, tusa</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>DET: aon, cibé, uile, haon, n-uile</li>
      <li>PRON: pé, Cibé, ceachtar, cheachtar</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Int
    <ul>
      <li>ADV: conas, cá</li>
      <li>DET: cad, cén</li>
      <li>PRON: cad, cé, cén, céard</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Prs
    <ul>
      <li>ADP: á, dhá</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Rel
    <ul>
      <li>AUX-Cop: ba, nach, is, ab, nár, nárbh</li>
      <li>PART: a, ina, nach, inar, ar, lena, n-a, nár, faoina, lenar</li>
      <li>VERB: atá, leanas, eireos, atáid, atáimse, bhíos, chaoinfeas, chuireas, fhéadas, rachas</li>
      <li>X: ná</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>NumType</a></li>
</ul>

<ul>
  <li>Card
    <ul>
      <li>NOUN: céad</li>
      <li>NUM: dhá, trí, céad, seacht, aon, ceithre, fiche, sé, dá, cúig</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ord
    <ul>
      <li>NUM: chéad, dara, 10ú, gcéad, 11ú, 17ú, 18ú, 3ú, cheathrú, dtríú</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Poss</a></li>
</ul>

<ul>
  <li>Yes
    <ul>
      <li>ADP: ina, á, dá, lena, faoina, arna, óna, dhá, lenár, dár</li>
      <li>DET: a, mo, do, m', ár, d'</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Reflex</a></li>
</ul>

<ul>
  <li>Yes
    <ul>
      <li>NOUN: fhéin</li>
      <li>PRON: féin</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Person</a></li>
</ul>

<ul>
  <li>1
    <ul>
      <li>ADP: liom, agam, againn, dúinn, orm, dom, linn, chugainn, chugam, a'm</li>
      <li>DET: mo, m', ár</li>
      <li>PRON: mé, muid, mise, sinn, sinne</li>
      <li>VERB: bhíos, rabhas, Táimid, glacaim, leanas, mbeinn, mbínn, Bhíomar, Casaimid, Chaitheamar</li>
      <li>X: Bhraitheas, chuireas, domhsa</li>
    </ul>
  </li>
</ul>

<ul>
  <li>2
    <ul>
      <li>ADP: leat, agat, duit, ort, agatsa, leatsa, uait, agaibh, asat, oraibh</li>
      <li>DET: do, d'</li>
      <li>PRON: tú, sibh, thusa, thú, tusa</li>
      <li>VERB: féach, déan, cuir, Tabhair, faigh, éist, Amharcaigí, BUAIL, Cheapfá, Lig</li>
      <li>X: dein</li>
    </ul>
  </li>
</ul>

<ul>
  <li>3
    <ul>
      <li>ADP: ann, ina, air, leis, acu, á, dá, aige, orthu, dó</li>
      <li>AUX-Cop: Sé</li>
      <li>DET: a</li>
      <li>PRON: sé, é, sí, iad, siad, í, ea, seisean, eisean, ise</li>
      <li>VERB: bíodh, bhíodar, Chuiridís, Sheoladar, atáid, bheidís, bogadh, chríochnaíodar, chuadar, chuireadar</li>
      <li>X: fá</li>
    </ul>
  </li>
</ul>




<h3>Other Features</h3>


<ul>
  <li><a>Abbr</a>
    <ul>
      <li>Yes
        <ul>
          <li>PROPN: UNDDSMS</li>
          <li>SYM: post@clubsult.com</li>
          <li>X: Co., Uimh., A, FÁS, I.R., IO, J., P., RTÉ, SEIF</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Dialect</a>
    <ul>
      <li>Connaught
        <ul>
          <li>X: Caidé</li>
        </ul>
      </li>
      <li>Munster
        <ul>
          <li>VERB: dhein</li>
          <li>X: san, so, age, dein, des, dhein, fachta, Bhraitheas, chuireas, deineadh</li>
        </ul>
      </li>
      <li>Ulster
        <ul>
          <li>X: chan, fá, cha, Caidé, achan, domhsa</li>
          <li>X-Cop: Caidé</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Foreign</a>
    <ul>
      <li>Yes
        <ul>
          <li>ADJ: necessary, other, white</li>
          <li>ADJ-Part: white</li>
          <li>ADP: by</li>
          <li>NOUN: Office, Regeneration, tasks, cheap</li>
          <li>PROPN: major</li>
          <li>VERB: deemed</li>
          <li>X: -e, Comptroller-General, Cyrano, Forget, I, Love, May, September, The, TrueType</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Form</a>
    <ul>
      <li>Ecl
        <ul>
          <li>ADJ: gcéanna</li>
          <li>AUX-Cop: mba</li>
          <li>DET: ngach, gach</li>
          <li>NOUN: gcuid, gcás, gceist, ndóigh, bhfeidhm, gcónaí, gcomhairle, dtús, mbealach, ndáil</li>
          <li>NOUN-Inf: bhfeidhmiú, bhfíorú, gcailliúint, gcomhlíonadh, gcraitheadh, gcraoladh, gcur, ndéanamh, ngabháil, ngoradh</li>
          <li>NOUN-Vnoun: titim</li>
          <li>NUM: gcéad, dtríú, gceithre</li>
          <li>PART: n-a</li>
          <li>PROPN: mBaile, nGaeilge, Mumhan, gCill, nGaillimh, Mullen, Mí, Sergeant, gCambridge, gCuan</li>
          <li>VERB: raibh, bhfuil, mbeidh, mbeadh, mbíonn, mbaineann, bhfaca, dtiocfadh, ndeachaigh, bhfuair</li>
        </ul>
      </li>
      <li>Emp
        <ul>
          <li>NOUN: liostasa</li>
          <li>VERB: Creidimidne, atáimse, deirimse, gcaithfeadsa, nílirse</li>
          <li>X: domhsa</li>
        </ul>
      </li>
      <li>HPref
        <ul>
          <li>ADJ: háirithe, hamháin, hiontach, han-luath, hiomlán, hálainn, héifeachtach, héifeachtúil</li>
          <li>DET: haon</li>
          <li>NOUN: háit, hordú, haigne, heagraíochtaí, hOllscoile, haghaidh, hainm, hainmhithe, halt, ham</li>
          <li>NOUN-Inf: himeacht, hithe, hordú, húsáid</li>
          <li>NUM: haon</li>
          <li>PROPN: h-Íde, hÉirinn, mí</li>
        </ul>
      </li>
      <li>Len
        <ul>
          <li>ADJ: mhaith, cheart, chóir, Bhriotáineach, céanna, chéanna, mhór, chomhionann, chultúrtha, chuí</li>
          <li>ADJ-Part: Bhunaithe</li>
          <li>ADP: dhaoibh, dhom, dhíobh, dhúinn</li>
          <li>ADV: Thuaidh</li>
          <li>NOUN: bheith, chur, dhéanamh, chuid, chéile, thabhairt, fho-alt, bhaint, fhios, chineál</li>
          <li>NOUN-Inf: bheith, chur, dhéanamh, thabhairt, bhaint, chaitheamh, fháil, dhul, sheoladh, choinneáil</li>
          <li>NUM: chéad, dhó, cheathrú, thrí, cheithre, sheacht, sheasca, thríú</li>
          <li>PRON: cheachtar, thusa, thú</li>
          <li>PROPN: Bhaile, Átha, Mháire, Phádraig, Bhreandán, Chill, Bhéal, Cholm, Chonamara, Ghaeilge</li>
          <li>VERB: bhí, bheidh, raibh, thug, tháinig, bheadh, chuir, bhíonn, bhíodh, bhaineann</li>
          <li>X: dhein, chuireas</li>
        </ul>
      </li>
      <li>VF
        <ul>
          <li>AUX-Cop: b', gurb, gurbh, ab, níorbh, mb', nárbh</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>NounType</a>
    <ul>
      <li>NotSlender
        <ul>
          <li>ADJ: beaga, difriúla, príomhúla, seachtracha, aisteacha, bríomhara, crúcacha, deasa, deonacha, eachtracha</li>
        </ul>
      </li>
      <li>Slender
        <ul>
          <li>ADJ: éagsúla, aisteacha, bhradacha, chuí, cháilitheacha, dheonacha, ghlasa, mhéadracha, orgánacha, phríomhúla</li>
        </ul>
      </li>
      <li>Strong
        <ul>
          <li>ADJ: beaga, éagsúla, Ultacha, bána, deonacha, difriúla, inmheánacha, maithe, móra, núicléacha</li>
          <li>NOUN: daoine, oibreacha, ban, n-oibreacha, ndaoine, ceoltóirí, gCailíní, nduillí, orduithe, rudaí</li>
          <li>PROPN: Fíoncheannaithe</li>
        </ul>
      </li>
      <li>Weak
        <ul>
          <li>ADJ: orgánach, plaisteach, saor</li>
          <li>NOUN: Fiontar, súl, Náisiún, bhflaitheas, breiseán, fear, mballstát, Bhéal, Ealaíon, Foras</li>
          <li>PROPN: Eorpach, Éireannach</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>PartType</a>
    <ul>
      <li>Ad
        <ul>
          <li>PART: go, le</li>
        </ul>
      </li>
      <li>Cmpl
        <ul>
          <li>PART: go, nach, nár, ná</li>
        </ul>
      </li>
      <li>Comp
        <ul>
          <li>AUX-Cop: ba</li>
          <li>NOUN: níos</li>
          <li>PART: ní</li>
        </ul>
      </li>
      <li>Cop
        <ul>
          <li>PART: a</li>
        </ul>
      </li>
      <li>Deg
        <ul>
          <li>ADP: dá</li>
          <li>PART: a</li>
        </ul>
      </li>
      <li>Inf
        <ul>
          <li>PART: a, do, trasna, a'</li>
        </ul>
      </li>
      <li>Num
        <ul>
          <li>PART: a</li>
        </ul>
      </li>
      <li>Pat
        <ul>
          <li>PART: Ó, de, Mac, Uí, Nic, Ní, O', Mc, Mhic, O</li>
        </ul>
      </li>
      <li>Vb
        <ul>
          <li>PART: a, d', ní, gur, do, nach, níor, ar, an, ná</li>
          <li>X: chan, cha, ná</li>
        </ul>
      </li>
      <li>Voc
        <ul>
          <li>ADJ: Eachtraigh, fáinneach, ghil, ghrinn, uaisle</li>
          <li>PART: a</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>PrepForm</a>
    <ul>
      <li>Cmpd
        <ul>
          <li>ADP: i, go, ar, de, tar, in, le, os, thar, faoi</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 2 lemmas as copulas (<a>cop</a>). Examples: is, má.</li>
</ul>

<ul>
<li>This corpus does not contain auxiliaries.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB--NOUN (20)</li>
      <li>VERB--NOUN-Dat (2)</li>
      <li>VERB--NOUN-Gen (11)</li>
      <li>VERB--NOUN-NomAcc (606)</li>
      <li>VERB--NOUN-NomAcc-ADP(le) (1)</li>
      <li>VERB--PRON (415)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB--NOUN (4)</li>
      <li>VERB--NOUN-Gen (10)</li>
      <li>VERB--NOUN-NomAcc (332)</li>
      <li>VERB--NOUN-NomAcc-ADP(as) (1)</li>
      <li>VERB--NOUN-NomAcc-ADP(le) (1)</li>
      <li>VERB--PRON (73)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
    </ul>
  </li>
</ul>




<h3>Relations Overview</h3>

<ul>
<li>This corpus uses 11 relation subtypes: <a>acl:relcl</a>, <a>case:voc</a>, <a>compound:prt</a>, <a>csubj:cleft</a>, <a>csubj:cop</a>, <a>flat:name</a>, <a>mark:prt</a>, <a>nmod:poss</a>, <a>obl:prep</a>, <a>obl:tmod</a>, <a>xcomp:pred</a></li>
<li>The following 2 main types are not used alone, they are always subtyped: <a>acl</a>, <a>csubj</a></li>
<li>The following 9 relation types are not used in this corpus at all: <a>iobj</a>, <a>expl</a>, <a>dislocated</a>, <a>aux</a>, <a>clf</a>, <a>orphan</a>, <a>goeswith</a>, <a>reparandum</a>, <a>dep</a></li>
</ul>
