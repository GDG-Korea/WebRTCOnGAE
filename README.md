#개인용 영상통화 만들기 (WebRTC + Google AppEngine)

GDG Korea DevFair 2014의 Codelab 에서 사용될 Repo 입니다.

## Pre-requisite

본 Codelab을 진행하기 위해 필요한 것들 입니다. 코드랩 장소의 네트워크에 많은 분들이 동시에 접근하셔서 네트워크상황이 좋지 않을 가능성이 높기 때문에 개발관련 Tool은 미리 설치해오시기 바랍니다. 


#### 선수지식

- 한국어, 영어(영문 자료 읽기용)
- HTML / Javascript / jQuery / JSON / ajax
- Java (아주 간단한 초급 수준.)

#### 장비

- 웹캠
- 컴퓨터 (데스크탑? 노트북!)

### 계정

- [Google Cloud Platform](https://console.developers.google.com/billing/freetrial?hl=ko&_ga=1.139487542.402653137.1412223855) 계정
- [Github](https://github.com) 계정 : 본 저장소 접근을 위해

#### 개발 Tool

- [Java SDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
- [Google Appengine SDK](https://cloud.google.com/appengine/downloads) (eclipse + GAE plugin 권장)
- [Chrome Browser](http://www.google.com/chrome/)


#### 코드랩 이전에 읽어 두면 좋은 자료

- [Getting Started with WebRTC.html5rocks](http://www.html5rocks.com/ko/tutorials/webrtc/basics/) - 한글 번역있음 :-)

## CodeLab 목차

- WebRTC 란? (20분)
- Codelab 환경 설정 (20분)
- Setup the playground. : GAE 첫 Deploy (10분)
- 내가 이렇게 생겼군. : GetUserMedia 실행 (20분)
- Signaling Server 구성 : Channel API 설정. (20분)
- PeerConnection 연결하기 (40분)
- Streaming 연결하기 (20분)
- 채팅 연결하기 : DataChannel 연결 (30분)
- 화면 이쁘게 꾸미기 & 질의응답 (나머지 시간)