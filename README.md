# Awesome Korean NLP

> 한국어 자연어처리 소프트웨어 목록

## 목차

- Arirang
- HAM
- HanNanum
- khaiii
- Kiwi
- kkma
- K-LIWC
- KoalaNLP
- KOMORAN
- KoNLP
- KoreanParser
- Korean XTAG
- KoSpacing
- KRISTAL-IRMS
- KTS
- MATCH
- mecab-ko
- nlp4kor
- Nori
- Open Korean Text Processor
- POSTAG/K
- Rhino
- Rouzeta
- Seunjeon
- soynlp
- soyspacing
- SynKDP(깜짝새)
- UMorpheme
- Utagger

---

## Arirang

루씬 한글 분석기

- [Java](https://sourceforge.net/projects/lucenekorean/)
- 이수명
- [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)

## HAM

[한국어 형태소 분석 라이브러리](http://nlp.kookmin.ac.kr/HAM/kor/ham-intr.html)

한국어 형태소 분석을 기반으로 하여 자동색인 및 철자검사 기능까지 가능한 HAM(Hangul Analysis Module)은 자동색인에 매우 적합한 형태소 분석기를 이용하기 때문에 문서의 종류나 유형에 관계없이 문서에 나타난 keyword를 추출한다.

- 강승식(국민대학교)
- 사용기간 만료(2013년 12월 31일까지)

## HanNanum

Hannanum is a morphological analyzer and a POS tagger which is plug-in component architecture-based tool.

- [Java](http://semanticweb.kaist.ac.kr/home/index.php/HanNanum)
- [KAIST 시멘틱 웹 연구실](http://semanticweb.kaist.ac.kr/home/index.php/Home)
- [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)

## khaiii

khaiii는 "Kakao Hangul Analyzer III"의 첫 글자들만 모아 만든 이름으로 카카오에서 개발한 세 번째 형태소분석기입니다. 기존 버전이 사전과 규칙에 기반해 분석을 하는 데 반해 khaiii는 데이터(혹은 기계학습) 기반의 알고리즘을 이용하여 분석을 합니다.

- [C++, Python 3](https://github.com/kakao/khaiii)
- [Kakao](http://tech.kakao.com/)
- [Apache License 2.0](https://github.com/kakao/khaiii/blob/master/LICENSE)

## Kiwi

지능형 한국어 형태소 분석기(Korean Intelligent Word Identifier)

Kiwi는 C++기반의 한국어 형태소 분석기 라이브러리입니다. 입력한 단어나 문장을 세종 품사 태그에 따라 분석하고 그 태그를 붙여줍니다. 분석기는 문어 텍스트의 경우 평균 94%의 정확도로 해당 텍스트를 분석해 낼 수 있습니다. C++기반으로 최적화되었으며 멀티스레딩을 지원하기에, 대량의 텍스트를 분석해야하는 경우 멀티코어를 활용하여 좀 더 빠르게 분석이 가능합니다.

- [C, C++, Python 3](https://github.com/bab2min/Kiwi)
- 이민철
- [LGPL 2.1](https://github.com/bab2min/Kiwi/blob/master/LICENSE)

## kkma

꼬꼬마 한국어 형태소 분석기

- [Java](http://kkma.snu.ac.kr/documents/index.jsp)
- [서울대학교 지능형 데이터 시스템 연구실](http://ids.snu.ac.kr/site/)

## K-LIWC

한국어 언어분석 프로그램

- [언어적 특성을 이용한 '심리학적 한국어 글분석 프로그램(KLIWC)' 개발 과정에 대한 고찰](http://dlps.nanet.go.kr/SearchDetailView.do?cn=KINX2005083518), 이창환(부산대학교), 심정미(부산대학교), 윤애선(부산대학교)

## KoalaNLP

KoalaNLP는 한국어 처리의 통합 인터페이스를 지향하는 Java/Kotlin/Scala Library입니다. 서로 다른 형태의 형태소 분석기를 모아, 동일한 인터페이스 아래에서 사용할 수 있도록 하는 것이 목적입니다.

- [Java, Kotlin, Node.js, Python 3, Scala](https://github.com/koalanlp/koalanlp)
- 김부근(서울대학교)
- [MIT License](https://github.com/koalanlp/koalanlp/blob/master/LICENSE.md)

## KOMORAN

Korean Morphological Analyzer

- [Java](https://github.com/shin285/KOMORAN)
- [SHINEWARE](http://www.shineware.co.kr/about/shineware/)
- [Apache License 2.0](https://github.com/shin285/KOMORAN/blob/master/LICENSE)

## KoNLP

POS Tagger and Morphological Analyzer for Korean text based research. It provides tools for corpus linguistics research such as Keystroke converter, Hangul automata, Concordance, and Mutual Information. It also provides a convenient interface for users to apply, edit and add morphological dictionary selectively.

- [R](https://github.com/haven-jeon/KoNLP)
- 전희원
- [GPL 3.0](https://github.com/haven-jeon/KoNLP/blob/master/DESCRIPTION)

## KoreanParser

A project to build a Korean syntactic parser

- [Java](http://semanticweb.kaist.ac.kr/home/index.php/KoreanParser)
- [KAIST 시멘틱 웹 연구실](http://semanticweb.kaist.ac.kr/home/index.php/Home)

## Korean XTAG

[Korean XTAG](http://www.cis.upenn.edu/~xtag/koreantag/#XTAG)

Korean XTAG is an on-going project to develop a wide-coverage grammar for Korean using Feature-Based Lexicalized Tree Adjoining Grammar (LTAG) formalism.

- [펜실베니아 대학](http://www.upenn.edu/)

## KoSpacing

Automatic Korean word spacing

KoSpacing has fairly accurate automatic word spacing performance, especially good for online text originated from SNS or SMS.

- [Python](https://github.com/haven-jeon/PyKoSpacing), [R](https://github.com/haven-jeon/KoSpacing)
- 전희원
- [GPL 3.0](https://github.com/haven-jeon/KoSpacing/blob/master/DESCRIPTION)

## KRISTAL-IRMS

[오픈소스 정보검색관리시스템](http://www.kristalinfo.com/kristal_irms.php)

KRISTAL은 과학기술문헌 정보서비스를 목적으로 개발을 시작한 정보검색관리시스템입니다. 정보검색엔진에서 출발하여 IRMS의 틀을 잡아가고 있으며 최종적으로는 DB-IR 통합을 지향하고 있습니다.

- [KISTI](https://www.kisti.re.kr/)
- [GPL, Commercial License](http://www.kristalinfo.com/kristal_licence.php)

## KTS

공개 한글 형태소 분석기

KTS는 EUC-KR, 이성진코드 기반의 한글 형태소분석기로서 1995년에 만들어진 것이 2002년에 GPL2 라이센스로 정식 공개되었습니다.

- [C, C++](https://wiki.kldp.org/wiki.php/KTS)
- 이상호(KAIST), 서정연, 오영환
- [GPL 2.0](http://www.opensource.org/licenses/gpl-2.0.php)

## MATCH

초고속 한국어 형태소 분석기

- [C, C++](http://cs.sungshin.ac.kr/~shim/demo/mach.html)
- 심광섭(성신여대)

## mecab-ko

mecab-ko는 은전한닢 프로젝트에서 사용하기 위한 MeCab의 fork 프로젝트 입니다.

최소한의 변경으로 한국어의 특성에 맞는 기능을 추가하는 것이 목표입니다.

- [C, C++](https://bitbucket.org/eunjeon/mecab-ko/)
- [은전한닢 프로젝트](http://eunjeon.blogspot.com/)
- [BSD License](https://bitbucket.org/eunjeon/mecab-ko/src/908db8de3cb5f4931b4e3a7a5a3894daefb98c37/BSD?at=master&fileviewer=file-view-default)
- [GPL 2.0](https://bitbucket.org/eunjeon/mecab-ko/src/908db8de3cb5f4931b4e3a7a5a3894daefb98c37/GPL?at=master&fileviewer=file-view-default)
- [LGPL 2.1](https://bitbucket.org/eunjeon/mecab-ko/src/908db8de3cb5f4931b4e3a7a5a3894daefb98c37/LGPL?at=master&fileviewer=file-view-default)

## nlp4kor

딥러닝을 이용한 한글 자연어 처리

- [Python 3](https://github.com/bage79/nlp4kor)
- 박혜웅
- [MIT License](https://github.com/bage79/nlp4kor/blob/master/LICENSE.md)

## Nori

Nori Korean Morphological Analyzer

- [Java](https://github.com/elastic/elasticsearch/tree/master/plugins/analysis-nori)
- Jim Ferenczi(Elastic)
- [Apache License 2.0](https://github.com/elastic/elasticsearch/blob/master/plugins/analysis-nori/licenses/lucene-LICENSE.txt)

## Open Korean Text Processor

**Official Fork of `twitter-korean-text`**

스칼라로 쓰여진 한국어 처리기입니다. 현재 텍스트 정규화와 형태소 분석, 스테밍을 지원하고 있습니다. 짧은 트윗은 물론이고 긴 글도 처리할 수 있습니다.

- [Java, Scala](https://github.com/open-korean-text/open-korean-text)
- [Apache License 2.0](https://github.com/open-korean-text/open-korean-text/blob/master/LICENSE)

## POSTAG/K

Korean Morphological Analyzer

- [POSTECH 지능형 소프트웨어 연구실](http://nlp.postech.ac.kr/home/)
- [Syllable patternbased unknown morpheme estimation for hybrid partofspeech tagging of Korean](http://nlp.postech.ac.kr/~project/DownLoad/cgi-bin/POSTAG/9908_cljournal_gblee.pdf), 이근배(POSTECH), 차정원(POSTECH), 이종혁(POSTECH)

## Rhino

RHINO parses Korean words by morpheme and part-of-speech. The newly developed Dynamic Dictionary, a programmed database, can make words to react with their context.

- [R](https://github.com/SukjaeChoi/RHINO)
- 최석재(경희대학교)
- [GPL 3.0](https://github.com/SukjaeChoi/RHINO/blob/master/DESCRIPTION)

## Rouzeta

[유한 상태 기반의 한국어 형태소 분석기](https://shleekr.github.io/)

- [How to compile Rouzeta](https://github.com/dsindex/rouzeta)
- 이상호(SK플래닛)
- [MIT License](https://opensource.org/licenses/MIT)

## Seunjeon

`mecab-ko-dic` 기반으로 만들어진 JVM 상에서 돌아가는 한국어 형태소분석기입니다. 복합명사 분해와 활용어 원형 찾기가 가능합니다.

- [Java, Scala](https://bitbucket.org/eunjeon/seunjeon)
- [은전한닢 프로젝트](http://eunjeon.blogspot.com/)
- [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)

## soynlp

한국어 자연어처리를 위한 파이썬 라이브러리입니다. 학습데이터를 이용하지 않으면서 데이터에 존재하는 단어를 찾거나, 문장을 단어열로 분해, 혹은 품사 판별을 할 수 있는 비지도학습 접근법을 지향합니다.

- [Python 3](https://github.com/lovit/soynlp)
- 김현중(서울대학교)
- [GPL 3.0](https://github.com/lovit/soynlp/blob/master/setup.py)

## soyspacing

Soyspacing은 한국어 띄어쓰기 문제를 해결하기 위한 휴리스틱 알고리즘을 제공합니다. Conditional Random Field와 비교하여 가벼운 모델 사이즈와 빠른 학습이 가능합니다.

- [Python 3](https://github.com/lovit/soyspacing)
- 김현중(서울대학교), 황성구(Scatter Lab), 신윤하(성균관대)
- [GPL 3.0](https://github.com/lovit/soyspacing/blob/master/setup.py)

## SynKDP

깜짝새: 통합형 한글 자료 처리기 [[미러]](https://wrightgongyoo.tistory.com/entry/%EB%A7%90%EB%AD%89%EC%B9%98-%EB%B6%84%EC%84%9D-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8-%EA%B9%9C%EC%A7%9D%EC%83%88-155-SynKDP)

- 소강춘(전주대학교), 김진규(전주대학교), 박진양(전주대학교)

## UMorpheme

한국어 형태소 분석기 API (Mecab Wrapper)

- [Python 2](https://pypi.org/project/UMorpheme/)
- [은전한닢 프로젝트](http://eunjeon.blogspot.com/)
- 김경훈(UNIST)
- [MIT License](https://opensource.org/licenses/MIT)

## Utagger

한국어 형태소 분석기

- [C++](http://nlplab.ulsan.ac.kr/doku.php?id=utagger)
- [울산대학교 한국어처리 연구실](http://nlplab.ulsan.ac.kr/doku.php)
