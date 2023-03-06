# groad_app

A new Flutter project.

한림대학교 캡스톤 디자인 춘천 관광앱 flutter 이용한 프론트 코드

1. 프로젝트 요약

▶ 춘천시 관광을 소재로 하는 앱을 개발하였고, 춘천시의 주요 관광 명소를 소개하고 관광 명소들을 묶어 놓은 코스를 주행할 수 있는 시스템을 제공한다. 또한 관광 명소들 주변의 카페, 음식점, 숙소 등을 소개하여 춘천시의 경제 활성화에 기여하도록 하였으며 여행자들 사이에 후기를 공유할 수 있도록 커뮤니티 장을 마련하였다.

2. 오픈소스 사용 내역

▶ 안드로이드 스튜디오 (플러터 프레임워크(Dart))

▶ 파이참 (장고 프레임워크(Python))

▶ 피그마(Figma)

▶ MariaDB

▶ imgbb(이미지 저장소)

3. 프로젝트 목적

▶ 관광과 관련된 소재를 벤치마킹 하던 중 기존 강원도 관광 앱이 얼마전 서비스 종료를 하였고 아직 운영되고 있는 웹 사이트를 살펴보았는데 디자인, 기능, 시스템 체계 면에서 부실한 면을 보여준 것 같았다. 관광앱에 있어서 단순한 코스 정보 설명만으로는 관광객들을 끌어들여 수익을 창출할 수 없는 것을 보게 됐다. 반면에 제주도 올레 길을 코스로 짠 어플에서는 디자인, 기능, 제도 등이 모두 깔끔하고 체계적이었으며 관광객들로 하여금 이 앱을 사용하게끔 할 수 있는 동기부여 요소들이 있었다. 그래서 강원도 춘천시를 대상으로 하여 춘천시의 대표 관광 명소들을 소개하고 알리는데 있어서 이 장점을 활용하면 좋을 것 같다는 필요성을 느꼈다. 저희 팀 관광 앱은 좀 더 동적이고 실시간적인 요소를 넣어 관광객들로 하여금 적극적인 참여를 할 수 있도록 개발하는데 목적을 두었다.

4. 프로젝트 어플 화면 설명서

▶ 인트로 화면 : 어플 로고와 캐릭터를 띄워주며 3초간 보여주게 됨.

![image](https://user-images.githubusercontent.com/77048218/222997914-32de434f-4f9c-49a3-a2b0-ef3a697854db.png)

▶ 메인 화면 : 공지 배너창(포스터, 날씨 알림창), 여행 코스 둘러보기, 코스 주변 포토스팟&카페 리스트, 코스 주변 맛집&숙소 리스트, 여행자들의 후기 리스트 등 목록 나열

![image](https://user-images.githubusercontent.com/77048218/222997975-4d740060-5058-4d7f-b079-df08ace2c91e.png)
![image](https://user-images.githubusercontent.com/77048218/222998033-154b2538-9b45-4914-804c-7f1fccfac5e2.png)



▶ 메뉴 리스트: (로그인 전) 여행 정보, 여행 도우미, 자주 묻는 질문, 이용 약관, (로그인 후) 이벤트, 문의하기, 설정, 로그아웃 목록 추가 



▶ 회원가입&로그인 창: 회원 가입, 로그인 정보들은 모두 DB에 저장 후 서버를 통해 불러와 기능 작동함.



▶ 총 9개의 코스 구현 : 메인 화면의 여행 코스 둘러보기에 소개된 리스트를 선택할 시 해당 코스 화면으로 넘어감. 코스 주행을 시작하면 실시간으로 여행자의 위치정보가 GPS로 기록되며 해당 거점에서의 방문 인증을 스탬프 QR 코드를 통해 할 수 있다. 





