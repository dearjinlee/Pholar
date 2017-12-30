# PHOLAR Lite.

## 소개
Firebase 의 주요 기능 공부를 목적으로 네이버 소셜 포토블로그 앱인 'PHOLAR' 를 카피하기로 했습니다.</br></br>
__PHOLAR Lite.__ 는 사진 공유 SNS 로 유저가 사진을 필수로 한 글을 작성하고, 그 글을 통해 사람들과 소통하는 APP 입니다.</br></br>
일주일이라는 짧은 기간 동안 개발을 통해 특수한 기능들을 빼고, 기존에 학습했던 기능들과
배워보고 싶고, 사용해보고 싶은 기능들을 위주로 구현하였습니다.</br>

## 요약

![Skills&Library](https://github.com/Heepie/Pholar/blob/master/img/table.png)

## 화면

![screenshot1](https://github.com/Heepie/Pholar/blob/master/img/screen1.PNG)
![screenshot2](https://github.com/Heepie/Pholar/blob/master/img/screen2.PNG)
![screenshot3](https://github.com/Heepie/Pholar/blob/master/img/screen3.PNG)
![screenshot4](https://github.com/Heepie/Pholar/blob/master/img/screen4.PNG)

## 소스 코드

  - [전체 소스코드](https://github.com/Hooooong/Pholar/tree/master/app/src/main/java/com/hooooong/pholar)

## 사용 Skills

  - Firebase Authentication

      - Google 계정 연동 로그인

  - Firebase Database & Storage

      - Firebase 에서 제공되는 Realtime DB 를 통해 Post 의 정보를 Create, Read

      - Firebase Storage 에 Post 에 관련된 사진 파일 업로드

  - Firebase Function & FCM ( Firebase Cloud Messaging )

      - Post 의 `좋아요` 와 `댓글` 이 달리면 Post 작성자에게 알림(Notification)

      - Function 에 Script 를 작성하여 Notification 활성화

  - ViewPager

  - RecyclerView

  - LayoutBehavior

  - Permission

  - Glide
