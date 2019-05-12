# 프로그램 개발배경
-기숙사 외박계가 서비스 되지 않은점이 아쉬웠으며 유용하게 쓰일 수 있는 프로그램을 만들어 보고싶어 학교 채팅봇을 만들어보게 되었습니다.

# 프로그램 소개

플러스 친구 추가 후 통학버스 조회, 기숙사 식단조회, 도서관 좌석조회, 홈페이지 조회 기능을 사용할 수 있습니다.
또한 AWS EC2인스턴스를 활용하여 서비스하며 동국대학교 경주캠퍼스 채팅봇을 검색 후 친구추가가 가능합니다.

# 프로그램 동작화면

![](https://kkimsangheon.github.io/2017/08/11/dg-chat-bot/dgchat.png) 
플러스 친구 추가 후 통학버스 조회, 기숙사 식단조회, 도서관 좌석조회, 홈페이지 조회 기능을 사용할 수 있습니다.



# 프로그램 개발배경
-기숙사 외박계가 서비스 되지 않은점이 아쉬웠으며 유용하게 쓰일 수 있는 프로그램을 만들어 보고싶어 학교 채팅봇을 만들어보게 되었습니다.

# 프로그램 소개
플러스 친구 추가 후 실시간 버스 도착정보, 도서관 좌석정보, 기숙사 식단조회, 통학버스 조회, 홈페이지 조회 기능을 사용할 수 있습니다.
또한 AWS EC2인스턴스를 활용하여 서비스하며 동국대학교 경주캠퍼스 채팅봇을 검색 후 친구추가가 가능합니다.

2018-06-02 부터 EC2 인스턴스의 프리티어가 만료되어 GCP로 변경하였습니다.
2019-06-01 부터 GCP의 사용기한이 종료됨에 따라 서비스가 종료되었습니다.

# 프로그램 동작화면
![](https://kkimsangheon.github.io/2017/08/11/dg-chat-bot/1.png) 

카카오톡 내 친구검색기능을 활용하여 "동국대학교 경주캠퍼스 채팅봇"을 검색하면 위와같이 출력됩니다.

![](https://kkimsangheon.github.io/2017/08/11/dg-chat-bot/2.png) 
해당 봇과 채팅을 시도하게 되면 화면에 보이는 기능(버스 도착정보, 도서관 좌석정보, 기숙사 식단조회, 통학버스 조회, 홈페이지 조회)을 제공합니다.

![](https://kkimsangheon.github.io/2017/08/11/dg-chat-bot/3.png) 
초기 화면에서 버스도착정보 버튼을 선택하고 조회할 정류장의 숫자를 입력하게 되면 위와같이 버스도착정보를 실시간으로 조회 가능합니다.

![](https://kkimsangheon.github.io/2017/08/11/dg-chat-bot/4.png) 
초기 화면에서 도서관 좌석정보 버튼을 선택하면 다음과 같이 실시간 잔여석을 확인 가능합니다.

![](https://kkimsangheon.github.io/2017/08/11/dg-chat-bot/5.png) 
초기화면에서 기숙사 식단조회 버튼을 선택하고 아침, 점심, 저녁, 야식 메뉴중 한가지를 선택할 경우 당일의 식단 메뉴를 확인할 수 있습니다.

![](https://kkimsangheon.github.io/2017/08/11/dg-chat-bot/6.png) 
초기화면에서 통학버스 조회 버튼을 선택하고 지역(부산, 양산, 대구, 울산, 포항)을 선택하게 되면 해당 지역의 통학버스 정보를 조회할 수 있습니다.

![](https://kkimsangheon.github.io/2017/08/11/dg-chat-bot/7.png) 
초기화면에서 홈페이지 조회 버튼을 선택하고 일반, 학사, 장학 중 하나를 선택하게 되면 최근 등록된 10개의 게시물을 조회할 수 있습니다.

![](https://kkimsangheon.github.io/2017/08/11/dg-chat-bot/article.jpg) 
{% asset_img article.jpg 관련기사 %}
교내신문에 관련 기사가 실리기도 하였습니다.

# 서버
2018-06-02
기존 AWS를 사용했지만 무료이용기간이 만료되어 구글클라우드 플랫폿을 이용.

[github Repository](https://github.com/KKimSangHeon/Dg_Chat_Bot)
