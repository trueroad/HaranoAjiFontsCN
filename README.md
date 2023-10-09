<!-- -*- coding: utf-8 -*- -->
# Experimental Harano Aji Fonts CN

Harano Aji Fonts CN (Harano Aji Mincho CN and Harano Aji Gothic CN)
are fonts obtained by replacing Adobe-Identity-0 (AI0) CIDs
of Source Han fonts (Source Han Serif and Source Han Sans)
with Adobe-GB1 (AG1) CIDs.

There are 14 fonts, 7 weights each for Mincho and Gothic.

## Distribution

* Japanese (JP): Adobe-Japan1
    + [
https://github.com/trueroad/HaranoAjiFonts
](https://github.com/trueroad/HaranoAjiFonts)
* (Experimental) Simplified Chinese (CN): Adobe-GB1
    + [
https://github.com/trueroad/HaranoAjiFontsCN
](https://github.com/trueroad/HaranoAjiFontsCN)
* (Experimental) Traditional Chinese (TW): Adobe-CNS1
    + [
https://github.com/trueroad/HaranoAjiFontsTW
](https://github.com/trueroad/HaranoAjiFontsTW)
* (Experimental) Korean (KR): Adobe-KR
    + [
https://github.com/trueroad/HaranoAjiFontsKR
](https://github.com/trueroad/HaranoAjiFontsKR)
* (Experimental) Korean (K1): Adobe-Korea1
    + [
https://github.com/trueroad/HaranoAjiFontsK1
](https://github.com/trueroad/HaranoAjiFontsK1)

See [
Harano Aji Fonts generator
](https://github.com/trueroad/HaranoAjiFonts-generator)
for details.

## Release Notes

* [
20231009
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20231009)
(JP, CN, TW, KR, K1)
    + Based on SourceHanSerif 2.002 (JP, CN, TW, KR, K1)
    + Support Adobe-GB1-6 (CN)
    + Update
        + SourceHanSerif 2.002
        + Adobe-GB1-6
        + ttx 4.43.1
    + Number of contained glyphs (JP)
        - No changes.
* [
20230610
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20230610)
(JP, CN, TW, KR, K1)
    + Add pre-rotated glyphs (JP, CN, TW, K1)
    + Refactor scripts
    + Update
        + python 3.9.16
        + ttx 4.39.4
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 18015
          (conversion 16867 + glyph processing 699 + pre-rotated 448
          + .notdef 1)
        - HaranoAjiGothic: 18015
          (conversion 16866 + glyph processing 700 + pre-rotated 448
          + .notdef 1)
* [
20220220
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20220220)
(JP, CN, TW, KR, K1)
    + Add glyphs by 180 and 270 (-90) degree rotation (JP)
    + Add kana similar CIDs to pwid and pwidvert (JP)
    + Fix making conversion table from GSUB single feature (CN, K1)
    + Improve adding GSUB vert substituion (JP, CN, TW, KR)
    + Update
        + ttx 4.29.1
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 17567
          (conversion 16867 + glyph processing 699 + .notdef 1)
        - HaranoAjiGothic: 17567
          (conversion 16866 + glyph processing 700 + .notdef 1)
* [
20220211
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20220211)
(CN, TW, KR, K1)
    + Improve making conversion table (CN, TW, KR, K1)
    + Update
        + ttx 4.29.1
* [
20220130
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20220130)
(JP, CN, TW, KR, K1)
    + Based on SourceHanSerif 2.001 (JP, CN, TW, KR, K1)
        + JP: CID+13729 and CID+14019 are now contained again.
    + Update
        + SourceHanSerif 2.001
        + ttx 4.29.0
        + Python 3.9.10
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 17559
          (conversion 16867 + glyph processing 691 + .notdef 1)
        - HaranoAjiGothic: 17559
          (conversion 16866 + glyph processing 692 + .notdef 1)
* [
20211103
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20211103)
(JP, CN, TW, KR, K1) test release
    + This is a test release.
        + There is a major change due to a major version up of
          SourceHanSerif 2.000.
        + JP: CID+13729 and CID+14019 are missing.
        + Please test.
    + Based on SourceHanSerif 2.000 (JP, CN, TW, KR, K1)
    + Based on SourceHanSans 2.004 (JP, CN, TW, KR, K1)
    + Update
        + SourceHanSerif 2.000
        + SourceHanSans 2.004
        + ttx 4.27.1
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 17557
          (conversion 16865 + glyph processing 691 + .notdef 1)
        - HaranoAjiGothic: 17559
          (conversion 16866 + glyph processing 692 + .notdef 1)
* [
20210410
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20210410)
(JP, CN, TW, KR, K1)
    + Based on SourceHanSans 2.003 (JP, CN, TW, KR, K1)
    + Update
        + SourceHanSans 2.003
        + ttx 4.22.0
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 17554
          (conversion 16862 + glyph processing 691 + .notdef 1)
        - HaranoAjiGothic: 17559
          (conversion 16866 + glyph processing 692 + .notdef 1)
* [
20210101
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20210101)
(JP, CN, TW, KR, K1)
    + Based on SourceHanSans 2.002 (JP, CN, TW, KR, K1)
    + Add many Kana glyphs (JP)
    + Add many GSUB features and entries (JP)
    + Update
        + SourceHanSans 2.002
        + ttx 4.18.2
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 17554
          (conversion 16862 + glyph processing 691 + .notdef 1)
        - HaranoAjiGothic: 17559
          (conversion 16867 + glyph processing 691 + .notdef 1)
* [
20200612
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20200612)
(JP, CN, TW, KR, K1)
    + Add `cmap` table from CMap such as AJ1
      and change CID in `cmap` table according to CMap (JP, CN, TW, KR, K1)
    + Add AJ1 CID+151 by copying from AJ1 CID+14 (JP)
    + Change size reducing method for size exceeded `cmap` table format 4
      (TW, KR)
    + Add `GPOS` table (KR)
    + Improve generator
    + Update
        + ttx 4.12.0
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 16888
          (conversion 16678 + glyph processing 209 + .notdef 1)
        - HaranoAjiGothic: 16893
          (conversion 16683 + glyph processing 209 + .notdef 1)
* [
20200524
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20200524)
(JP, CN, TW, KR, K1)
    + Add proportional Kana glyphs (JP)
    + Add some space glyphs (JP, KR)
    + Fix broken `GPOS` table such as palt (JP, CN, TW, KR)
    + Change width of Monospaced glyphs in **experimental** Korean font (KR)
    + Add **experimental** Korean font variation (K1)
        + Korean: Adobe-Korea1, suffix K1
            + UniKS-UTF32-H 1.008
    + Update
        + ttx 4.10.2
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 16887
          (conversion 16678 + glyph processing 208 + .notdef 1)
        - HaranoAjiGothic: 16892
          (conversion 16683 + glyph processing 208 + .notdef 1)
* [
20200516
](https://github.com/trueroad/HaranoAjiFontsCN/releases/tag/20200516)
(CN, TW, KR)
    + The generator can now generate **experimental**
      Simplified Chinese, Traditional Chinese, and Korean fonts.
    + The font name for each langulage has the two letter suffix
      same as Source Han fonts.
        + Simplified Chinese: Adobe-GB1, suffix CN
            + UniGB-UTF32-H 1.016
        + Traditional Chinese: Adobe-CNS1, suffix TW
            + UniCNS-UTF32-H 1.019
        + Korean: Adobe-KR, suffix KR
            + UniAKR-UTF32-H 1.002
    + No change for Japanese version, no release this time.
    + The suffix is used as an abbreviation for each language font.
        + The Japanese font name has no suffix,
          but the abbreviation is JP.
    + Update
        - ttx 4.10.0

## LICENSE

Copyright (C) 2019-2023
Masamichi Hosoda, with Reserved Font Name 'Harano Aji'.

Copyright 2014-2021 Adobe (http://www.adobe.com/),
with Reserved Font Name 'Source'.

Copyright 2017-2023 Adobe (http://www.adobe.com/),
with Reserved Font Name 'Source'.

Source is a trademark of Adobe in the United States and/or other countries.

This Font Software is licensed under the SIL Open Font License, Version 1.1.
See [LICENSE](LICENSE).
