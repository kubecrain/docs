---
layout: post
title: "Python IDE 뭘 쓸까?"
date: 2020-04-09
categories:
    - python
tags:
    - python
    - IDE
---

> Most Pipular Python IDE, Editors
>
> ![Most Pipular Python IDE, Editors](https://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1561996940/ide3_zy6tat.jpg)
> ![Most Popular Python IDE/Editors by Employment](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2FcGxanw%2FbtqARi6ezpS%2F7M4rAVoDlTwMNXxb0t1HcK%2Fimg.jpg)
> ![Most Popular Python IDE/Editors by Region](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2FwxWpk%2FbtqAQNljtNn%2Fyn16am9wEzu0Ih68bKtvKk%2Fimg.jpg)

## Compare
특이하게 Python IDE의 경우 Jupyter를 제외하면 점유율의 차이가 크지 않습니다.
아래의 핵심 키워드를 기준으로 비교하였습니다. Sublime Text와 같은 전용 IDE가 아니거나 공식 지원되는 Plugin이 없는 경우는 제외하였습니다.

> **핵심 비교 키워드**
>
> 구동방식, 특징(무겁다 vs 가볍다, Plugin 확장 여부, 장단점 등), 유료여부, 지원 OS

이름|구동방식|특징|License or 가격|지원 OS|비고
--|--|--|--|--|--
Jupyter|Web|Web에서 Markdown 에디터를 이용해 자유로운 편집이 가능합니다. Notebook 형태여서 메모가 쉽고, 공부에 용이한 반면 실제 프로그래밍에는 어려움이 있습니다.<br/> .ipynb 확장자로 저장이 되기 때문에 변환을 해주어야 하는 번거러움이 있습니다.|BSD 3-Clause|-|K8S에 인스턴스로 올려 간단한 코드 수정 용도로 적합해 보입니다.<br/> [Home Page](https://jupyter.org/)
PyCharm|응용프로그램|설치형 IDE 중 가장 많이 사용하는 IDE 입니다. 유료 소프트웨어이지만 일부 기능은 무료로 사용 가능합니다.(커뮤니티 버전) 하지만 안타깝게도 커뮤니티 버전에선 웹 개발 및 웹 프레임워크를 지원하는 기능들이 제공되지 않습니다.<br/> 활발한 커뮤니티 지원, 강력한 자동완성 기능 및 디버깅 기능이 지원 되지만 로딩이 느리고 무겁다는 평이 많습니다.|$199/년|Windows, Mac, Linux|[Home Page](https://www.jetbrains.com/ko-kr/pycharm/)
Spyder|응용프로그램|Data 과학 전문가들을 위해 제작되었습니다. Anaconda 라이브러리가 사전 설치되어 있어야만 합니다.|MIT|Windows, Mac, Linux|[Home Page](https://www.spyder-ide.org/)
VSCode|응용프로그램|Multi Language 지원, 4700개 이상의 확장 Plugin을 보유, 강력한 자동완성 기능 및 디버깅 기능 지원, Git Controller가 내장되어 있습니다. 다른 IDE 들에 비해 가볍다는 장점이 있지만 큰 코드파일을 처리하는데는 부적합합 니다.|MIT|Windows, Mac, Linux|[Home Page](https://code.visualstudio.com/)<br/> [GitHub](https://github.com/Microsoft/vscode/)
THEIA|Web|Multi Language 지원, Terminal 통합, Flexible Layout, VSCode가 구현한 opensource monaco를 기반으로 하여 흡사한 UI를 가지고 있고, 확장 Plugin들을 그대로 쓸 수 있습니다.<br/> Electron으로 설치형으로도 사용 가능합니다.|EPL-2.0 OR GPL-2.0 WITH Classpath-exception-2.0|-|[Home Page](https://theia-ide.org/)<br/> [Github](https://github.com/eclipse-theia/theia) <br/> [yangster(Electron Application) Github](https://github.com/theia-ide/yangster-electron)

참고 페이지
- <https://www.datacamp.com/community/tutorials/top-python-ides-for-2019>
- <https://hackr.io/blog/best-python-ide>