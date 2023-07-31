# solvedac-svg-card

Generates a status card for solved ac.

SOLVED AC에 있는 나의 정보를 카드로 만들어줍니다.

# TODO

- 글자 색깔 커스텀 기능

- 배경화면 그라데이션 색깔 커스텀 기능

# 사용 방법

아래 코드와 같이 사용하실 수 있습니다.

- `![](http://cse.syu.kr/api/v1/card?username=백준아이디)`

- `<img src="http://cse.syu.kr/api/v1/card?username=백준아이디" />`

- ex) `![](http://cse.syu.kr/api/v1/card?username=test1234)`

- ex) `<img src="http://cse.syu.kr/api/v1/card?username=test1234" />`

# 티어 별 디자인

아래에 있는 카드는 예시를 위한 것뿐 무작위 아이디임을 알려드립니다.

<img src="http://cse.syu.kr/api/v1/card?username=cki86201" />
<img src="http://cse.syu.kr/api/v1/card?username=flappybird" />
<img src="http://cse.syu.kr/api/v1/card?username=devluyten" />
<img src="http://cse.syu.kr/api/v1/card?username=cdt416z" />
<img src="http://cse.syu.kr/api/v1/card?username=eunhxa" />
<img src="http://cse.syu.kr/api/v1/card?username=wjdrh0222" />
<img src="http://cse.syu.kr/api/v1/card?username=k4n9jun3" />

# FIXED

- 갱신으로 인한 header cache control age 3200초 변경

- 스크린 크기가 작은 경우 클래스 티어 사진 깨짐 해결

- SSL 인증서 발급 및 적용, HTTP - > HTTPS 보안 문제 해결
