---
layout: page
title: プロジェクト / Projects
permalink: /projects/
---

---

# __[大規模欠陥データを利用したソフトウェア開発におけるプロジェクト比較の枠組みの研究](https://kaken.nii.ac.jp/ja/grant/KAKENHI-PROJECT-19K20242/)__

* ソフトウェア開発においては、ソフトウェアに不具合を与える様々な欠陥が作りこまれ、試験(テスト)によってモニタリングされる。開発中に欠陥数がどれだけ存在するかを予測する方法が数多く提案されているが、それぞれの方法は特定の状況下でのみ有効であり、条件が異なる場合に利用できない。また、ドメインや開発手法の異なるプロジェクトを対象とした評価は行われておらず、それぞれの特性を考慮したものはない。そこで様々な企業におけるソフトウェア開発で発見された欠陥情報を収集しドメインや特性に関する知見を分析しまとめ広く公開する。
  * [IssuesFromGitHub](https://github.com/kiyoshi-honda/IssuesFromGitHub)でデータを公開中。

---

# __画像認識AIはどこを見ているの？__

* さまざまな画像認識AIが提案されていますが、画像のどこを見て認識しているのでしょうか？
AIの認識箇所を特定する技術が研究されています。そこで我々は認識箇所を可視化しどこを見て認識しているかを調べました！本研究では[Grad-CAM](https://arxiv.org/pdf/1610.02391.pdf)という技術を利用しました。その結果から次の提案ができないか検討しています。
  1. 画像認識AIの精度比較: 
    * 画像内に傷があるかどうかを画像認識するAIに対して、正しく傷の箇所に注目して判断しているのか？を研究課題として評価実験をしました。Grad-CAMによってAIが注目している箇所を可視化します。この技術を利用して、金属表面画像に対する傷を学習させた二つのAIに対して評価しできます。この技術を利用することで傷以外を注目して傷と判断することがあることが分かります！
  2. 長年の経験や勘を知識へ: 
    * 経験や勘で評価していた画像認識の技術をAIで学習させ、経験による注目箇所の違いを明らかにして経験や勘を知識へに変換したいです。経験者の注目している箇所をAIを通して明らかにし知識へと変えて経験のない人でもできる技術としていきたいと考えています。

---
