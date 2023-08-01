# solvedac-svg-card

Generates a status card for solved ac.

SOLVED AC에 있는 나의 정보를 카드로 만들어줍니다.

# TODO

- 글자 색깔 커스텀 기능

# 사용 방법

아래 코드와 같이 사용하실 수 있습니다.

params: `username`

- `![](http://cse.syu.kr/api/v1/card?username=백준아이디)`

- `<img src="http://cse.syu.kr/api/v1/card?username=백준아이디" />`

- ex) `![](http://cse.syu.kr/api/v1/card?username=test1234)`

- ex) `<img src="http://cse.syu.kr/api/v1/card?username=test1234" />`

# 배경화면 커스텀 사용 방법

아래 코드와 같이 사용하실 수 있습니다.

params: `username`, `bgc1`, `bgc2`, `bgc3`

- `![](http://cse.syu.kr/api/v1/card?username=백준아이디&bgc1=헥스코드&bgc2=헥스코드&bgc3=헥스코드)`

- `<img src="http://cse.syu.kr/api/v1/card?username=백준아이디&bgc1=헥스코드&bgc2=헥스코드&bgc3=헥스코드" />`

- ex) `![](http://cse.syu.kr/api/v1/card?username=test1234&bgc1=322653&bgc2=8062D6&bgc3=9288F8)`

- ex) `<img src="http://cse.syu.kr/api/v1/card?username=test1234&bgc1=322653&bgc2=8062D6&bgc3=9288F8" />`

# 티어 별 디자인

아래에 있는 카드는 예시를 위한 것뿐 무작위로 설정된 아이디 입니다.

<img src="http://cse.syu.kr/api/v1/card?username=cki86201" />
<img src="http://cse.syu.kr/api/v1/card?username=flappybird&bgc1=311D3F&bgc2=A076F9&bgc3=D7BBF5" />
<img src="http://cse.syu.kr/api/v1/card?username=devluyten&bgc1=FF0060&bgc2=FFD93D&bgc3=F6F1E9" />
<img src="http://cse.syu.kr/api/v1/card?username=cdt416z&bgc1=54B435&bgc2=82CD47&bgc3=F0FF42" />
<img src="http://cse.syu.kr/api/v1/card?username=eunhxa&bgc1=00FFD1&bgc2=00D7FF&bgc3=72FFFF" />
<img src="http://cse.syu.kr/api/v1/card?username=wjdrh0222&bgc1=6096B4&bgc2=5800FF&bgc3=222831" />
<img src="http://cse.syu.kr/api/v1/card?username=k4n9jun3&bgc1=FF55BB&bgc2=DEFCF9&bgc3=D800A6" />

# FIXED

- 갱신으로 인한 header cache control age 3200초 변경

- 스크린 크기가 작은 경우 클래스 티어 사진 깨짐 해결

- SSL 인증서 발급 및 적용, HTTP - > HTTPS 보안 문제 해결

- 티어 글자 크기 수정 및 가운데 정렬
