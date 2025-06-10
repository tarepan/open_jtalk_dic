<div align="center">

# 📖 Dictionary for Open JTalk 🎵 <!-- omit in toc -->

*Dictionary for Open JTalk*, Japanese word/morpheme dictionary with accents.  
*Dictionary for Open JTalk* はアクセント情報を持った形態素解析向け日本語辞書です。  

</div>

## About this repository
This repository is unofficial clone of *Dictionary for Open JTalk* (`open_jtalk_dic`).  
*Dictionary for Open JTalk* has many versions, so this repository controls these versions with `git`.  
You can easily browse dictionary entries, check diffs, clone for your project 😉  

## Contents list
Extracted *Dictionary for Open JTalk*, `open_jtalk_dic`, is under [`open_jtalk_dic_utf_8-RAW` branch](https://github.com/tarepan/open_jtalk_dic/tree/open_jtalk_dic_utf_8-RAW) without any modification, except for v1.11's `sys.dic`[^v111sysdic].  

Full list of versions is below.  

| `open_jtalk_dic` |
| :--------------: |
|      v1.11       |
|      v1.10       |
|      v1.09       |
|      v1.08       |
|      v1.07       |
|      v1.06       |
|      v1.05       |
|      v1.04       |
|      v1.03       |
|      v1.02       |
|                  |
|      v1.00       |

All versions have version tags.  

[^v111sysdic]: `sys.dic` became too big for git in v1.11. Replaced by same name placeholder.

## About Dictionary for Open JTalk
*Dictionary for Open JTalk* is officially-pre-compiled dictionary of *Open JTalk*[^def].  
The dictionary is derivatives of *NAIST-jdic* (cf. [unofficial git](https://github.com/tarepan/NAIST-jdic)), with entry modification including accents.  
The dictionary is distributed as `.tar.gz`. When extracted, some files are binary formats, some files are text formats.  

[^def]: "Dictionary for Open JTalk version 1.11 (25 December, 2018) ... If you cannot compile dictionary, you can use compiled dictionaries as follows." from [official cite](https://open-jtalk.sourceforge.net/)

## Origin
[Original *Open JTalk* project page](https://open-jtalk.sourceforge.net/) is alive at 2025-06-10.  
All source codes are cloned from [SourceForge](https://sourceforge.net/projects/open-jtalk/files/Dictionary/).  
I'd like to express my gratitude to everyone concerned.  

## How to Make
1. Download all version (`_utf_8` variants) from [SourceForge](https://sourceforge.net/projects/open-jtalk/files/Dictionary/)
2. Expand these `.tar.gz`
3. Commit raws with tag
<!-- 4. Make UTF-8 variants with `./eucjp_to_utf8.py` and manual PDF move
5. Commit them -->