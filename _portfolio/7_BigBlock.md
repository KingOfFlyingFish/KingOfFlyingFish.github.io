---
layout: post
title: Big Block
#feature-img: "assets/img/portfolio/11_BigBlock.png"
img: "assets/img/portfolio/7_BigBlock.png"
date: 2017-08-31
tags: [Big Block, Portfolio]
---

<center><iframe width="853" height="480" src="https://www.youtube.com/embed/aI7AEghwUlg" frameborder="0" allowfullscreen></iframe></center>

---

### 프로젝트 소개

블럭을 알맞게 끼워맞춰 숨겨져있는 그림을 찾는 게임입니다. 행성을 꾸며나가는 Normal 모드와, 커다란 그림을 모두 맞춰 일러스트를 획득하고 스토리를 진행해 나아가는 Bigmap 모드로 나누어져 있습니다. 또한 숙련자를 위해 블럭을 회전시켜 맞춰야 하는 톱니 행성이 있으며, 반대로 초보자를 위해 시작 시 자동으로 몇 개의 블럭을 맞춰주는 초보 모드도 있습니다. 

BigBlock은 UGUI의 캔버스 내에서 모든 기능을 구현하였습니다. 하단 블럭 선택 메뉴와 게임 부분을 명확하게 나누기 쉽지 않고, 블럭을 터치하고 드래그하여 움직이는 부분을 이벤트 시스템으로 쉽게 구현할 수 있다고 생각했기 때문입니다. 그로 인해 개발 구조가 상당히 심플해진 대신, 확실히 일반 씬에서 구현한 것보다 리소스를 더 많이 소비하였습니다. UI만의 앵커 포인트나 피벗 포인트 등 각종 계산이 더해져 어찌보면 당연한 일일수도 있습니다. 작은 퍼즐 게임이라 큰 문제는 없었지만 큰 규모가 있는 게임이나, 많은 리소스를 사용해야 하는 게임에서는 이러한 개발 방식은 지양해야 한다는 교훈을 얻었습니다.

BigBlock은 Android와 iOS로 출시되었습니다.

핵심 기능 소개

> * 어드민
>    * 블럭 생성 기능
>    * 블럭 회전 기능
>    * 빈칸 및 중복 타일 체크 기능
>    * 스테이지 저장 기능

>* 게임
>    * 스테이지 생성
>    * 힌트 및 초보 모드
>    * 세이더를 이용한 일러스트 획득 애니메이션(흑백-> 컬러)


---

### 마켓 다운로드 주소

* Android - [바로가기](https://play.google.com/store/apps/details?id=com.gamefox.bigblock)
* iOS - [바로가기](https://itunes.apple.com/us/app/big-block-puzzle/id1278824613?ls=1&mt=8)

---

### 게임 소개

![image]({{ site.baseurl }}/{{ "assets/img/screenshot/bigblock/mainimage.png" }}) 

지구 종말의 날, 늦잠 때문에 지구를 탈출하는 우주선을 놓쳐버린 고양이 캐럿. 지나가던 U.F.O.가 캐럿을 구조하게 되면서 같이 주인을 찾는 여행을 떠나게 되는데...과연 고양이 캐럿이 주인과 다시 만날 수 있을까요?

빅 블록은 스토리형 블록 퍼즐 게임으로 게임을 진행할수록 다양한 캐릭터와 개성있는 그림들을 감상할 수 있습니다. 가볍게 즐길 수 있는 쉬운 난이도부터 아무나 풀 수 없는 전문가용 난이도까지 다양한 레벨이 모두 무료입니다.

