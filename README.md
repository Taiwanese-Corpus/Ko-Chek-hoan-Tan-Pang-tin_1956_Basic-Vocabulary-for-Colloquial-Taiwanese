# Basic Vocabulary for Colloquial Taiwanese 台灣白話基礎語句 Ko Chek-hòan, Tân Pang-tìn 1956 
[![Build Status](https://travis-ci.org/Taiwanese-Corpus/Ko-Chek-hoan-Tan-Pang-tin_1956_Basic-Vocabulary-for-Colloquial-Taiwanese.svg?branch=master)](https://travis-ci.org/Taiwanese-Corpus/Ko-Chek-hoan-Tan-Pang-tin_1956_Basic-Vocabulary-for-Colloquial-Taiwanese)

## 原始網站
- 對楊允言老師的『[台語文記憶](http://ip194097.ntcu.edu.tw/memory/TGB/thak.asp?id=862)』計畫網站引用

## 數位化版本
- [ChhoeTaigi計劃](https://github.com/ChhoeTaigi/ChhoeTaigiDatabase#8-%E5%8F%B0%E7%81%A3%E7%99%BD%E8%A9%B1%E5%9F%BA%E7%A4%8E%E8%AA%9E%E5%8F%A5)
```
【台灣白話基礎語句】
（A Basic Vocabulary for a Beginner in Taiwanese）
原作者：Ko Chek-hoàn（高積煥）、Tân Pang-tìn（陳邦鎮）
數位化kap編修：Lîm Bûn-cheng、Tēⁿ Tì-têng、Tân Kim-hoa、Chiúⁿ Ji̍t-êng
以 姓名標示-Sio-kâng方式分享 4.0 國際 (CC BY-SA 4.0) 授權
https://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW
```

## 原網站鏡像指令
```
wget -r -l inf --page-requisites --no-parent --convert-links --adjust-extension --reject='mowt.asp','Tgb.asp' http://ip194097.ntcu.edu.tw/memory/TGB/thak.asp?id=862
rename 's/_.*_/_頁面_/g' ip194097.ntcu.edu.tw/memory/TGB/data/TOPOKCGK/*
find ip194097.ntcu.edu.tw/ -name '*html' -exec bash -c "iconv -f big5 -t utf8 '{}' > a.html && mv a.html '{}'" \;
find ip194097.ntcu.edu.tw/ -name '*html' -exec sed 's/big5/utf-8/g' -i {} \;
```
鏡像站：[gh-pages](https://taiwanese-corpus.github.io/Ko-Chek-hoan-Tan-Pang-tin_1956_Basic-Vocabulary-for-Colloquial-Taiwanese/memory/TGB/thak.asp%3Fid=862.html)
