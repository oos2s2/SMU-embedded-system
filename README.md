# SMU-embedded-system project

## 1주차 팀 활동 보고서

### 팀 소개
- 팀명 : 미정 (주제가 선정되면 정하겠습니다.)
-팀원 : 201821024 강정연, 201821069 이예림, 201821074 이채 린, 201821077 임 진선,  김현승

 -역할 분담 : 이채 린-깃 허브 작성, 합침-대본, 임 진선-녹음, 이예림-영상으로
- 팀 규칙 : 프로젝트 관련 연락 자주 보기, 꾸준히 공부하고 자료 찾아보기, 팀에게 피해주지 않기 위해 책임감 있게 행동하기n

### 자료조사
* 1차 회의 : 평소 생활 속에서의 니즈를 찾으려고 노력함 -> 전세계가 재난상황에 처한 이후 집에 있는 시간이 많아짐에 따라, 집 안에서의 불편함을 해소할 수 있는 아이디어를 생각함.
따라서 홈케어 기반 임베디드 시스템에 대한 자료조사 시작


[라즈베리파이를 이용한 스마트홈 및 원격관리 어플리케이션](https://1d1cblog.tistory.com/m/45)

[와이프를 위한 스마트홈 만들기, 매직미러!](https://youtu.be/0h0ULAXlm7w)

[라즈베리파이IoT 딥러닝 Computer Vision프로젝트](https://www.youtube.com/watch?v=6oBZPW8spgA)

[라즈베리파이를 이용한 홈케어디바디스 '우렁케어'](https://github.com/wjrmffldrhrl/UleungCare)

#### 구상도

<img src="https://user-images.githubusercontent.com/62593236/92331952-1b8a0b80-f0b5-11ea-8da9-a95e5b7da5ed.png" width="90%"></img>

* 문제점 : 홈케어와 하드웨어를 접목시키는 것이 어려움. 무인자동차를 기반으로 한 자동화 로봇을 통해 집 안의 상태를 확인하고, 앱으로 데이터를 전달하여 사람에게 알려주면 
앱을 통해 집안의 사물을 제어할 수 있도록(에어컨키기, 제습기키기, 조명키기 등)하려했으나,  앱을 통해 사물을 제어하는 기술의 성공가능성에 대한 의문점을 갖게 됨. 또, 로봇의 필요성에 대한 의문점이 생김( 집안의 상태를 알려준 뒤, 그 다음의 액션이 딱히 떠오르지않음). 홈케어와 하드웨어의 접목 외에 다른 아이디어를 생각해보기로하여 2차 회의 시작.


* 2차 회의 : 코로나 상황이 심각해짐에 따라 이 생활 속의 니즈가 떠오름. 아직 마스크를 필수로 챙겨야 하는 생활이 익숙치 않기 때문에
나이가 드신 분들을 포함한 많은 사람들이 마스크를 두고 나가 밖에서 급하게 새 마스크를 사는 일이 빈번하게 발생함.
이제 코로나는 빠른시일내에 사라지기 어려운 상황으로 보여짐으로 생활 속에서의 대처가 자연스러워짐.

#### 구상도 

<img src="https://user-images.githubusercontent.com/62593236/92330566-d6f97280-f0aa-11ea-99cc-64b3d537cc5f.png" width="90%"></img>

신발장 벽에 부착된 대시보드디바이스와 마스크 살균기 박스, 손소독제로 구성되어 있음.

외출 시 열감지 센서에 사람이 인식되면 대시보드에서 '마스크를 착용하세요'라는 멘트가 나오도록 설정하고, 
똑같이 집에 들어오는 것이 인식되면 대시보드에서 '소독제를 사용한 후 마스크를 살균기에 넣으세요'라는 멘트가 나오도록 설정할 것임.
대시보드에는 이 외에도 수동으로 살균기가 작동하도록 버튼이 제작돼있고, 코로나 관련 소식을 담아놓도록 제작할 것임.
(위는 초기 구상도이며, 기능을 더 추가하고 구체화 할 것임. 좀 더 시간을 들이면 더 나은 아이디어가 나올 것으로 예상됨.)

* 문제점 : 취지나 아이디어는 좋으나 프로젝트의 난이도가 쉬운 것 같음. 좀 더 난이도 있게 하고싶은 아쉬움이 남음.

기타 아이디어 : 미리 앱으로 등록한 내 커피 레시피를 얼굴인식을 통해 취향에 맞는 커피를 제조해주는 기계 (가정, 직장 등등에서 사용가능)

### 주제선정
후보
1. 홈케어 디바이스
2. 얼굴인식 기반 커피머신
3. 코로나 깜빡이 디바이스
(교수님의 조언이 필요합니다.)

### 회의과정

회의는 디스코드 프로그램 사용.

<img src="https://user-images.githubusercontent.com/62593236/92319405-bb627d80-f052-11ea-8499-92e8e4e24914.png" width="90%"></img>


## 2주차 팀 활동 보고서
-역할 분담 : 이채린 – 대본 작성, 이예림 – 자료조사 및 깃 허브 작성, 임진선 – 발표 영상 녹음, 김현승 – 자료조사 및 깃 허브 작성, 강정연 – 자료조사 및 깃 허브 작성 .

### 주제 선정
1주차에서 나온 얼굴인식 기반 커피머신 아이디어에서 기술적인 어려움과 구체적인 아이디어 구상에서 어려움을 겪어 이와 비슷한 새로운 아이디어 구상.

1번째 주제 : 1차 회의에서는 딥러닝을 기반으로 한 카메라로 사람 얼굴을 인식해 표정과 감정을 데이터로 받아들여 라즈베리파이로 데이터를 각각 분석해 그에 맞는 음료를 추천 및 뽑아주는 임베디드 시스템 설계. 음료 제작 기계는 아두이노를 사용해서 제작

구상도 

<img src="https://user-images.githubusercontent.com/70967826/93000087-e1ab8000-f560-11ea-87fd-2e28bfa5ca1a.png" width=70%></img>

### 자료 조사 

[파이썬 강좌 – 딥러닝으로 표정 인식하기](https://m.blog.naver.com/roboholic84/221633210887)

[얼굴 표정인식을 통한 사용자 감정 케어](https://ausome.tistory.com/6)

[라즈베리파이를 이용한 칵테일 제조기 알콜램프](https://youtu.be/WO7iVxId79U)

[라즈베리파이를 이용한 칵테일 제조기 알콜램프](http://eswcontest.or.kr/bbs/download.php?tbl=award&no=1411)

### 문제점
카메라로 사람 얼굴을 인식한 뒤 딥러닝을 통한 표정 인식 과정에서 다양한 표정을 성공적으로 데이터화 하는 기술의 성공가능성에 대한 의문점을 가짐. 

2번째 주제 : 라즈베리파이를 이용해 취향과 기호에 맞게 음료를 제조할 수 있는 기계와 그 기계를 직접 제어할 수 있는 어플리케이션 제작. 추가로 단순 음료 제조뿐만 아니라 원하는 레시피를 직접 입력하는 기능이나 원하는 시간에 맞춰 음료를 제조할 수 있는 예약 기능 등과 같은 기능 추가

구상도 

<img src="https://user-images.githubusercontent.com/70967826/93000083-dd7f6280-f560-11ea-96bb-edbb70e09a47.png" width=70%></img>
<img src="https://user-images.githubusercontent.com/70967826/93000085-e112e980-f560-11ea-874e-89cb617a038d.png" width=70%></img>
<img src="https://user-images.githubusercontent.com/70967826/93000086-e112e980-f560-11ea-921c-80cf74452647.png" width=70%></img>

### 자료 조사 

[라즈베리파이와 어플을 이용한 임베디드 시리얼 제조기](https://www.youtube.com/watch?v=iAL7O1oMXZU&feature=youtu.be)

[라즈베리파이 서브모터 음료 디스펜서](https://www.youtube.com/watch?v=Va_HRMmJt-g)

[Rasberry Pi Smart Bartender](https://youtu.be/2DopvpNF7J4)

[라즈베리파이 컨트롤러 자동 드링크 바텐더 분배](https://ko.howtodogood.com/49472-Raspberry-pi-Controller-Automatic-Drink-Dispensing-66)

[Make your own crude Cocktail Machine](https://www.youtube.com/watch?v=Z7GkGeZrb2Y)

[Cocktails based on your mood created by a Raspberry Pi bartender](https://www.youtube.com/watch?v=8q_5STFzJ6c)

문제점 : 부족한 기능 구성. 그러므로 복잡하고 높은 수준의 난이도에 맞는 추가적인 아이디어 구상이 필요함


### 회의 과정

회의는 디스 코드 프로그램 사용


## 3주차 팀 활동 보고서

- 역할분담 : 이채린,이예림 - 깃허브 작성, 강정연 - 대본작성, 임진선 - 녹음 및 영상제작

- 회의내용 

 2주차 회의에서 나왔던 2개의 주제와 2주차 보고서에 대한 교수님의 피드백을 바탕으로 최종 작품회의를 진행하였습니다.
 회의 중 ① 딥 러닝과 어플 또는 모니터를 만드는 계획과 ② 어플과 라즈베리 파이를 사용하여 기계를 만드는 계획 인 주제가 나 왔습니다. 
주제들의 기능성 이랑 난이도 체계를 고려해 주제를 선정 하여 아래와 같은 계획으로 진행할 예정입니다.

 카메라로 표정을 인식하는 딥 러닝 기술을 표정 정보를 받아옴. 
받아온 정보를 직접 제작한 어플에 전송함.
 1. 딥러닝을 통해 받아온 표정인식 정보
 2. 나이
 3. 성별
 4. 현재 날씨 등등
 표정인식 정보외에 위와같은 정보를 사용자로부터 받아 어플에 저장한 뒤, 데이터 통계를 통해 음료를 추천해준다.
 추천해준 음료를 기계가 라즈베리파이를 사용하여 만든 기계로 제조해준다.
 
 ### 전체 흐름도 예시
 
 어플에 있는 두 가지 선택지 중 자신이 원하는 기능을 선택한다.
 
 만약 내가 내 레시피에 따른 음료를 만들고싶다면, choosing a recipe 를 누르고 2주차 보고서에 있는 구상도에 맞춰 진행하면 된다.
 
 <img src="https://user-images.githubusercontent.com/62593236/93715219-0c21bc80-fba3-11ea-9674-30b6f742edd9.png" width="30%"></img>
 
 만약 추천음료를 받고싶다면 recommend drinks를 누르고 기계에 부착된 카메라에 얼굴을 갖다댄다. 
 
 <img src="https://user-images.githubusercontent.com/62593236/93715301-763a6180-fba3-11ea-8b15-086fc508d50f.png" width="40%"></img>
 
 얼굴이 인식되어 표정분석 결과가 어플에 띄워지면 설문을 진행하고 save를 누르면 추천음료가 나온다.
 
 <img src="https://user-images.githubusercontent.com/62593236/93715374-d7facb80-fba3-11ea-8978-95c7e3c77a20.png" width="70%"></img>

 ### 역할 분담 및 계획

- 역할 분담 : 딥러닝 - 강정연, 김현승  /  기계제조 - 이예림, 임진선  /  어플 - 이채린

1. 딥러닝 : 라즈베리파이와 카메라를 연결해 사용자의 얼굴을 데이터로 받아들이는 것을 할 계획입니다.
2. 기계제작 : 라즈베리파이를 사용해 음료를 제조할 수 있는 기계를 만들 계획입니다.
3. 어플 : 전체적인 어플 틀을 만들어 딥러닝 정보를 가져올 수 있게 만들 계획입니다.

 

### 회의 과정
회의는 디스코드 프로그램 사용

# 4주차 팀 활동 보고서

- 역할 분담 : 깃허브작성 - 김현승, 대본 작성 - 이예림,  녹음 및 영상 제작 - 임진선

## 팀 구성

팀명 : Make your drinks(팀장 : 이채린)

딥러닝 - 강정연, 김현승

기계 제조 - 임진선, 이예림

어플 - 이채린

## 회의 내용

1. 음료는 아이스 아메리카노, 바닐라 라떼, 헤이즐넛 라떼, 아이스티, 포도주스, 오렌지주스로 7종류의 음료로 결정하였습니다.
총 필요한 재료는 커피 원액, 아이 스티 원액, 물, 우유, 헤이즐넛 시럽, 바닐라 시럽, 포도 주스, 오렌지 주스가있습니다.

2. 기계 제작시 아두이노와 라즈베리파이 둘 중 무엇을 사용할지 고민하다 회의 결과 라즈베리파이를 사용하기로 했다.
이 기계를 개인용으로 사용할지 상업용으로 사용할지 회의했는데 상업용으로 사용하기로 결정이 났다.

3. 2주차에서 다뤘던 시간예약을 활용하는 기능은 사용하지 않기로 결정했다.


## 이번 주 활동 내용
### 딥러닝

1.라즈베리파이 설치
sd카드에 https://www.raspberrypi.org/downloads/ 링크에서 다운받은 라즈베리파이os 설치
sd카드를 라즈베리파이3 모델에 꽂아준 뒤 라즈베리파이와 컴퓨터용 모니터를 hdmi로 연결

2.라즈베리파이 웹캠 연결

<img src="https://user-images.githubusercontent.com/70967826/94369747-911e5000-0126-11eb-821b-10bd56809e44.png" width=50%></img>

라즈베리파이 웹캠을 usb로 연결 후 fswebcam명령어를 이용해 사진촬영 동작 코드 작성

<img src="https://user-images.githubusercontent.com/70967826/94369771-b612c300-0126-11eb-991f-875450fd06e4.png" width=50%></img>

라즈베리파이와 웹캠을 위 와 같은 명령어로 촬영한 사진

3.opencv 설치

실시간 동영상 촬영과 촬영 하는 동시에 얼굴을 인식하기 위한 opencv 프로그램 설치

http://makeshare.org/bbs/board.php?bo_table=raspberrypi&wr_id=92

위 링크에 나온 내용을 토대로 opencv설치

<img src="https://user-images.githubusercontent.com/70967826/94369779-c034c180-0126-11eb-99f2-0e8f9701e06e.png" width=50%></img>

opencv가 정상적으로 설치됬는지 확인

### 기계 제조

기계 제작에 필요한 재료들을 생각해본 후 교수님께 재료들을 어떤 방법으로 구매할 수 있는지 피드백을 구함

### 어플

앱 로딩화면이 2초 나타난 후 메인페이지 화면으로 이동

<img src="https://user-images.githubusercontent.com/70967826/94380278-e03ca300-016f-11eb-8733-66ea4765b4de.png" width=30%></img>

구상도대로 음료 추천받기와 직접 제조하기 버튼을 만들어 사용자에게 선택할 수 있게 함 firebase와 app을 연동시켜놓았음.

<img src="https://user-images.githubusercontent.com/70967826/94380288-eaf73800-016f-11eb-85e0-3bec4d86b568.png" width=30%></img>


## 다음 주 활동 계획
### 딥러닝
라즈베리파이와 opencv 프로그램을 이용해 동영상 촬영 및 얼굴인식 기능 구현
### 기계 제조
기계제작팀은 여태까지 회의했던 내용을 토대로 구상도를 구상해 그려보고, 기계제작에 필요한 재료와 부품들을 찾아본 후 다음 회의를 통해 구체적인 구상도를 구상한 후 제작에 필요한 재료와 부품들을 찾아 목록을 만들어 교수님께 제출할 계획입니다.
### 어플
설문조사 폼 구성 및 안드로이드와 파이어베이스 연결하여 데이터 저장

## 5주차 팀 활동 보고서

- 역할 분담 : 강정연 - 깃허브작성, 이채린 - 대본작성, 김현승 -발표 녹음 및 영상 제작

## 회의 내용
 1. 기계 구상 과정에서 음료 제어에 사용할 부품에 대한 두 가지 방안 고려.
  - 워터 펌프를 이용한 제어 : 아두이노 워터 펌프를 쉽게 제어하기 위한 아두이노 모터 드라이브 사용. 모터 드라이버 제어를 위한 코딩과 그 후 모터와 기압차를 이용해 아두이노
                             워터 펌프를 통해 음료를 빨아들이는 방법 구상. 워터 펌프에 관한 정확한 부품 종류와 가격에 대한 추가적인 조사 예정
                             
  - 서보 모터를 위한 제어 : 음료 배출구를 호스로 제작한 뒤, 아두이노 서보 모터의 움직임을 제어할 수 있는 코드를 작동해 호스 제어. 정상적인 음료 배출을 위한 호스와 
                          서보 모터의 결합 방법 구상 예정.
                          
 2. 라즈베리파이와 카메라의 정상적인 작동에 계속해서 문제가 생기기 때문에 문제 해결을 위한 추가적인 방법 모색과 추가로 필요한 부품을 구매해 라즈베리파이 환경구축에
    지장이 없도록 노력 필요.

 3. 위 두 내용에서 추가로 구매가 필요하다고 생각이 되는 부품 정리.(라즈베리파이캠,랜 케이블, 아두이노 서보 모터, 아두이노 워터 펌프, 아두이노 모터 드라이버.. 등)

## 이번 주 활동 내용

### 어플

- 음료 레시피 선택을 위한 폼 구성 및 안드로이드와 파이어베이스를 연결하여 데이터 저장이 가능하도록 제작.

<img src="https://user-images.githubusercontent.com/70554317/95019739-17e0a900-06a2-11eb-9cd5-014b5cd5db97.png" width=30%></img>

음료 종류별로 버튼을 설정하여 페이지마다 자신이 원하는 레시피를 제조할 수 있도록 제작.

<img src="https://user-images.githubusercontent.com/70554317/95019767-39419500-06a2-11eb-95fd-f81e29d13351.png" width=30%></img>

음료 카테고리를 선택한 뒤 음료 제조에 필요한 물과 커피원액의 입력 및 사람마다 데이터 저장을 위한 이름을 입력할 수 있도록 제작 ,
그 후 start버튼을 누르면 기계가 작동하도록 제작.

<img src="https://user-images.githubusercontent.com/70554317/95019780-465e8400-06a2-11eb-8fe5-6c471b4878bc.png" width=30%></img>

위에서 입력한 정보들을 버튼을 누름과 동시에 Firebase Realtime database에 데이터가 저장되도록 설정.     

### 딥러닝

- 라즈베리파이와 웹캠을 연결해 웹캠이 사람 얼굴을 찾아 얼굴만 인식이 가능하도록 가동.

<pre>
$ sudo apt-get install git
$ git clone https://github.com/insung3511/OpenCV_Face_detection_code.git
$ cd openCV_Face_detection_code/openCV_EYE/
$ python face_eye_detection.py
</pre>
</br>

웹캠과 정상적으로 연결된 라즈베리파이에 명령어로 소스를 가져오기위한 프로그램을 sudo apt-get install git로 다운로드.
git clone명령어로 웸캡 작동을 위한 소스 프로그램을 가져와 로컬에 복사본을 생성.
opencv프로그램을 python을 이용하여 카메라가 사람 얼굴을 인식하도록 실행.

(라즈베리파이 작동 환경에서 문제가 생겨  연결 문제를 해결한 뒤 활동 과정과 활동 사진 캡처가 불가능하여 추후에 재업로드 예정)

### 기계 제조

- 구체적인 구상도 제작과 그에 관한 부품 조사와, 각 부품에 따른 기능 구상

<img src="https://user-images.githubusercontent.com/70554317/95021237-bcff7f80-06aa-11eb-8320-2e4af7897c96.jpg" width=90%></img>

아두이노 워터 펌프를 이용해 음료가 담긴 병에서 기압차와 모터를 이용해 음료를 배출해내는 방법 구상.

<img src="https://user-images.githubusercontent.com/70554317/95021271-f9cb7680-06aa-11eb-8d5a-44f254b6435e.jpg" width=80%></img>

아두이노 서보 모터를 이용한 호스제어를 통해 음료 배출을 제어하는 방법 구상.

제품 구매 시 서보 모터와 워터 펌프 두가지를 다 구매해 각각 제작후 가동해본뒤, 기계 작동에 지장이 없는쪽으로 부품을 선택해 제작 예정.

## 6주차 팀 보고서

- 역할 분담 : 강정연 - 깃허브작성, 김현승 - 대본작성, 임진선 -발표 녹음 및 영상 제작

## 이번주 활동 

### 딥 러닝

- 딥 러닝에서의 정상적인 데이터셋 활동이 시작되면 그에 맞춰 데이터를 받아올 수 있는 방법 연구 예정.

정상적인 프로그램 설치를 위해 기본적으로 라즈베리파이 업데이트 및 업그레이드를 해줌.

<pre>
$ sudo apt-get update
$ sudo apt-get upgrade
</pre>
</br>

웹 서버로부터 Miniconda3 설치 프로그램 콘텐츠를 가져오기 위해 wget명령어를 사용해 Miniconda3 설치 프로그램 패키지 다운.

<pre>
$ wget http://repo.continuum.io/miniconda/Miniconda3-latest-Linux-armv7l.sh
</pre>
</br>

md5sum명령어를 이용하여 다운로드한 파일의 이상유무 확인.

<pre>
$ sudo md5sum Miniconda3-latest-Linux-armv7l.sh
</pre>
</br>

다운받은 Miniconda3 설치 프로그램 실행하여 Miniconda3 설치(설치 파일 경로 = /home/pi/miniconda3).

<pre>
$ sudo /bin/bash Miniconda3-latest-Linux-armv7l.sh
</pre>
</br>

설치가 완료된 후 nano 편집기로 Miniconda3 실행파일에 들어감(본 파일의 끝에 export PATH="/home/pi/miniconda3/bin:$PATH" 추가).

<pre>
$ sudo nano /home/pi/.bashrc
</pre>
</br>

실행파일 실행.

<pre>
$ source ~/.bashrc
</pre>
</br>

conda --version을 입력해 정상적으로 설치 되었음을 확인.

![2020-10-11-235521_631x449_scrot](https://user-images.githubusercontent.com/70554317/95682567-d2cbf200-0c20-11eb-901e-dd49ec462439.png)

- 아나콘다 설치 후 실행 과정에서 이전에 설치한 opencv프로그램 작동이 안됨, 그 이유가 웸캠 실행에 필요한 파이썬 버전이 아나콘다와 opencv 서로 안맞음. 이 문제 해결 완료 후 본격적인 딥 러닝 활동 시작 예정.

### 기계 제조

- 음료 제조 기계에 필요한 구상 완성과 그에 맞는 부품 구매. 

<img src="https://user-images.githubusercontent.com/70554317/95021237-bcff7f80-06aa-11eb-8320-2e4af7897c96.jpg" width=90%></img>

<img src="https://user-images.githubusercontent.com/70554317/95021271-f9cb7680-06aa-11eb-8d5a-44f254b6435e.jpg" width=80%></img>

부품 목록(표기된 가격은 배송비가 포함되어 있는 가격이 아닙니다.)

부품 | 상세 | 가격 | 참고 
---- | ---- | ---- | ----
우드락 | 5T 60x90cm 10장 비접착 1개 | 15000원 | https://smartstore.naver.com/dnara/products/2309183053
우드락본드 | 2개 | 2400원 | https://smartstore.naver.com/dnara/products/2478819744
하드보드지 | 2절지 5장 1개 | 7500원 | https://smartstore.naver.com/dnara/products/2441815695
워터펌프 & 실리콘 호수 | (옵션선택) 흡입구, 토출구호스 둘 다  1m(d5 X D8 X 1.5T) 1개 | 15,950원 | https://www.devicemart.co.kr/goods/view?no=1326767
서보모터 | 1개 | 6800원 | http://m.techshenzhen.com/goods/goods_view.php?goodsNo=1000000605
글루건 & 글루스틱 | GR-20 글루건 1개 7.3 투명 (10개/26cm)  1개 | 7300원 | https://daisomall.co.kr/shop/goods_view.php?id=0001763633&cid=&depth=&search_text=%EA%B8%80%EB%A3%A8%EA%B1%B4

- 본 부품들이 도착한 뒤 본격적인 기계 제조에 앞서 본 부품들의 작동 원리와 작동을 위한 지식과 정보를 찾아보고 공부할 예정.

### 어플

- 음료 선택을 위한 폼 구성에서 추가로 메뉴 구성.

<img src="https://user-images.githubusercontent.com/70554317/95695215-e30bbd80-0c70-11eb-9bf5-9f9b4ca25a42.png" width=30%></img>

<img src="https://user-images.githubusercontent.com/70554317/95695236-059dd680-0c71-11eb-865b-9fc8c128412c.png" width=30%></img>

<img src="https://user-images.githubusercontent.com/70554317/95695246-11899880-0c71-11eb-8872-3e132aef05f0.png" width=30%></img>

<img src="https://user-images.githubusercontent.com/70554317/95695252-19e1d380-0c71-11eb-9264-01618b543584.png" width=30%></img>

- 딥 러닝에서의 정상적인 데이터셋 활동이 시작되면 그에 맞춰 데이터를 받아올 수 있는 방법 연구 예정.


## 7주차 팀 보고서

 - 역할 분담 : 이예림 - 깃허브작성, 강정연 - 대본작성, 임진선 - 발표 녹음 및 영상 제작

## 이번주 활동

### 딥 러닝
 - 라즈베리파이와 노트북 랜선연결을 시도하였음.
 - 딥 러닝에 필요한 라이브 코드와 딥 러닝에 필요한 통계 데이터와 문서를 공유하기 위해 라즈베리파이에 jupyter notebook 설치하였음.

설치에 필요한 라즈베리파이 업데이트를 해줌.

<pre>
$ sudo apt-get update
</pre>
</br>

설치에 필요한 python 라이브러리들을 설치해줌.
또한, pip도 최신버전으로 업그레이드까지 해준 뒤 재부팅을 해줌.

<pre>
$ sudo apt-get install python3-matplotlib -y
$ sudo apt-get install python3-scipy -y
$ sudo pip3 install --upgrade pip
$ sudo reboot
</pre>
</br>

재부팅이 완료되면 pip를 이용하여  jupyter notebok을 설치해줌.

<pre>
$ sudo pip3 install jupyter
</pre>
</br>

jupyter notebook 실행을 위한 명령어를 입력해줌. (라즈베리파이의 ip주소는 ifconfig명령어로 확인)
실행할 때 ip주소를 지정해주고 ssh 연결 상태이므로 "--no-browser" 플래그를 통해 인터넷 창이 켜지지 않도록 함.
그렇지 않으면 display관련 에러가 나면서 jupyter notebook이 꺼짐

<pre>
$ jupyter-notebook --ip="라즈베리파이 ip 주소" --no-browser
</pre>
</br>

위의 명령어를 입력하면 다음과 같은 내용이 출력됨

<pre>
[I 11:42:23.596 NotebookApp] Writing notebook server cookie secret to /run/user/1000/jupyter/notebook_cookie_secret
[I 11:42:33.408 NotebookApp] Serving notebooks from local directory: /home/pi
[I 11:42:33.409 NotebookApp] The Jupyter Notebook is running at:
[I 11:42:33.409 NotebookApp] 
http://192.168.0.17:8888/?token=4aaf5f14fa5d7c93bb0c49c16ae3d0af5d106ea465a2e771
[I 11:42:33.409 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 11:42:33.431 NotebookApp]

    To access the notebook, open this file in a browser:
        file:///run/user/1000/jupyter/nbserver-9071-open.html
    Or copy and paste one of these URLs:
        http://192.168.0.17:8888/?token=4aa**********
</pre>
</br>

http://192.168.0.17:8888/?token=4aaf5f14fa5d7c93bb0c49c16ae3d0af5d106ea465a2e771
부분에 해당하는 URL로 들어가면 jupyter notebook이 실행됨.

![image](https://user-images.githubusercontent.com/70791411/96401969-c0008100-120f-11eb-968f-eb2d70b4a4cb.png)


 - 라즈베리파이와 휴대폰을 서로 스트리밍 하기위해 uv4l프로그램을 라즈베리파이에 설치할 예정.
 - 라즈베리파이와 노트북 랜선 연결을 계속 시도해볼 예정

### 기계 제조
 - 두 개의 구상도 중 워터펌프를 사용하여 기계를 제조하는 구상도로 확정하였고 라즈베리파이를 이용하여 워터펌프를 제어하여 기계를 제작하는 것으로 확정함.

![기계구상도도안1](https://user-images.githubusercontent.com/70791411/96402133-15d52900-1210-11eb-9687-0fe3f9599563.jpg)

 - 기계 제조에 앞서 라즈베리파이를 사용하여 워터펌프를 제어할 수 있는 방법과 지식, 정보에 대해 찾아보고 공부할 예정.

### 어플

핸드폰에서 카메라를 스트리밍 하기위해 라즈베리파이에 uv4l 드라이버를 설치함. (아래 코드는 설치코드)

<pre>
$ sudo apt-get install uv4l uv4l-raspicam
$ sudo apt-get install uv4l-raspicam-extras
</pre>
</br>

서비스를 시작 및 종료하는 명령어

시작하는 명령어

<pre>
$ sudo service uv4l_raspicam restart
</사전>
</pre>

원하는 옵션으로 시작하는 명령어

<pre>
$ uv4l —driver raspicam —auto-video_nr —width 640 —height 480 —encoding jpeg
</사전>
</pre>

강제종료하는 명령어

<pre>
$ sudo pkill uv4l
</pre>
</br>

스트리밍 서버를 위한 패키치를 설치함

<pre>
$ sudo apt-get install uv4l-server uv4l-uvc uv4l-xscreen uv4l-mjpegstream uv4l-dummy uv4l-raspidisp
</pre>
</br>

안드로이드 스튜디오에 웹뷰 추가해서 
http://라즈베리파이주소/stream/video.mjpeg 에 들어가면 카메라가 보고있는 화면이 뜸.

 - 안드로이드 핸드폰을 전달받아 안드로이드 핸드폰에 만든 앱을 연결 해보고 연결 시키기 등을 해볼 예정.

## 8주차 팀 보고서

### 딥 러닝

- 휴대폰 안드로이드와 아즈베리파이의 웹캠을 실시간 스트리밍 시키기 위해 라즈베리파이에 uv4l프로그램 설치.

uv4l프로그램 버전 설정을 위한 명령어 입력.
<pre>
$ curl http://www.linux-projects.org/listing/uv4l_repo/lpkey.asc | sudo apt-key add -
</pre>
<br>

sources.list 파일에 다음을 추가.
<pre>
$ sudo nano /etc/apt/sources.list
// 아래 내용 추가
deb http://www.linux-projects.org/listing/uv4l_repo/raspbian/stretch stretch main
</pre>
<br>

소스를 바꿔주었으므로 전체적인 시스템 update 진행.
<pre>
$ sudo apt-get update
</pre>
<br>

uv4l 설치.
<pre>
$ sudo apt-get install uv4l uv4l-raspicam
</pre>
<br>

드라이버 로드를 위한 패키지 설치.
<pre>
$ sudo apt-get install uv4l-raspicam-extras
</pre>
<br>

서비스 시작 및 종료 명령어.
<pre>
// 시작
$ sudo service uv4l_raspicam restart
// 원하는 옵션으로 시작
$ uv4l —driver raspicam —auto-video_nr —width 640 —height 480 —encoding jpeg   
// 강제종료
$ sudo pkill uv4l      
</pre>
<br>

스트리밍 서버를 위한 패키지 설치.
<pre>
$ sudo apt-get install uv4l-server uv4l-uvc uv4l-xscreen uv4l-mjpegstream uv4l-dummy uv4l-raspidisp     
</pre>
<br>


웹캠관련 명령어.
<pre>
// 펌웨어 업데이트하기
$ sudo rpi-update
// 웹캠이 인식됐는지 확인하기
$ v4l2-ctl -V
// uv4l로 웹캠화면 한번 찍기
$ dd if=/dev/video0 of=snapshot.jpeg bs=11M count=1  
</pre>
<br>

웹에서 스트리밍 하기 위해서는 "http://라즈베리파이ip:8080"으로 접속(파이캠은 8080, 웹캠은 8090).
위 과정에서 설치하기이전 라즈베리파이캠을 인식 시켜야 되는데 라즈베리파이캠 인식 불가로 프로그램 실행하지 못하였음.

### 기계 제조

- 이전에 주문한 부품 수령 및 확인.
- 본격적인 제조에 앞서 구체적인 원리와 정보 등 공부 예정.

### 어플

- 어플 제작에 요구되는 환경과 다른 활동과의 진도가 맞지 않아 추가적인 활동 진행하지 못하였음. 
- 추가로 어플의 전체적인 폼 디자인적 요소 구성과 세부적인 요소 구상 예정

시험기간으로 인해 많은 양의 활동을 못하였음. 다음 주 부터 빠른 속도로 프로젝트 진행 예정. 

## 9주차 팀 보고서 

### 딥 러닝

라즈베리파이에 필요없는 다수의 프로그램 다운된게 너무 많아 라즈베리파이 내에서 시스템이 너무 엉켜서 라즈베리파이 sd카드를 포멧하고 이전에 했던 과정을 반복하였음

### 기계 제조

![image](https://user-images.githubusercontent.com/70967826/97831743-48a11600-1d14-11eb-9eeb-0a89b93f9bd9.png)

구상도는 위에와 같이 진행하기로 함.
아두이노와 라즈베리파이 둘 중 아두이노를 사용하여 만들기로 함.
음료는 아메리카노, 아이스티, 바닐라라떼, 헤이즐넛라떼, 오렌지주스, 포도주스로 정했었는데 여러개의 워터펌프 제어를 할 때에 아두이노가 버티지 못할 상황을 대비해 음료와 재료의 개수를 줄임.
재료는 아메리카노원액, 아이스티원액, 시럽1가지 (바닐라시럽 또는 헤이즐넛시럽), 주스 1가지, 물, 우유로 확정.
재료를 담을 병으로는 일회용 플라스틱 생수병을 선택함.
기계의 크기는 생수병에 기준을 맞춰서 생수병 6개까지 들어갈 수 있도록 만들었음.
생수병의 높이는 20.5cm, 너비는 6.2cm로, 너비는 생수병 6개가 들어갈 수 있도록 6.2 * 6으로 계산 후 양쪽으로 +5cm를 더해 총 48cm로 제작하였음.
높이는 생수병 높이+높이의 반으로 20.5+10.5로 계산해 총 31cm로 제작하였음.

![image](https://user-images.githubusercontent.com/70967826/97831772-55256e80-1d14-11eb-86ea-ab5861348585.png)

제작과정은 아래 사진과 같음.

정확한 치수를 정해 재단함

![image](https://user-images.githubusercontent.com/70967826/97831780-60789a00-1d14-11eb-8eab-454650cde818.png)

우드락본드와 글루건으로 붙임	

![image](https://user-images.githubusercontent.com/70967826/97831788-640c2100-1d14-11eb-9f6b-42f8f8810cf1.png)

전체적인 틀은 완성

![image](https://user-images.githubusercontent.com/70967826/97831792-65d5e480-1d14-11eb-83cd-2c0966cac8de.png)

재료가 든 병을 버틸 수 있는지 실험함

![image](https://user-images.githubusercontent.com/70967826/97831794-68383e80-1d14-11eb-903b-49bc38401504.png)


못버티는 거 확인 후 밑 바닥을 덧댐
우드락위에 하드보드지 두장과 우드락 하나를 더 더해 단단하게 만듬 물이 든 6개의 병으로 실험했을 때 버팀

![image](https://user-images.githubusercontent.com/70967826/97831795-6a9a9880-1d14-11eb-996f-363a9e3cb6c1.png)

지금까지 현황
앞면

![image](https://user-images.githubusercontent.com/70967826/97831801-6ec6b600-1d14-11eb-860f-f2cbc0b6cd11.png)

뒷면

![image](https://user-images.githubusercontent.com/70967826/97831803-70907980-1d14-11eb-88ca-c6f9a148534b.png)

![image](https://user-images.githubusercontent.com/70967826/97831807-72f2d380-1d14-11eb-8bd9-cbe876922c5c.png)

호수와 아두이노, 워터펌프까지 전부 연결 후 마지막에 호수와 아두이노, 워터펌프가 보이지 않도록 윗쪽을 가려주고 재료가 든 병이 기계에서 벗어나지 않도록 밑쪽도 가려줄 예정


다음 주에는 드라이버쉴드를 사용해 워터펌프가 작동하는지 테스트 후 워터펌프를 작동시킬 코드를 짜고 추가적으로 필요한 부품들을 정리해 주문할 예정.


### 어플

안드로이드 스튜디오로 진행한 프로젝트를 핸드폰에 연결해서 엡을 이용해 직접 구동시켰음 다음주에는 딥러닝팀과 같이 진행할 예정

## 10주차 팀 활동 보고서

### 딥 러닝
uv4l 드라이브로 카메라 스트리밍 과정에서 파이캠으로 영상을 연결하는 방법이 중간에서 오류없이 잘 전송되기 때문에 
카메라 얼굴인식을 파이캠으로 동작하는 것으로 변경(이전까지는 웹캠 사용)
파이캠을 연결한 뒤 정상적인 연결 확인을 시도했지만 파이2개 모두 계속적인 연결 오류 메시지가 뜸

밑의 사진처럼 메시지에서 supported=1 detected=1과 같이 떠야 정상

<img src="https://user-images.githubusercontent.com/62593236/98489773-c9ab6080-2272-11eb-8cf3-3de68fe4c2ee.png" width="50%"></img>

오류의 원인을 파이캠의 FFC케이블의 문제라고 판단하여 새로운 파이캠을 구매함

파이캠이 도착하기 전까진 이전에 사용하던 라즈베리파이의 동작 문제로 새로운 라즈베리파이에 opencv를 새로 다운로드하여 사용할 예정임

### 어플

기계팀과 딥러닝팀에서 아두이노와 라즈베리파이가 미완성되어 어플과 연동시킬 수 없어 디자인만 수정하였음

<img src="https://user-images.githubusercontent.com/62593236/98501630-2454b480-2293-11eb-86ab-294a4c8740af.png" width="30%"></img>


### 기계제조

아두이노와 워터펌프를 연결해 먼저, 테스트를 진행

노트북에 Arduino 프로그램을 설치하고, usb 드라이버를 설치함. 

<img src="https://user-images.githubusercontent.com/62593236/98489977-7685dd80-2273-11eb-84eb-e323d6f338ac.png" width="30%"></img>
<img src="https://user-images.githubusercontent.com/62593236/98490057-b351d480-2273-11eb-8f3f-1ebe22d2b4fb.png" width="30%"></img>

워터펌프를 동작시킬 코드를 찾아 진행하였고, 우선 구매한 1개의 워터펌프로 진행함. 
잠깐 빌려온 부품(모듈과 전원선의 연결)을 통해 아두이노를 동작시킬 수 있었고, 
핀번호, delay 함수를 통해 워터펌프의 동작시간을 설정할 수 있었음. Low로 정지가능함을 확인함.
호스를 워터펌프에 연결하여 물로 테스트를 진행하였으며,
이를 통해 물을 흡입하고 배출하는 과정에서 이상이 없음을 확인하였음.

아두이노와 워터펌프동작을 위해 필요한 프로그램 설치와 실제 테스트를 진행한 상태임.

<img src="https://user-images.githubusercontent.com/62593236/98490140-f7dd7000-2273-11eb-9a07-7da7a634ea54.png" width="20%"></img>

다음주에는 1개의 펌프의 작동이 원활하였으므로, 
추가로 어러개의 펌프를 제어하기 위해 릴레이 모듈과 펌프, 호스를 추가주문할 계획이며, 
전원선을 받아 다수의 펌프작동을 원활하게 동작시킬 수 있도록 그에 맞는 코딩을 시도할 예정임.

## 11주차 팀 활동 보고서

### 딥 러닝

- 라즈베리파이카메라 재주문 후 라즈베리파이와 정상적인 연결을 해준 뒤 uv4l 스트리밍 재시도.

이전에 했던 라즈베리파이에 uv4l 설치를 재진행.

uv4l프로그램 버전 설정을 위한 명령어 입력.
<pre>
$ curl http://www.linux-projects.org/listing/uv4l_repo/lpkey.asc | sudo apt-key add -
</pre>
<br>

sources.list 파일에 다음을 추가.
<pre>
$ sudo nano /etc/apt/sources.list
// 아래 내용 추가
deb http://www.linux-projects.org/listing/uv4l_repo/raspbian/stretch stretch main
</pre>
<br>

소스를 바꿔주었으므로 전체적인 시스템 update 진행.
<pre>
$ sudo apt-get update
</pre>
<br>

uv4l 설치.
<pre>
$ sudo apt-get install uv4l uv4l-raspicam
</pre>
<br>

드라이버 로드를 위한 패키지 설치.
<pre>
$ sudo apt-get install uv4l-raspicam-extras
</pre>
<br>

서비스 시작 및 종료 명령어.
<pre>
// 시작
$ sudo service uv4l_raspicam restart
// 원하는 옵션으로 시작
$ uv4l —driver raspicam —auto-video_nr —width 640 —height 480 —encoding jpeg   
// 강제종료
$ sudo pkill uv4l      
</pre>
<br>

스트리밍 서버를 위한 패키지 설치.
<pre>
$ sudo apt-get install uv4l-server uv4l-uvc uv4l-xscreen uv4l-mjpegstream uv4l-dummy uv4l-raspidisp     
</pre>
<br>

웹에서 스트리밍 하기 위해서는 "http://라즈베리파이ip:8080"으로 접속(파이캠은 8080, 웹캠은 8090).

위 주소로 접속하면 밑과 같은 uv4l페이지가 나옴.

<img src="https://user-images.githubusercontent.com/70554317/99212654-fd582e80-280e-11eb-95fe-bee3250684fe.png" width="50%"></img>

본 메뉴에서 MJPEG/Stills stream이 나와있는 메뉴를 선택하면 밑과 같이 실시간 스트리밍이 진행된다.

<img src="https://user-images.githubusercontent.com/70554317/99212879-88392900-280f-11eb-84a5-d3630880d857.png" width="50%"></img>

### 어플

- 이전까지 딥 러닝에서의 스트리밍 과정이 진행되지 못하였기 때문에 파이를 이용해 opencv 설치 및 작동과 딥 러닝 관련 자료 검색등을 함.
- 기계팀과 어플과의 연동 및 부품관련 주기적인 회의 진행함.

### 기계제조

- 부품 주문 과정에서 착오가 생긴 이유로 인해 몇번의 회의를 거친뒤, 부품 재주문이 이루어질 예정.
- 이전에 구상하였던 구상도 확인 및 부품에 맞게 구상도를 재수정함.

## 12주차 팀 활동 보고서

### 머신 러닝

 - 지난주에 접속한 스트리밍 서버를 어플과 연동될 수 있게 스트리밍 서버에 고정 ip할당을 하였음.
 - 원래 표정인식으로 인한 감정 추출 후 데이터를 저장하려고 했으나 더욱더 정삭적인 데이터 추출과 상용화적인 부분을 위해 사람 얼굴인식을 기반으로한 데이터 추출로 변경 예정.

### 어플

 - 안드로이드에 webview를 추가하여 파이캠이 스트리밍 될 수 있도록 구현함.

<img src="https://user-images.githubusercontent.com/70791411/99930579-eaa4a300-2d94-11eb-9783-b678b7f73fb6.png" width="50%"></img>

<구현코드>

<img src="https://user-images.githubusercontent.com/70791411/99930604-04de8100-2d95-11eb-9422-02d4661e6ff6.png" width="50%"></img>

### 기계제조

 - 회의 후 결졍 된 부품들을 재주문 후, 전달받음
 - 구매한 워터펌프와 드라이버쉴드가 작동이 되는지 테스트 후 아두이노와 워터펌프를 연결한 후 실행코드 작성 및 부품 납땜 후 기계에 부착할 예정.

## 13주차 팀 활동 보고서

### 머신 러닝

- 라즈베리파이의 외부 스트리밍을 완료 시킨후 얼굴 인식 기반 데이터셋을 하기 이전 스트리밍내에서 얼굴 인식을 시도함.
  
- 얼굴 인식 및 인식한 얼굴의 데이터 수집을 하기 위한 opencv에서 제공하는 xml형태의 이미지 모델인 haarcascade_frontalface_default.xml을 
  라즈베리파이에 다운.
  
- 라즈베리파이에 얼굴 인식을 위한 코드 작성
  
<pre>
import numpy as np
 import cv2
 faceCascade = cv2.CascadeClassifier('Cascades/haarcascade_frontalface_default.xml')
 cap = cv2.VideoCapture(0)
 cap.set(3,640) # set Width
 cap.set(4,480) # set Height
 while True:
   ret, img = cap.read()
   gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
    faces = faceCascade.detectMultiScale(
       gray,     
       scaleFactor=1.2,
       minNeighbors=5,     
       minSize=(20, 20)
   )
   for (x,y,w,h) in faces:
       cv2.rectangle(img,(x,y),(x+w,y+h),(255,0,0),2)
       roi_gray = gray[y:y+h, x:x+w]
       roi_color = img[y:y+h, x:x+w]  
   cv2.imshow('video',img)
   k = cv2.waitKey(30) & 0xff
   if k == 27: # press 'ESC' to quit
       break
cap.release()
cv2.destroyAllWindows()   
</pre>
<br>

- 작성한 코드를 파이썬으로 실행한 화면.

<img src="https://user-images.githubusercontent.com/70554317/100547461-3df18680-32aa-11eb-94e2-1b84d9d8c47d.PNG" width="50%"></img>

- 위 코드에서 카메라 영상을 스트리밍 서버안에서 켜기 위해 cap = cv2.VideoCapture(0)코드를 
  cap = cv2.VideoCapture("http://"raspi-ip:8080/stream/video.mjpeg")로 변경 하였으나 통신이 원활하지 못해 영상 송출이 안되는 문제를 해결 진행중.

### 기계 제조

- 아두이노에 드라이버쉴드를 부착하고, 워터펌프 4개 연결함.

<img src="https://user-images.githubusercontent.com/70554317/100547608-0f27e000-32ab-11eb-8b77-5822799ebe01.png" width="50%"></img>

- 모터당 순서를 설정 해준 후, 속조를 설정해줌.

<img src="https://user-images.githubusercontent.com/70554317/100547639-35e61680-32ab-11eb-9a7e-a4915b5febaa.png" width="50%"></img>

- 4개의 워터펌프를 작동시킬 코드를 작성함.

<img src="https://user-images.githubusercontent.com/70554317/100547663-531ae500-32ab-11eb-80a1-a6a7a292485e.png" width="50%"></img>

- 순서를 설정해준 모터에 이름을 설정해줌.

<img src="https://user-images.githubusercontent.com/70554317/100547695-7cd40c00-32ab-11eb-887a-fae3f094abfe.png" width="50%"></img>

- 설정한 이름을 시리얼 모니터를 실행해 입력했을 때, 입력받은 이름의 모터가 작동함.

<img src="https://user-images.githubusercontent.com/70554317/100547741-b1e05e80-32ab-11eb-824c-35b434afcaab.png" width="50%"></img>

<img src="https://user-images.githubusercontent.com/70554317/100547774-f23fdc80-32ab-11eb-94fa-3d25f88d7267.png" width="25%"></img>
<img src="https://user-images.githubusercontent.com/70554317/100547791-01268f00-32ac-11eb-8cda-f32b334120ef.png" width="25%"></img>

- 아두이노와 드라이버쉴드에 4개의 워터펌프를 연결시켰기 때문에 재료의 가지 수를 4가지로 맞춰 커피원액, 바닐라시럽, 물, 우유로 정하였고, 메뉴는 아   메리카노, 카페라떼, 바닐라라떼로 정함. 각 재료의 그램수를 정해 초단위로 계산해서 음료의 레시피대로 코딩을 한 후, 어플 & 머신 러닝 팀에 전달할 예   정.
  
  ### 어플
  
  - 회원가입과 로그인창을 만들어 파이어 베이스와 연결시켜 데이터를 저장함.
  
 <img src="https://user-images.githubusercontent.com/70554317/100567481-f13e9780-330b-11eb-94fe-76c06a25d79c.png" width="25%"></img>
 <img src="https://user-images.githubusercontent.com/70554317/100567577-2945da80-330c-11eb-8ccd-d6dd5ab63f0e.png" width="25%"></img>
 <img src="https://user-images.githubusercontent.com/70554317/100567628-4d092080-330c-11eb-8137-71912cc25ef1.png" width="25%"></img> 
 
 - 테스트결과 데이터가 저장된 것을 볼 수 있음.
 
  <img src="https://user-images.githubusercontent.com/70554317/100569189-a8d5a880-3310-11eb-8f44-e0ed601bc075.png" width="50%"></img> 
 
 
 ## 14주차 팀 활동 보고서

### 머신 러닝
파이캠을 이용해 얼굴인식을 한 뒤 얼굴 데이터를 추출해서 라즈베리파이에 저장함

<pre>
import cv2
import os

cam = cv2.VideoCapture(0)
cam.set(3, 640) # set video width
cam.set(4, 480) # set video height
face_detector = cv2.CascadeClassifier('haarcascades/haarcascade_frontalface_default.xml')

# For each person, enter one numeric face id
face_id = input('\n enter user id end press <return> ==>  ')
print("\n [INFO] Initializing face capture. Look the camera and wait ...")

# Initialize individual sampling face count
count = 0
while(True):
    ret, img = cam.read()
    #img = cv2.flip(img, -1) # flip video image vertically
    gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
    faces = face_detector.detectMultiScale(gray, 1.3, 5)
    for (x,y,w,h) in faces:
        cv2.rectangle(img, (x,y), (x+w,y+h), (255,0,0), 2)     
        count += 1
        # Save the captured image into the datasets folder
        cv2.imwrite("dataset/User." + str(face_id) + '.' + str(count) + ".jpg", gray[y:y+h,x:x+w])
        cv2.imshow('image', img)
    k = cv2.waitKey(100) & 0xff # Press 'ESC' for exiting video
    if k == 27:
        break
    elif count >= 30: # Take 30 face sample and stop video
         break
# Do a bit of cleanup
print("\n [INFO] Exiting Program and cleanup stuff")
cam.release()
cv2.destroyAllWindows()
</pre>
<br>

추출해낸 얼굴 데이터(사진)를 통해 얼굴 학습을 실행함
<pre>
import cv2
import numpy as np
from PIL import Image
import os

# Path for face image database
path = 'dataset'
recognizer = cv2.face.LBPHFaceRecognizer_create()
detector = cv2.CascadeClassifier("haarcascades/haarcascade_frontalface_default.xml");

# function to get the images and label data
def getImagesAndLabels(path):
    imagePaths = [os.path.join(path,f) for f in os.listdir(path)]     
    faceSamples=[]
    ids = []
    for imagePath in imagePaths:
        PIL_img = Image.open(imagePath).convert('L') # convert it to grayscale
        img_numpy = np.array(PIL_img,'uint8')
        id = int(os.path.split(imagePath)[-1].split(".")[1])
        faces = detector.detectMultiScale(img_numpy)
        for (x,y,w,h) in faces:
            faceSamples.append(img_numpy[y:y+h,x:x+w])
            ids.append(id)
    return faceSamples,ids
print ("\n [INFO] Training faces. It will take a few seconds. Wait ...")
faces,ids = getImagesAndLabels(path)
recognizer.train(faces, np.array(ids))

# Save the model into trainer/trainer.yml
recognizer.write('trainer/trainer.yml') # recognizer.save() worked on Mac, but not on Pi
# Print the numer of faces trained and end program
print("\n [INFO] {0} faces trained. Exiting Program".format(len(np.unique(ids))))
</pre>
<br>

딥 러닝 과정 완료 후 얼굴을 인식해 얼굴 판별 기능을 실행함.
<pre>
import cv2
import numpy as np
import os

recognizer = cv2.face.LBPHFaceRecognizer_create()
recognizer.read('trainer/trainer.yml')
cascadePath = "haarcascades/haarcascade_frontalface_default.xml"
faceCascade = cv2.CascadeClassifier(cascadePath);
font = cv2.FONT_HERSHEY_SIMPLEX

#iniciate id counter
id = 0

# names related to ids: example ==> loze: id=1,  etc
# 이런식으로 사용자의 이름을 사용자 수만큼 추가해준다.
names = ['None', 'loze', 'ljy', 'chs', 'ksw']

# Initialize and start realtime video capture
cam = cv2.VideoCapture(0)
cam.set(3, 640) # set video widht
cam.set(4, 480) # set video height

# Define min window size to be recognized as a face
minW = 0.1*cam.get(3)
minH = 0.1*cam.get(4)

while True:
    ret, img =cam.read()
    img = cv2.flip(img, -1) # Flip vertically
    gray = cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)
    
    faces = faceCascade.detectMultiScale( 
        gray,
        scaleFactor = 1.2,
        minNeighbors = 5,
        minSize = (int(minW), int(minH)),
       )

    for(x,y,w,h) in faces:
        cv2.rectangle(img, (x,y), (x+w,y+h), (0,255,0), 2)
        id, confidence = recognizer.predict(gray[y:y+h,x:x+w])
        # Check if confidence is less them 100 ==> "0" is perfect match
        if (confidence < 100):
            id = names[id]
            confidence = "  {0}%".format(round(100 - confidence))
        else:
            id = "unknown"
            confidence = "  {0}%".format(round(100 - confidence))
        
        cv2.putText(img, str(id), (x+5,y-5), font, 1, (255,255,255), 2)
        cv2.putText(img, str(confidence), (x+5,y+h-5), font, 1, (255,255,0), 1)  
    
    cv2.imshow('camera',img) 
    k = cv2.waitKey(10) & 0xff # Press 'ESC' for exiting video
    if k == 27:
        break
# Do a bit of cleanup
print("\n [INFO] Exiting Program and cleanup stuff")
cam.release()
cv2.destroyAllWindows()
</pre>
<br>

![image](https://user-images.githubusercontent.com/62593236/101313832-81e01f00-389a-11eb-873d-fdd4b828683e.png)

얼굴 인식 과정(0%이상이면 얼굴 인식  성공).

### 어플

아두이노와 블루투스 연결하기 위한 코드를 작성하였고 블루투스 모듈을 받으면 아두이노와 실행시킬 예정.
라즈베리파이와의 연결은 블루투스연결이 원활하지 않아 소켓통신을 시도하고있으며, 
얼굴인식 시 첫 방문이 아닌 기존의 데이터에 있는 사용자일 경우 푸쉬알림이 가도록 설정하는 과정에 있음.

### 기계 제조

순서와 속도를 설정한 4개의 모터에 각각 음료재료들을 정해주고 
동작시간을 초단위로 설정하여, 컵에 담길 재료 양을 설정함.

<img src="https://user-images.githubusercontent.com/62593236/101311945-ed73bd80-3895-11eb-9e04-9ba73cfd82df.png" width="40%"></img> 

현재 
모터 1은 커피원액으로 설정했으며, 1.4초동안 30ml 추출하도록 설정함.
모터 2는 물로 설정하였으며, 9.6초동안 200ml 추출하도록 설정함.
모터 3은 우유로 설정하였으며, 11.2초동안 200ml 추출하도록 설정함.
모터 4는 시럽으로 설정하였으며,1.2초동안 10ml 추출하도록 설정함.


<img src="https://user-images.githubusercontent.com/62593236/101312135-58bd8f80-3896-11eb-950b-e14c5ff6ce31.png" width="60%"></img> 

각 모터를 활용하여 위에서 설정한 초단위를 바탕으로 레시피에 따라 각각의 음료를 제조할 수 있도록 번호를 부여하였음

<img src="https://user-images.githubusercontent.com/62593236/101312216-8acef180-3896-11eb-8c74-26f712f7496a.png" width="60%"></img>

정한 번호(이름)을 시리얼 모니터를 실행해 입력했을 때, 입력받은 이름의 모터가 작동하며 그에 맞는 음료가 제조됨.

<img src="https://user-images.githubusercontent.com/62593236/101312322-d1bce700-3896-11eb-9285-196612f4412c.png" width="60%"></img> 

<img src="https://user-images.githubusercontent.com/62593236/101312364-ebf6c500-3896-11eb-95dd-cc976c1d29a6.png" width="20%"></img> 

<img src="https://user-images.githubusercontent.com/62593236/101312414-09c42a00-3897-11eb-89af-68685f024f68.png" width="70%"></img> 

<img src="https://user-images.githubusercontent.com/62593236/101312470-2d877000-3897-11eb-9caf-e1343a093111.png" width="20%"></img> 

<img src="https://user-images.githubusercontent.com/62593236/101312521-4d1e9880-3897-11eb-99b7-fd84b7777011.png" width="70%"></img> 

<img src="https://user-images.githubusercontent.com/62593236/101312554-66274980-3897-11eb-8f6c-9cf6a8858fad.png" width="20%"></img> 

<img src="https://user-images.githubusercontent.com/62593236/101312588-7ccda080-3897-11eb-889d-5342ab633848.png" width="50%"></img> 

<img src="https://user-images.githubusercontent.com/62593236/101312636-97a01500-3897-11eb-87e6-d69f6cd1adc1.png" width="50%"></img> 





### 15주차 최종보고서

#### 팀장 : 이채린
#### 팀원 : 강정연, 이예림, 임진선, 김현승


### 머신러닝

14주차에서 작성한 얼굴 인식 코드에서 얼굴이 인식되는 부분(%가 0이 넘을 때)에 

어플 및 안드로이드 스튜디오에서 API키와 토큰을 받아와 알림이 전송되는 코드를 작성함


<pre>
import time
from pyfcm import FCMNotification

push_service = FCMNotification(api_key="Your_API_KEY")

mToken = "Your App Token"
nth = 0

def sendMessage(p):

    global nth
    nth += 1
    registration_id = mToken

    data_message = {
        "body" : "회원 인증에 성공하였습니다."
    }
    
    result = push_service.single_device_data_message(registration_id=registration_id,      data_message=data_message)
    print(result)

def _main():
    
    while True:
        sendMessage(80)
        time.sleep(60 * 1)

if __name__ == "__main__":
	_main()

</pre>
<br>

위 코드를 넣어준 뒤 얼굴 인식이 완료 되었을 때 알림 메시지 전송이 완료되었다고 나옴.

![image](https://user-images.githubusercontent.com/62593236/102030358-e00a8600-3df5-11eb-9688-0da209801029.png)

위와 같은 메시지에서 success가 뜨면 제대로 된 알림 전송이 완료된 것.

결과물 동작 전에 라즈베리파이에서 설정 내용 - https://youtu.be/CroAQbJxWLI

라즈베리파이 동작 영상 - https://youtu.be/uSz6iAdj3FM



### 어플

어플 실행시 로딩화면이 몇 초간 떴다가 메인화면이 뜸 

이 어플을 사용하기 위해서는 등록되어있는 사용자 인증이 필요함

메인화면이 켜짐과 동시에 안드로이드 로그창에 기기의 token을 읽어옴

라즈베리파이에 등록해놓은 앱 token과 일치하면 얼굴인식을 진행해 등록되어있는 얼굴데이터와 비교과정을 거침

얼굴인식에 성공하면 어플사용자 인증이 완료된 것으로, 인증이 완료됨과 동시에 메뉴를 선택할 수 있는 화면으로 전환됨

메뉴를 선택하면 기기와 기계를 연결하기 위해 블루투스 통신하는 화면으로 넘어감

맞음 버튼을 누르고 블루투스 기기를 선택한 뒤 제조시작 버튼을 누르면 음료가 나오며 제조완료 페이지로 넘어감

<img src="https://user-images.githubusercontent.com/62593236/102027930-b5670000-3dea-11eb-922a-df83b73de973.png" width="30%"><img src="https://user-images.githubusercontent.com/62593236/102027950-ddeefa00-3dea-11eb-8ae6-064712d125a7.png" width="30%"><img src="https://user-images.githubusercontent.com/62593236/102027966-0d9e0200-3deb-11eb-83d5-32c769541582.png" width="30%">
<img src="https://user-images.githubusercontent.com/62593236/102027978-1d1d4b00-3deb-11eb-9e60-7762f8af127a.png" width="25%"><img src="https://user-images.githubusercontent.com/62593236/102028039-6b324e80-3deb-11eb-8dde-5ac495921969.png" width="25%"><img src="https://user-images.githubusercontent.com/62593236/102028052-800ee200-3deb-11eb-833b-6dadc1f7b54f.png" width="25%"><img src="https://user-images.githubusercontent.com/62593236/102028059-8d2bd100-3deb-11eb-8a6d-6115efce7dd1.png" width="25%">

MainActivity에서는 얼굴인식을 바로 실행하기 위해 현재 등록되어있는 토큰을 읽어오는 메소드를 실행시킴
<pre>
public class MainActivity extends AppCompatActivity {

    @NotNull
    private final String TAG = "MainActivity";
    @NotNull
    public final String getTAG() {
        return this.TAG;
    }

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        FirebaseMessaging.getInstance().getToken()
                .addOnCompleteListener(new OnCompleteListener<String>() {
                    @Override
                    public void onComplete(@NonNull Task<String> task) {
                        if (!task.isSuccessful()) {
                            Log.w(TAG, "Fetching FCM registration token failed", task.getException());
                            return;
                        }
                        String token = task.getResult();
                        Log.d(TAG, token);
                    }
                });
    }
}
</pre>
<br>

라즈베리파이와 안드로이드 사이에 통신할 수 있는 FirebaseCloudMessaging 서비스를 추가함. 
onNewToken은 새로운 토큰이 생성되는 경우에 실행되며, onMessageReceived은 토큰이 일치해 메세지를 상대 기기로부터 받았을 때 실행됨. 메세지를 받으면 안드로이드 로그창에 라즈베리에 설정해두었던 인증완료 메세지가 생성됨.

![image](https://user-images.githubusercontent.com/62593236/102034952-9d02df80-3e02-11eb-929f-b1d61b5beefb.png)

그리고 sendNotification로 알림이 올때의 설정들을 추가해두었음.

<pre>
public class MyFirebaseMessagingService extends FirebaseMessagingService {
    private static final int FLAG_ACTIVITY_NEW_TASK =  0x10000000;
    @NotNull
    private final String TAG = "Service";

    @NotNull
    public final String getTAG() {
        return this.TAG;
    }

    @Override
    public void onNewToken(String s) {
        super.onNewToken(s);
        Log.d("NEW_TOKEN",s);
    }
    @Override
    public void onMessageReceived(RemoteMessage remoteMessage) {
        Log.d(this.TAG, "From: " + remoteMessage.getFrom());
        Log.d(this.TAG, String.valueOf(remoteMessage.getData().get("body")));
        this.sendNotification(remoteMessage);

        Intent intent = new Intent(this, MenuActivity.class);
        startActivity(intent.addFlags(FLAG_ACTIVITY_NEW_TASK));
        
    }
    private final void sendNotification(RemoteMessage remoteMessage) {
        Intent intent = new Intent((Context)this, MainActivity.class);
        intent.addFlags(Intent.FLAG_ACTIVITY_CLEAR_TOP);
        PendingIntent pendingIntent = PendingIntent.getActivity((Context)this, 0, intent, PendingIntent.FLAG_ONE_SHOT);
        Uri defaultSoundUri = RingtoneManager.getDefaultUri(RingtoneManager.TYPE_NOTIFICATION);
        NotificationCompat.Builder notificationBuilder = new NotificationCompat.Builder(this)
                .setSmallIcon(R.mipmap.ic_launcher)
                .setAutoCancel(true)
                .setSound(defaultSoundUri)
                .setContentText(remoteMessage.getData().get("body"))
                .setContentIntent(pendingIntent);
        
        NotificationManager notificationManager = (NotificationManager) getSystemService(Context.NOTIFICATION_SERVICE);
        notificationManager.notify(0,notificationBuilder.build());
        
    }
}
</pre>
<br>

MenuActivity에서는 각 메뉴를 클릭하면 액티비티가 이동할 수 있게 설정해두었음.
<pre>
public class MenuActivity extends AppCompatActivity {

    private Button btn1;
    private Button btn2;
    private Button btn4;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_menu);
        btn1 = findViewById(R.id.btn_Americano);
        btn2 = findViewById(R.id.btn_Vanilla_Latte);
        btn4 = findViewById(R.id.btn_Cafe_Latte);


        btn1.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent intent1 = new Intent(MenuActivity.this , ArduinoActivity.class);
                startActivity(intent1);
            }
        });
        btn2.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent intent1 = new Intent(MenuActivity.this , arduinoActivity3.class);
                startActivity(intent1);
            }
        });
        btn4.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent intent1 = new Intent(MenuActivity.this , ArduinoActivity2.class);
                startActivity(intent1);
            }
        });
    }
}
</pre>
<br>

ArduinoActivity는 안드로이드와 아두이노 블루투스 모듈을 연결시키는 액티비티임. 
setBluetoothConnectionListener를 통해 btnConnect 버튼을 누르면 블루투스 기기를 선택하여 연결할 수 있고, 연결되면 음료제조를 시작해도 좋다는 토스트메세지를 띄움. 
 연결이 됐으면 setup()메소드를 통해 아두이노 시리얼 모니터에 data를 전송함. onActivityResult는 현재 액티비티의 반환 액티비티로, 연결 가능한 디바이스와 연결 시도 후 연결에 성공하면 데이터를 전송하고, 보내지 못함을 의미함.

<pre>
public class ArduinoActivity extends AppCompatActivity {

    private BluetoothSPP bt;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_arduino);
        bt = new BluetoothSPP(this);


        if (!bt.isBluetoothAvailable()) {
            Toast.makeText(getApplicationContext()
                    , "Bluetooth is not available"
                    , Toast.LENGTH_SHORT).show();
            finish();
        }

        bt.setOnDataReceivedListener(new BluetoothSPP.OnDataReceivedListener() {
            public void onDataReceived(byte[] data, String message) {
                Toast.makeText(ArduinoActivity.this, message, Toast.LENGTH_SHORT).show();
            }
        });

        bt.setBluetoothConnectionListener(new BluetoothSPP.BluetoothConnectionListener() {
            public void onDeviceConnected(String name, String address) {
                    Toast.makeText(getApplicationContext()
                        , "제조시작 버튼을 눌러주세요 !"
                        , Toast.LENGTH_SHORT).show();
            }

            public void onDeviceDisconnected() {
                Toast.makeText(getApplicationContext()
                        , "Connection lost", Toast.LENGTH_SHORT).show();
            }

            public void onDeviceConnectionFailed() {
                Toast.makeText(getApplicationContext()
                        , "연결에 실패하였습니다ㅠㅠ", Toast.LENGTH_SHORT).show();
            }
        });
        Button btnConnect = findViewById(R.id.btnConnect);
        btnConnect.setOnClickListener(new View.OnClickListener() {
            public void onClick(View v) {
                if (bt.getServiceState() == BluetoothState.STATE_CONNECTED) {
                    bt.disconnect();
                } else {
                    Intent intent = new Intent(getApplicationContext(), DeviceList.class);
                    startActivityForResult(intent, BluetoothState.REQUEST_CONNECT_DEVICE);
                }
            }
        });
    }
    public void onDestroy() {
        super.onDestroy();
        bt.stopService();
    }
    public void onStart() {
        super.onStart();
        if (!bt.isBluetoothEnabled()) {
            Intent intent = new Intent(BluetoothAdapter.ACTION_REQUEST_ENABLE);
            startActivityForResult(intent, BluetoothState.REQUEST_ENABLE_BT);
        } else {
            if (!bt.isServiceAvailable()) {
                bt.setupService();
                bt.startService(BluetoothState.DEVICE_OTHER);
                setup();
            }
        }
    }
    public void setup() {
        Button btnSend = findViewById(R.id.btnSend);
        btnSend.setOnClickListener(new View.OnClickListener() {
            public void onClick(View v) {
                bt.send("1", true);

                Intent intent = new Intent(ArduinoActivity.this, SuccessActivity.class);
                startActivity(intent);
            }
        });
    }
    public void onActivityResult(int requestCode, int resultCode, Intent data) {
        super.onActivityResult(requestCode, resultCode, data);
        if (requestCode == BluetoothState.REQUEST_CONNECT_DEVICE) {
            if (resultCode == Activity.RESULT_OK)
                bt.connect(data);
        } else if (requestCode == BluetoothState.REQUEST_ENABLE_BT) {
            if (resultCode == Activity.RESULT_OK) {
                bt.setupService();
                bt.startService(BluetoothState.DEVICE_OTHER);
                setup();
            } else {
                Toast.makeText(getApplicationContext()
                        , "Bluetooth was not enabled."
                        , Toast.LENGTH_SHORT).show();
                finish();
            }
        }
    }
}
</pre>
<br>

<pre>
public class SuccessActivity extends AppCompatActivity {

    private Button back;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_success);

        back = findViewById(R.id.back);

        back.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent intent1 = new Intent(SuccessActivity.this , MainActivity.class);
                startActivity(intent1);
            }
        });

    }

}
</pre>
<br>


### 기계제조

아두이노 & 드라이버쉴드에 블루투스모듈 연결함

아두이노와 안드로이드 어플이 서로 통신하기 위한 블루투스 모듈을 연결하였다. 이 과정에서 추가적으로 핀헤드와 암수케이블, 그리고 납땜 과정이 필요하였음

2개의 암케이블은 아래 사진과 같이, 핀헤드를 드라이버 쉴드 5V와 GND 핀에 납땜하여 연결할 수 있었고

![image](https://user-images.githubusercontent.com/62593236/102033327-80fd3f00-3dfe-11eb-9503-27785122ea74.png)![image](https://user-images.githubusercontent.com/62593236/102033334-85295c80-3dfe-11eb-80bd-8517fd05e8d6.png)

나머지 2개의 암케이블은 헤더를 자르고 피복을 벗겨 드라이버쉴드 2,3번 핀에 아래 사진과 같이 직접 납땜하여 연결하였음

![image](https://user-images.githubusercontent.com/62593236/102033339-88244d00-3dfe-11eb-87d2-6d5dc35bc85d.png)

4개의 암케이블을 준비하여 블루투스 모듈, 암케이블, 드라이버 쉴드순으로 연결하였음
RX-갈색-3번핀 , TX-검은색-2번핀, GND-빨간색-GND, VCC-주황색-5V

![image](https://user-images.githubusercontent.com/62593236/102033344-8c506a80-3dfe-11eb-875f-013deb1e5c2a.png)

코드수정 및 테스트, 

모터가 가동할 수 있도록 작성해두었던 코드에서, 블루투스 연결을 할 수 있도록 코드를 추가하고 수정하였음

먼저 아두이노에 블루투스 연결을 확인하기 위한 테스트 코드를 아래와 같이 작성하였고

![image](https://user-images.githubusercontent.com/62593236/102033349-8fe3f180-3dfe-11eb-9b4f-841463054946.png)

시리얼 모니터에 연결을 확인하기 위해 “AT"를 입력하였음

![image](https://user-images.githubusercontent.com/62593236/102033359-93777880-3dfe-11eb-926d-74e8b5941c46.png)

아래와 같이 OK 가 출력되는 것을 확인하여, 블루투스 연결이 성공한 것을 알 수 있었음

![image](https://user-images.githubusercontent.com/62593236/102033363-97a39600-3dfe-11eb-8f54-e9d8e6ffd3e8.png)

따라서, 모터를 작동시킬 수 있는 코드에 블루투스 연결을 할 수 있도록 코드즐 추가, 수정하였음

![image](https://user-images.githubusercontent.com/62593236/102033366-9b371d00-3dfe-11eb-8ea3-7da67140b6ce.png)
![image](https://user-images.githubusercontent.com/62593236/102033370-9e320d80-3dfe-11eb-9474-95b88dba8d23.png)
![image](https://user-images.githubusercontent.com/62593236/102033373-a1c59480-3dfe-11eb-8d79-af4281550198.png)

어플과 연결한 후 어플의 값이 아두이노로 전달이되어 음료가 추출되면, 
아두이노의 시리얼 모니터에는 다음과 같이 어떤음료가 추출되는지 표시됨

![image](https://user-images.githubusercontent.com/62593236/102033378-a4c08500-3dfe-11eb-8e40-6de3eab8a0c7.png)

기계셋팅 및 조립 

앞면, 호스밑에 컵을 놓을 수 있도록 조립

![image](https://user-images.githubusercontent.com/62593236/102033388-a8eca280-3dfe-11eb-965a-b09fa9e19384.png)

뒷면, 음료 재료들과 펌프, 블루투스 모듈과 드라이버 쉴드가 연결된 아두이노, 파이캠이 연결된 라즈베리파이를 부착하여 기기 앞면에서 얼굴을 인식할 수 있도록 함

![image](https://user-images.githubusercontent.com/62593236/102033395-adb15680-3dfe-11eb-888c-ea50433918b8.png)

추출 후 뒷면을 확인하였을 때 줄어든 재료의 양을 확인할 수 있음

![image](https://user-images.githubusercontent.com/62593236/102033406-b144dd80-3dfe-11eb-94c6-c116a17b5c5f.png)

아메리카노, 카페라떼, 바닐라라떼 순으로 추출

![image](https://user-images.githubusercontent.com/62593236/102033411-b4d86480-3dfe-11eb-807a-03d85853fdc0.png)![image](https://user-images.githubusercontent.com/62593236/102033413-b7d35500-3dfe-11eb-9179-4404eafd74cd.png)![image](https://user-images.githubusercontent.com/62593236/102033421-bc980900-3dfe-11eb-88bb-1f6d1d4189cc.png)

