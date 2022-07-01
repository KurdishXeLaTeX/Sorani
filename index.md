---
layout: default
title: سەرەتا
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

## بە خێر بێن بۆ
# گرووپی بەکارهێنەرە کوردەکانی XeLaTeX
{: .fs-9 }

مەبەستی سەرەکیـی ئەم گرووپە پەرە پێدان و ناساندنی سیستمی پێکهێنانی دەقی TeX و بە تایبەت XeLaTeX بە کۆمەڵگای زانستیـی کوردییە.
{: .fs-6 .fw-300 }

<!-- [دەست پێ کردن](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/pmarsceill/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 } -->

---

## TeX چییە؟

[TeX](https://en.wikipedia.org/wiki/TeX){:target="_blank"} سیستەمێکی ئامادەکردنی بەڵگەیە کە تێیدا نووسەر لە دەقی ساکار لەگەڵ نیشانەگەلی تایبەتی بۆ نووسین کەڵک وەردەگرێ. ئەم بۆچوونە جیاوازە لە شێوازی دیکەی دەست وەردانی دەق کە تێیدا هەر شتێک بێتە چاو هەر ئەو شتەیە کە چاپ دەبێ و وەکوو ئاکامی بەڵگەکە نیشان دەدرێ. بۆیەش بە ئینگلیسی بەم شێوازە دەڵێن *what you see is what you get*، یان بە کورتی [WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG){:target="_blank"}. Microsoft Word نموونەیەکی ناسراوە کە لەم شێوازە کەڵک وەردەگرێ.

TeX بۆ یەکەم جار لە ساڵی ١٩٧٨ لە لایەنی زانا و بلیمەتی کۆمپیوتەر دۆناڵد کنووس [Donald Knuth](https://en.wikipedia.org/wiki/Donald_Knuth){:target="_blank"} ەوە ساز کرا. TeX لە سەر ئەو بۆچوونەدا پێکهاتووە کە نووسەر دەبێ کاری نووسین بکا نەک ڕازاندنەوەی دەق. واتە، بۆ نووسەری بەڵگەیەک دەبێ ئەو ئامێرانە دابین کرابێ کە بتوانێ بە هەموو پێداویستییەکانی لە نووسیندا بگا، بگرە بۆ نووسینی فرمووڵێکی بیرکاری بێ یان هاوکێشەیەکی کیمیایی یان پارچە شیعرێک. بۆیەش، لە نێو ئاکادیمیا و ئەو کەسانه کە بە لێهاتوویی لە سەر بابەتێکی زانستی دەنووسن لە TeX زۆر بە بەربڵاوی کەڵک وەردەگیردرێ. وشەی TeX لە وشەی یۆنانی *τέχνη* یەوە دێ کە بە مانای هونەرە. لە بەر ئەوەی فۆنیمی χ لە کوردی و زۆر زماندا بەرانبەرێکی نییە، دەتوانین لە کوردی بڵەین *تێک* یان *تێخ*.

تایبەتمەندییەکانی TeX بە کورتی، لە تایبەتیمەندییە هەرە گرینگەکانی تێک ئەمانەن:

<ul>
  <li><span> نووسینی گۆڤار، کتێب، ڕاپۆرتی تەکنیکی و سڵایدی ئامادەکاری</span></li>
  <li><span> بەڕێوە بردنی بەڵگە گەورەکان کە زۆر بەش و بەند و سەرچاوەیان تێدایە</span></li>
  <li><span>  نووسینەوەی فرمووڵە پڕ وردەکارییەکان لە بیرکاریدا</span></li>
  <li><span> سازکردنی ئۆتۆماتیکی سەرچاوەکان</span></li>
  <li><span> بە ئاسانی کەڵک وەرگرتن لە وێنە و دیاگرام</span></li>
  <li><span>  گۆڕانەوە بە شێوەکانی دیکەی نیشان دانی دەق وەکوو HTML</span></li>
</ul>

هەر لە سەر بنەمای TeX ەوە، دواتر چەندین بەرهەمی دیکە دابین کران کە تێیاندا تایبەتمەندیگەلی زۆرتر ڕە چاو دەگیردرێ، وەکوو نووسین بە زمانانی دیکە و بە ڕێنووسی جیاواز لە ڕێنووسی لاتین.  [LaTeX](https://en.wikipedia.org/wiki/LaTeX){:target="_blank"} و [XeLaTeX](https://en.wikipedia.org/wiki/XeTeX){:target="_blank"} دوو نموونەی بەنێوبانگن کە بە تایبەت لەم سەردەمەدا کەڵکیان لێ وەردەگیردرێ.


## چۆن TeX بە کار بێنم؟

بۆ کەڵک وەرگرتن لە TeX لە سەر کۆمپیوتەرەکەت لە پێش هەموو شتێک دەبێ بەرنامەکەت دامەزراندبێ. بەڵگەیەکی ساکار بە LaTeX لە وێنەی دا نیشان دراوە.

```tex
\documentclass{article}
\usepackage[utf8]{inputenc}

\title{An Example}
\author{Sina Ahmadi}
\date{\today}

\begin{document}

\maketitle
\section{Introduction}

This is a minimal working example in \LaTeX.

\section{Conclusion}

The joy of writing Kurdish in \TeX.

\end{document}
```


ئێستە پرسیار ئەوەیە ئایا هەر ئەم شێوەیەش دەتوانین بۆ نووسینی کوردی بە کار بێنین؟ سەرنج دەن کە لەو نموونەیەدا لە وێنەی X کە لە سەرێ دیتمان، نە مێژوو، نە ژمارەی بەشەکان و نە تەنانەت ئەوەی کە بابەتەکە لە کوێی بەڵگەکەدا بێ و قەبارەی لاپەڕەکە چۆن بێ بە ئێمە جێبەجێ نەکراوە. واتە، TeX بۆ خۆی بەڵگەکەمان بە هەموو ئەو وردەکارییانەوە ساز دەکا. جا بۆیە، ئەو کەسانەی کە چێژی کار کردن بە تێک دەچێژن، قەت ناتوانن بگەڕێنەوە سەر سیستمانی پێکهێنانی دەق (typesetting)  ی دیکە وەکوو Microsoft Office! بۆ ئەوەی زۆرتر لەگەڵ پێکهاتەکانی بەڵگەکان لە TeX ئاشنا بن چاو لە بکەن.



## XeLaTeX بۆ نووسینی کوردی

 کێشەیەک کە پێشتر لە بە کار هێنانی  TeX دا هەبوو، بە کار هێنانی زمانان و رێنووسانی دیکە بوو. XeLaTeX سیستمێکە کە لە سەر TeX ەوە ساز کراوە و بڕیار وایە کە لە یوونیکۆد بۆ نووسینی هەموو زمانێک کەڵک وەرگرێ. بۆیە بە خۆشحاڵییەوە دەتوانین لە جوانیـی سیستمی پێکهێنانی دەقی TeX بۆ نووسینی کوردی کەڵک وەرگرین.

[`Polyglossia`](https://github.com/reutenauer/polyglossia){:target="_blank"}  پەکەیجێکە کە بۆ بەکار هێنانی زمانە جۆراوجۆرەکان لە XeLaTeX ساز کراوە.   زمانی کوردی چەندین زاراوە و ڕێنووسی هەیە. لەم دۆخەدا، دوو زاراوەمان لەو پەکەیجە بۆ کوردی زیاد کردووە: سۆرانی و کرمانجی. بۆ هەر دوو زاراوەکەش، دوو ڕێنووسی لاتین و عەرەبی دابین کراوە. واتە، ئەگەر بەڵگەیەک سۆرانی بێ، بە هەر دوو ڕێنووسەکە دەتوانن بنووسن، بۆ کرمانجیش هەر بەو شێوەیە. بۆ بە کار هێنانی کوردی، بەڵگەکەتان دەبێ بەم شێوەیە بێ:

```tex
1  \documentclass{article}
2  \usepackage{polyglossia}
3  \setmainfont{Times New Roman}
4  \setdefaultlanguage[variant=sorani,script=arabic,numerals=eastern]{kurdish}
5  \title{نووسراوەیەکی من}
6  \author{نێوی من}
7  \date{\today}
8
9  \begin{document}
10
11  \maketitle
12
13  \end{document}
```


دەبێ بەڵگەکەتان بەو هەڵبژاردانە پێک بێنن کە لە هێڵی ٤دا دیاری کراوە کە لێیدا زاراوە، ڕێنووس و شێوەی ژمارەکان دیاری دەکەن. خشتەی  خوارەوە سەرجەم هەڵبژاردەکان نیشان دەدا کە لە دوایین وەشانی کوردی لە سەر
`Polyglossia` دا هەیە.

| Polyglossia name        | variant          | script | numerals |
|:-------------|:------------------|:------| :------- |
| Kurdish          | sorani | arabic, latin  | eastern, western |
| Kurdish | kurmanji  | arabic, latin  | eastern, western |



کەوا بوو، بۆ نموونە، ئەگەر بتانهەوێ بەڵگەیەک بە کرمانجی بنووسن و لە ڕێنووسی لاتین کەڵک وەرگرن، دەتوانن هێڵی ٤ بەم شێوەیە بگۆڕن:

```tex
 \setdefaultlanguage[variant=kurmanji,script=latin,numerals=western]{kurdish}
```

لە وەشانی ئێستادا، تەنیا ڕۆژژمێری زایینی دەتوانێ بە کار بهێندرێ. جێگای سەرنجە کە دوو شێواز هەن بۆ نیشان دانی مێژوو: `\today` و `\ontoday` . لە شێوازی یەکەمدا، تەنیا نێوی مانگەکە و ژمارەی ڕۆژ و ساڵ دێن. لە شێوازی دواییندا، لە نێوان سێ بەشەکە *î/y* ی ئیزافە دادەنرێ. ئەمە تەنیا لە ڕێنووسی لاتیندا دەکرێ.

بۆ زانیاریی زۆرتر لە سەر پێکهاتەکانی `Polyglossia`ی کوردی، چاو [لەم گوتار](https://kurdishxelatex.github.io/assets/Kurdish_XeLaTeX_English.pdf)ە بکە.

## بەڵگەکان

XeLaTeX ی کوردی ساز کراوە چاو لێ بکەن.
 لێرەدا دەتوانین چەند بەڵگە کە بە

 <ul>
   <li>
     <span>
     سۆرانی - ڕێنووسی عەرەبی
     (<a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/Kurdish_XeLaTeX_Sorani_Arabic.pdf" rel="noopener noreferrer" target="_blank">pdf</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/Kurdish_XeLaTeX_Sorani_Arabic.tex" rel="noopener noreferrer" target="_blank">tex</a>)
     </span>
   </li>
   <li>
     <span>
     سۆرانی - ڕێنووسی لاتین
     (<a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/Kurdish_XeLaTeX_Sorani_Latin.pdf" rel="noopener noreferrer" target="_blank">pdf</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/Kurdish_XeLaTeX_Sorani_Latin.tex" rel="noopener noreferrer" target="_blank">tex</a>)
     </span>
   </li>
   <li>
     <span>
     کورمانجی - ڕێنووسی لاتین
     (<a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/Kurdish_XeLaTeX_Kurmanji_Latin.pdf" rel="noopener noreferrer" target="_blank">pdf</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/Kurdish_XeLaTeX_Kurmanji_Latin.tex" rel="noopener noreferrer" target="_blank">tex</a>)
     </span>
   </li>
   <li>
     <span>
     کورمانجی - ڕێنووسی عەرەبی
 	(<a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/Kurdish_XeLaTeX_Kurmanji_Arabic.pdf" rel="noopener noreferrer" target="_blank">pdf</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/Kurdish_XeLaTeX_Kurmanji_Arabic.tex" rel="noopener noreferrer" target="_blank">tex</a>)
     </span>
   </li>
 </ul>


چەند نموونەی دیکەش لە لایەنی بەکارهێنەرە بەڕێزەکان ساز کراون کە دەتوانن بە کاریان بێنن. سپاسی تایبەت بۆ کاک هەتوان خالید بۆ ئامادەکردنی ئەو نموونانەی خوارەوە بە سۆرانی: 

<ul>
    <li>
      <span>
      نموونەیەک لە وتارێک لە سەر بیرکاری: (<a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/sin_math_Sorani_Arab.tex" rel="noopener noreferrer" target="_blank">tex</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/sin_math_Sorani_Arab.pdf" rel="noopener noreferrer" target="_blank">pdf</a>). 
      </span>
    </li>
    <li>
      <span>
      بەڵگەی تاقی کردنەوە بە خشتەوە: (<a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/exam_Sorani_Arabic.tex" rel="noopener noreferrer" target="_blank">tex</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/exam_Sorani_Arabic.pdf" rel="noopener noreferrer" target="_blank">pdf</a>).
      </span>
    </li>
    <li>
      <span>
      نموونەیەک بۆ کێشانەوەی دار یان گراف:  <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/tree_Sorani_Arabic.tex" rel="noopener noreferrer" target="_blank">tex</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/tree_Sorani_Arabic.pdf" rel="noopener noreferrer" target="_blank">pdf</a>. 
      </span>
    </li>
    <li>
      <span>
      نموونەیەک بۆ کێشانەوەی چارت یان هێڵکاری: <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/plots_Sorani_Arabic.tex" rel="noopener noreferrer" target="_blank">tex</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/plots_Sorani_Arabic.pdf" rel="noopener noreferrer" target="_blank">pdf</a>. 
      </span>
    </li>
    <li>
      <span>
      نموونەیەک بۆ کێشانەوەی هێڵکاریی سێگۆشە:  <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/triangle_Sorani_Arabic.tex" rel="noopener noreferrer" target="_blank">tex</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/triangle_Sorani_Arabic.pdf" rel="noopener noreferrer" target="_blank">pdf</a>. 
      </span>
    </li>
    <li>
      <span>
      نموونەیەک بۆ کێشانەوەی هێڵکاریی کولێرەیی:  <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/piecharts_Sorani_Arabic.tex" rel="noopener noreferrer" target="_blank">tex</a> | <a href="https://github.com/KurdishXeLaTeX/Support/blob/master/docs/piecharts_Sorani_Arabic.pdf" rel="noopener noreferrer" target="_blank">pdf</a>. 
      </span>
    </li>
</ul>


### هەواڵێکی خۆش ☺️🎉
**هەتوان خالید**، خوێندکاری فیزیا لە زانکۆی کۆیە، کتێبێکی لە سەر بەکارهێنانی لاتێک بە کوردی نووسیوە. زۆری سپاس دەکەم بۆ کات و سەرنجی و تێکۆشینی خۆبەخشانەی و هیوام سەرکەوتنی وی و هەموو هۆگرانی زانست لە کۆمەڵگای کوردییە. ئافەرین، هەتوان!

[فەرموو لێرەوە کتێبە کە خۆڕایی داگرە!](https://raw.githubusercontent.com/KurdishXeLaTeX/kurdishxelatex.github.io/master/assets/Learn_Latex_Kurdish-Hatwan_Khalid-V01-2022.pdf){:target="_blank"}.

<a href="https://raw.githubusercontent.com/KurdishXeLaTeX/kurdishxelatex.github.io/master/assets/Learn_Latex_Kurdish-Hatwan_Khalid-V01-2022.pdf" target="_blank">
  <img src="https://raw.githubusercontent.com/KurdishXeLaTeX/kurdishxelatex.github.io/master/assets/Learn_Latex_Kurdish-Hatwan_Khalid-V01-2022_cover.png" 
       width="400" 
       height="500"
       alt= "Hatwan Khalid Learn LaTeX Kurdish book cover"/>
</a>

---

## سەبارەت بەم پڕۆژەیە

TeX بۆ کۆمەڵگای زانستیی کوردییە.  مەبەستی سەرەکیی ئەم پڕۆژەی پەرە پێدان و زیاد کردنی زانیاری سەبارەت بە سیستمانی پێکهێنانی دەقی
دەتوانن چاو لە ماڵپەڕەکەمان بە [ئینگلیسی](https://kurdishxelatex.github.io){:target="_blank"} و  [کرمانجی](https://kurdishxelatex.github.io/Kurmanji){:target="_blank"} یش بکەن.

لە سەر ئەم پڕۆژەیە، وتارێک بە نێوی "پەرەپێدانی لاتێک بۆ کوردی" لە گۆڤاری هۆژین بڵاو کراوەتەوە کە دەتوانن [لێرەدا](https://hojan.org/j09/b14/) بیبیسن یان [لێرەدا](https://hojan.org/hojin/mag-no-9-10/) گۆڤارەکە بدۆزنەوە.

## بەشداری

ئەگەر TeX تان پێ خۆشە، لێی دەزانن یان دەتانهەوێ لێی بزانن و هەروەها کوردی ئاخێون، تکایە بەشداری لەم پڕۆژەیە بکەن. ئەم پڕۆژەیە خۆبەخشانە لە لایەنی بەشدارانی تامەزرۆوە بە ڕێوە دەچێ. گرووپی پڕۆژەکە: [https://groups.google.com/forum/#!forum/kurdishxelatexusersgroup](https://groups.google.com/forum/#!forum/kurdishxelatexusersgroup){:target="_blank"}

تکاتە پرسیارەکان یا کێشەکانتان پێمان ڕابگەیەنن.

<!-- Read more about becoming a contributor in [our GitHub repo](https://github.com/pmarsceill/just-the-docs#contributing). -->

#### سپاس بۆ هەموو بەشدار بووان




<script src='https://storage.ko-fi.com/cdn/scripts/overlay-widget.js'></script>
<script>
  kofiWidgetOverlay.draw('sinaahmadi', {
    'type': 'floating-chat',
    'floating-chat.donateButton.text': 'Support me',
    'floating-chat.donateButton.background-color': '#00b9fe',
    'floating-chat.donateButton.text-color': '#fff'
  });
</script>

