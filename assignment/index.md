---
title: titles.assignment
nav:
  order: 6
  tooltip: tooltips.assignment
---
{% case site.lang %}
<!-- {% when 'jp' %}
<div style="font-size:1.6em;font-weight:bold;color:red;margin:1.5em 0;text-align:center;">
これは2025年度版です．2026年度版の公開までしばらくお待ちください．
</div>

{% when 'en' %}
<div style="font-size:1.6em;font-weight:bold;color:red;margin:1.5em 0;text-align:center;">
This is the 2025 edition. Please wait until the 2026 edition is released.
</div>
{% endcase %} -->
# {% include icon.html icon="fa-solid fa-robot" %} {%t assignment.assignment_title %}
{% case site.lang %}
{% when 'jp' %}
アドバンスド・インテリジェント・システム研究室に興味を持っていただき、まことにありがとうござ います。このページは実世界情報コースの新卒研生（3回生）のために作られたものです。

{% when 'en' %}
Thank you very much for your interest in the Advanced Intelligent Systems Laboratory. This page was created for new graduate students (3rd year students) in the Real World Information Course.
{% endcase %}
## {% include icon.html icon="fa-solid fa-circle-info" %} {%t assignment.openlab_title %}
{% case site.lang %}
{% when 'jp' %}
研究室公開期間中（<span style="color:red;">6月1日（月）〜6月10日（水）</span>）は研究室の教員と先輩たちが皆さんの要望に応じて研究室に関することなら何でも紹介します。気軽にアクセスしてみてください。
研究室公開日は，<span style="color:red;">6月4日（木）（14:55～16:30）</span>と<span style="color:red;">6月5日（金）（16:40～18:15）</span>です。どちらも研究デモ、座談会を行います。研究デモでは、講義内の研究室公開で紹介できなかったデモを目の前で紹介します。座談会では、研究室の雰囲気を感じ取れたり、普段聞けないことも質問できたりするチャンスです。ぜひ気軽に訪れてみてください。

以下から、研究室紹介用の冊子を見ることができます。
{% include button.html 
     type="external" 
     icon="fa-solid fa-eye" 
     text="研究室紹介冊子プレビュー" 
     link="/files/Lab_introduce_booklet_2026.pdf" 
     tooltip="研究室紹介冊子を見る" 
%}
{% when 'en' %}
During the laboratory open period (<span style="color:red;">June 1 (Monday) to June 10 (Wednesday), 2025</span>), the faculty and senior students of the laboratory will introduce anything related to the laboratory according to your requests. Please feel free to visit.
The laboratory open house will be held on <span style="color:red;">Thursday, June 4 (14:55–16:30)</span> and <span style="color:red;">Friday, June 5 (16:40–18:15)</span>. On both days, we will have research demonstrations and a discussion session. During the research demonstrations, we will present demos in person that could not be introduced during the in-class laboratory presentation. The discussion session will be a great opportunity to get a sense of what the lab is like and to ask questions that you might not usually have the chance to ask. Please feel free to stop by and visit us!

The laboratory introduction booklet is available below.
{% include button.html 
     type="external" 
     icon="fa-solid fa-eye" 
     text="Laboratory Introduction Booklet Preview" 
     link="/files/Lab_introduce_booklet_2026.pdf" 
     tooltip="View the Laboratory Introduction Booklet" 
%}
{% endcase %}

{% include section.html %}
## {% include icon.html icon="fa-solid fa-tags" %}{%t assignment.assignment_contents %}
{% include assignment-list.html component="assignment-card" data="recruit" filter="group == 'contents'" style="small" %}

{% include section.html %}

