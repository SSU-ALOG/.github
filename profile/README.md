# 📢 사회적 안전 정보 통합 서비스, **ALOG** ⛑️🆘
📺 **[ALOG 시연영상 보러가기 (Youtube)](https://youtu.be/tlKO2gDIQOA?si=sg-wQaVhFZZxOSYn)**  
🔗 **[ALOG 앱 다운로드하기 (Android)](https://github.com/SSU-ALOG/alog_application/releases/download/v1.0.0/app-release.apk)**  

- 각종 사건, 사고, 재난, 질병 정보를 지도로 한 눈에
- 현장에서 일어나고 있는 상황을 라이브 스트리밍
- 근처에서 발생한 사건 사고 알리미
- 재난재해 대처 방법, 재난 문자 등 필수 안전 정보 제공

![2조_ALOG_포스터](https://github.com/user-attachments/assets/20da0918-9484-418c-965d-fb3a8b10396d)

# 🐣 팀원 및 개발 파트

|**김유림**|**윤서빈**|**이진**|**조예원**|
|---|---|---|---|
|라이브 스트리밍|사고 등록, 사건 사고 알리미 및 모아보기|재난 문자 모아보기 및 정보 게시판|위험 정보 지도 및 데이터 시각화|
---

# ✏️ 서론: 서비스 소개

## 1. 서비스 추진 배경 및 목적

  소셜 미디어의 활성화로 인해 개인이 자유롭게 다양한 정보를 공유할 수 있게 되었고, 이는 안전과도 밀접한 연관성을 가지게 되었다. 지난 여러 사건 사고에서 시민들이 촬영한 사진과 영상은 소셜 미디어를 통해 빠르게 확산되어 언론과 정부가 재난의 심각성을 신속히 인지하고 대응하는 데 중요한 역할을 했다. 소셜 미디어는 실시간 상황 파악에 중요한 정보원으로 기능하지만, 동시에 자극적이고 출처가 불분명한 정보 또한 함께 퍼지고 있다. 특히 재난 상황에서 이러한 잘못된 정보는 혼란과 불안감을 조성하고, 정확한 정보 파악을 어렵게 만든다. 따라서 재난 상황에서는 정확하고 신뢰할 수 있는 정보 제공이 무엇보다 중요하다. 그러나 기존의 안전 관련 서비스를 살펴보면 정보가 분산되어 있을 뿐만 아니라, 시민들이 필요로 하지 않는 통계나 보고서 등 불필요한 정보까지 제공되고 있음을 알 수 있다.
 
  이러한 문제를 해결하기 위해, 본 서비스는 소셜 미디어와 다양한 출처에 흩어진 정보를 한 곳에 모아 정확하고 실질적인 안전 정보를 제공하는 것을 목적으로 한다. 또한 시민들의 제보를 체계적으로 수집하고, 라이브 스트리밍 기능을 통해 실시간으로 상황을 파악함으로써 잘못된 정보로 인한 혼란을 줄이고, 신속하고 효과적인 대응을 가능하게 한다. 궁극적으로 사용자가 언제 어디서나 신속하게 정보를 확인하고 공유하며 대응할 수 있는 사회적 안전 정보 통합 서비스를 제공함으로써 사회적 안전망을 강화하는 데 기여하고자 한다.

## 2. 서비스 개요

  **ALOG(Accident LOG)** 는 각종 사건, 사고, 재난, 질병 정보를 실시간으로 한눈에 확인할 수 있는 사회적 안전 정보 통합 서비스다. 사용자는 지도를 통해 현재 발생하고 있는 범죄, 건강 위해, 안전사고, 자연재해 등 다양한 주제의 정보를 쉽게 확인할 수 있다. 사용자 근처에서 새로운 사건 사고가 발생하는 경우, 그에 대한 알림과 재난문자, 재난 상황별 대처 방법 등 필수 안전 정보를 제공해 사용자가 긴급 상황에 신속하게 대응할 수 있도록 돕는다. 또한 사용자가 직접 이슈를 등록할 수 있으며, 라이브 스트리밍을 통해 현장 상황을 공유하고 소통할 수 있다. 다른 사용자들은 스트리밍을 통해 현장 상황을 실시간으로 파악하고 이슈에 대한 이해도를 높일 수 있다.

# ✨ 본론

## 1. 개발 환경 구성

##### [기술 스택 구성도]
![image](https://github.com/user-attachments/assets/61bdf4db-bb73-4f8b-8908-8da991ff4c8e)

#### 기획 및 설계
   <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/> : 프론트 프로토타입, 서비스 정보구조, 인프라 아키텍처 설계  
   <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white"/> : 서비스 기획 및 협업 문서 관리
#### 협업
   <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> : 프로젝트 협업 및 버전 관리  
#### 인프라 
   <img src="https://img.shields.io/badge/Naver Cloud Platform-03C75A?style=flat-square&logo=naver&logoColor=white"/> : 전체 인프라 호스팅  
#### 개발
   <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/> : Flutter와 .dart 파일 관리를 위한 IDE  
   <img src="https://img.shields.io/badge/Android Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white"/> :  안드로이드 앱 개발을 위해 사용  
   <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> : 데이터 크롤링 서버 구축  
   <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=flat-square&logo=intellij-idea&logoColor=white"/> : Spring Boot 서버 개발 시 사용  
   <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> : 정형 데이터 저장 (재난 정보 등)  
   <img src="https://img.shields.io/badge/Object Storage-000000?style=flat-square&logo=objectstorage&logoColor=white"/> : 비정형 데이터 저장 (영상 정보)  
   <img src="https://img.shields.io/badge/Google Cloud Firestore-DD2C00?style=flat-square&logo=firebase&logoColor=white"/> : 비정형 데이터 저장 (채팅 내역)  
   <img src="https://img.shields.io/badge/Naver Cloud Live Station-03C75A?style=flat-square&logo=naver&logoColor=white"/> : 실시간 스트리밍 서비스  
   <img src="https://img.shields.io/badge/Naver Maps API-03C75A.svg?style=flat-square&logo=naver&logoColor=white"/> : 재난 위치를 프론트에서 지도상에 표시  
   <img src="https://img.shields.io/badge/Naver login-03C75A?style=flat-square&logo=naver&logoColor=white"/> : 네이버 로그인 기능  

##### [Cloud Architecture] VPC를 이용해 public subnet 2개, private subnet 1개로 구성.
![image](https://github.com/user-attachments/assets/112ec20c-3006-4dea-8bb0-ad66edfd132b)

- 각각의 subnet은 ACL를 이용해 인바운드, 아웃바운드 규칙 설정.
- private subnet에는 보안이 필요한 Cloud DB for MySQL 및 Object Storage 배치.
- 하나의 public subnet에는 live station, load balancer를 배치하고, live station은 트래픽이 몰리는 것을 방지하기 위해 load balancer로 접근.
- 다른 public subnet에는 여러 대의 server, load balancer, api gateway 배치. 트래픽 분산을 위해 load balancer를 통해 server에 접근. api gateway는 naver maps, naver login api와 같은 외부 api와의 통신을 담당.
- Cloud Log Analytics, App safer, ELSA 서비스를 이용해 애플리케이션 운영 상태를 모니터링하고 보안 강화.

##### [ERD]
![image](https://github.com/user-attachments/assets/beea1fe6-bd3a-4603-9583-274f1b422c43)

##### [Firestore 컬렉션과 문서]
![image](https://github.com/user-attachments/assets/69e6f8c2-b6d7-43e8-879c-2d3262d69958)

## 2. 사용 데이터 및 기술

각 데이터는 전처리를 통해 실시간으로 DB에 저장되고 활용된다. 

- 재난안전데이터공유플랫폼 긴급재난문자 API
  - 메시지내용, 수신지역명, 긴급단계명, 재해구분명, 등록일자에 대한 데이터로 재난 문자 모아보기 화면에서 분류 및 검색에 활용
- 국민재난안전포털 교통정보 데이터        
  - 사고 내용, 위치, 시간에 대한 데이터로 안전사고로 분류  
- 소방청 화재출동현황 데이터        
  - 관할 소방서, 일시, 주소, 진행 상황에 대한 데이터로 재난으로 분류 
- 국민재난안전포털 가축질병 데이터        
  - 농장주소, 병명, 진단일시에 대한 데이터로 동식물 재난으로 분류   
- 서울시 실시간 도시데이터 인파 안전 API        
  - 장소명, 실시간 인구현황, 장소 혼잡도 지표, 위치 정보 등에 대한 데이터로 도시 서비스 마비로 분류
- 서울시 실시간 돌발 정보 API        
  - 도로 통제 정보 제공. 돌발 유형, 발생 일자, 좌표, 돌발 내용에 대한 데이터로 도시 서비스 마비로 분류        
- 국가교통정보센터 돌발상황정보 API       
  - 도로 공사, 사고 도시 서비스 마비에 대한 정보 제공. 일시, 유형, 위치, 돌발구분, 돌발내용, 종료일시 데이터로 도시 서비스 마비로 분류
- 국민재난안전포털 재난안전뉴스        
  - 언론사에서 제공하는 안전 뉴스로 주요 내용은 관리자 검열 후 사건 등록하여 사용함.        
- 행정안전부 안전관리일일상황        
  - 행정안전부에서 제공하는 안전관리일일상황 정보로 주요 내용은 관리자 검열 후 사건 등록하여 사용함.


API로부터 데이터를 가져오는 경우는 다음과 같은 과정을 거친다.

##### [재난안전데이터공유플랫폼 긴급재난문자 API 데이터]
![image](https://github.com/user-attachments/assets/647b4869-5556-4f11-8840-42fbc30f6ae1)

##### [전처리를 거쳐 DB에 저장된 재난문자 데이터]
![image](https://github.com/user-attachments/assets/aa8d7d71-3492-40b9-9525-fd818114aea3)

API가 아닌 사이트로부터 데이터를 가져오는 경우는 다음과 같은 과정을 거친다.
##### [국민재난안전포털 교통정보 데이터]
![image](https://github.com/user-attachments/assets/47848bf5-663a-4266-97f1-82af774e1d88)

##### [크롤링 및 전처리를 거친 교통정보 데이터]
![image](https://github.com/user-attachments/assets/b5a62d2b-bd47-428d-9beb-2d6a3a0c5595)

##### [DB에 저장된 교통정보 데이터]
![image](https://github.com/user-attachments/assets/f6de0d3a-5436-4180-a53e-17533ce57328)


## 3. 서비스 화면 및 기능 설명

### 🌱 지도
![image](https://github.com/user-attachments/assets/840756c4-7612-4cbf-889f-f1b8afc267f9)

- 현재 발생하고 있는 사건, 사고, 질병, 재난 정보를 지도로 한 눈에 볼 수 있음.
- 필터링 기능을 통해 원하는 주제의 정보를 구분해 볼 수 있음.

|**분류**|**상세 내용**|
|---|---|
|범죄|성범죄, 사이버범죄(개인정보 유출, 보이스피싱·해킹, 몰카 등 사생활 침해), 강력죄(흉악 범죄, 묻지마 범죄 등)|
|건강위해|	감염병 및 신종 질환, 식품 안전(식중독), 생활환경 독성 확산(살균제, 살충제, 물티슈 등 화학물질)|
|안전사고|	생활 주변 환경 안전사고, 공연장, 경기장 등 다중밀집장소 깔림/압사 등 사고|
|자연재해|	홍수, 태풍, 가뭄, 대형산불, 산사태, 폭염 및 한파, 화산 폭발, 지진 및 쓰나미, 씽크홀(땅꺼짐) 등|
|재난|방사능 누출, 화학물질 유출, 화재, 교통(도로, 철도, 지하철, 항공, 선박 등) 사고 등|
|동식물 재난|가축전염병, 식물유행병(산림 또는 농작물 병충해), 유해 조수 및 곤충 확산|
|도시 서비스 마비|급수중단, 에너지 공급 마비, 보건의료 서비스 마비, 대중교통 마비, 유통체계 마비, 생활 폐기물 수거 마비, 공공청사 기능 및 서비스 마비|
|디지털 서비스 마비|ex) 카카오톡 마비, 통신사 마비|

- 사용자가 직접 이슈를 등록할 수 있음.
  - 관리자가 등록된 이슈의 내용을 확인하고 확인된 정보는 검증 표식을 붙여 정보의 정확성을 높임.

### 🌱 라이브 스트리밍
![image](https://github.com/user-attachments/assets/2cb41db8-22f5-48e2-b772-9331e34c8a24)
- 사용자의 위치 정보를 파악해 현장에 있는 사용자에 한해 재난 현장을 스트리밍 할 수 있음.
- 라이브 스트리밍을 보면서 실시간으로 채팅을 할 수 있음.
- 이후 관리자가 스트리밍 영상을 간략화 한 영상을 업로드하여 이용자가 해당 이슈의 현장을 확인할 수 있도록 도움.

### 🌱 사건 사고 알리미
![image](https://github.com/user-attachments/assets/3e042708-ef75-4821-9523-78d9b1637298)
- 사용자 근처에서 사건, 사고가 발생한 경우 알림을 보냄.

### 🌱 사건 사고 모아보기
![image](https://github.com/user-attachments/assets/22e3c0a4-d5e1-461e-9d42-ebbf89b9cdcc)
- 현재까지 일어난 사건 사고 기록을 모아볼 수 있음.

### 🌱 재난 문자 모아보기
![image](https://github.com/user-attachments/assets/47cfc3c4-065b-49c4-b305-f88cc900c67d)
- 위급재난문자/긴급재난문자/안전안내문자/실종알림문자를 모아볼 수 있음.
- 긴급단계별, 발송지역별 문자를 구분해 볼 수 있음.

### 🌱 정보 게시판
![image](https://github.com/user-attachments/assets/38055c5f-f6c6-40fa-82f0-f5a508a5fffd)
- 재난별 대처 방법 등 필수 안전 정보를 국민재난안전포털과 연결하여 제공함.

## 4. 서비스 흐름도

##### [서비스 정보 구조(IA)]
![image](https://github.com/user-attachments/assets/b26b4126-cab9-4543-96bc-fd7375f86461)

##### [서비스 흐름도]
![image](https://github.com/user-attachments/assets/8bd75b87-6fb0-47c8-b5ef-bea4f7d4d0b4)


## 5. 사용자 시나리오

### 🌱 지도 화면

- 사용자 위치를 중심으로 지도 위에 이슈를 표시함.
    - 각 이슈는 발생 일시로부터 종료 일시까지 표시됨.
    - 각 표시는 원형의 핀이며, 해당 이슈에 대한 라이브 스트리밍 시청자 수가 많을수록 그 크기가 커짐.
    - 진행 중인 라이브 스트리밍이 없거나 시청자 수가 없을 경우 최소 크기로 표시됨.
- 검색창을 통해 원하는 키워드의 이슈를 검색해 볼 수 있음.
- 필터를 통해 원하는 카테고리의 이슈를 필터링해 볼 수 있음.
- 각 이슈 핀을 클릭하면 사건 정보창이 표시됨.
    - 사건 제목, 분류, 설명이 표시됨.
    - 영상을 클릭해 라이브 스트리밍을 볼 수 있음.
    - 관리자에 의해 확인된 정보에는 체크 마크가 표시됨.
- 하단의 bottom sheet를 끌어올리면 현재 지도에 표시된 이슈 목록을 볼 수 있음.
    - 목록의 각 이슈를 클릭하면 사건 정보창이 표시됨.
- 사용자 위치를 기준으로 1km 반경 내의 이슈에 대해서 사용자의 방송 권한이 활성화 됨.
    - 사건 정보창에 라이브 스트리밍 버튼이 활성화 됨.
    - 활성화 된 버튼 클릭 시 라이브 스트리밍을 시작할 수 있음.

### 🌱 사고 등록 화면

- 상단 바의 왼쪽 아이콘을 클릭해 새로운 이슈를 등록할 수 있음.
  - 사고 제목, 분류, 위치, 설명을 기입해 등록함.

### 🌱 라이브 스트리밍 화면

- 라이브 송출자는 활성화된 라이브 스트리밍 버튼을 통해 방송을 시작함.
    - 카메라 전환, 마이크 on/off, 화면 on/off 기능을 통해 방송 상태를 조절함.
    - 엑스 버튼으로 방송을 종료할 수 있음.
- 라이브 시청자는 진행중인 라이브 스트리밍 목록에서 시청하고 싶은 방송을 선택해 입장함.
    - 채팅을 통해 송출자 또는 다른 시청자와 소통할 수 있음.

### 🌱 재난 문자 모아보기 화면

- 송신된 재난 문자를 실시간으로 가져와 보여줌.
- 재난문자는 1주 전에 수신된 것까지 열람이 가능함.
- 검색창에 내용을 입력해 원하는 재난문자 검색이 가능함.
- 긴급단계 및 발송지역 탭을 선택하여 수신된 재난문자를 해당 분류에 따라 정렬하여 열람 할 수 있음.
- 긴급단계 탭
    - 위급재난, 긴급재난, 안전안내, 실종알림 필터를 이용하여 필터링한 재난문자를 볼 수 있음.
- 발송지역 탭
    - 대상 지역을 드롭다운 버튼을 이용하여 시도, 시군구,  읍면동을 선택함.

### 🌱 정보 게시판 화면

- 자연재난, 사회재난, 생활안전, 비상대비 탭으로 분류하여 행동요령을 볼 수 있음.
- 탭 내부의 행동요령을 선택하면 해당 상황에서의 국민재난안전포털의 행동요령을 볼 수 있음.
- 검색창에 키워드를 입력하여 행동요령을 검색할 수 있음.
 
### 🌱 사건 사고 모아보기 화면
- 현재 날짜 기준으로 일주일 이내의 모든 재난 정보를 모아볼 수 있음.
- 재난 카테고리별, 진행 상황별, 지역별 필터를 적용할 수 있음.
- 검색어를 통해 키워드를 포함한 재난 정보를 확인할 수 있음.
- 각각의 이벤트 카드를 누르면 해당 재난 정보(사고명, 발생일, 상세내용, 위치, 재난 상황 등)와 라이브 스트리밍을 클립화 한 영상을 확인할 수 있음.

### 🌱 마이페이지 화면
- 네이버에 저장된 정보(프로필 사진, 닉네임, 이메일, 연락처 등)을 확인할 수 있음.
- 네이버 로그아웃 기능
- 네이버 로그인 연동 해제할 수 있음.

### 🌱 사건 사고 알림 화면

- 현재 위치 기준 1km 내의 사건, 사고에 대한 알림을 수신함.
- 알림 클릭 시 해당 사건이 표시된 지도 화면으로 넘어감.

# ✅ 결론

## 1. 기대 효과 🤩

#### 1. 정보 제공의 신속성과 정확성 강화    
다양한 출처의 안전 정보를 실시간으로 통합하여 제공해 사용자가 정확하고 신뢰할 수 있는 정보를 신속하게 확인할 수 있다. 사건·사고 발생 시 사용자에게 즉각적으로 알림을 제공할 뿐만 아니라, 각 재난 상황별 대처 방법을 함께 제공하여 사용자들의 재난 대응 능력을 향상시킨다.    

#### 2. 구조 효율성 증대    
라이브 스트리밍 기능은 단순한 정보 공유를 넘어서 재난 현장에 있는 사람들이 자신의 위치를 알리고 구조 요청을 할 수 있는 도구로 작용한다. 이를 통해 구조대는 현장 상황을 정확히 파악하고 신속하게 대응할 수 있으며, 구조의 효율성을 높이는 데 기여한다. 실시간으로 상황을 공유함으로써 구조대가 가장 필요한 곳에 적절한 자원을 배치할 수 있다.

#### 3. 안전 관련 정책 수립에 기여   
ALOG 서비스를 통해 수집된 다양한 재난 관련 데이터는 정부나 관련 기관이 향후 재난 대응 정책을 수립하는 데 중요한 자료로 활용될 수 있다. 시민들의 실시간 제보와 다양한 재난 유형별 데이터는 정책 수립에 있어 현실적인 피드백을 제공하고, 보다 효과적인 대응책 마련을 지원할 수 있다.

#### 4. 사회적 안전망 강화   
재난 정보를 통합적으로 제공하고 시민들이 직접 참여하여 재난 상황을 공유함으로써, 지역 사회에서 일어나는 안전 이슈에 대한 대응 능력을 높인다. 사용자는 언제 어디서나 안전한 상태를 확인하고 대응할 수 있게 되며, 이는 사회적 안전망을 강화하여 보다 안전한 사회를 만드는 데 기여할 것이다. 

#### 5. 신뢰할 수 있는 안전 정보 플랫폼으로 성장
ALOG는 통합된 재난 정보를 제공하고 시민 참여를 통해 재난 상황을 공유함으로써 사회적 안전망을 강화한다. 또한, 라디오 기능, AI 챗봇, 실시간 병상 수용 정보 등의 기능을 추가하여 서비스를 지속적으로 확장할 수 있다. 이는 다양한 재난 유형에 맞춘 서비스 확장성을 보여주며, 기술적 진보와 함께 지속적으로 발전할 수 있는 안전 정보 통합 플랫폼으로 성장할 수 있다.

## 2. 개선 방향 🛠️

#### 1. 관리자 페이지
현재 애플리케이션은 관리자와 일반 사용자가 동일한 인터페이스를 사용하도록 설계되어 있어, 관리 업무와 일반 사용자의 기능 간 구분이 명확하지 않다. 이는 사건·사고 신고와 라이브 스트리밍 콘텐츠의 검토 및 승인 과정에서 비효율성을 초래할 수 있다. 관리자 페이지를 별도로 구현함으로써 플랫폼 운영을 체계화하고 신고 및 콘텐츠 검수 과정을 효율적으로 개선할 수 있다. 

#### 2. 신고 시스템
현재는 사용자가 라이브 스트리밍을 송출할 수 있지만, 신고 시스템이 구현되지 않아 사용자의 무분별한 방송 송출이 가능하다. 신고 시스템을 제공하여 현장에 있는 사용자가 제공하는 자극적인 소셜 미디어 콘텐츠와 있는 정보를 방지함으로써 잘못된 정보의 확산이 되는 것을 막고, 트라우마를 유발할 수 있는 자극적인 내용을 검열해 사용자들이 안정된 환경에서 정보를 얻을 수 있게 할 수 있다.

#### 3. 대피요령 정보 내재화
기존 안전정보 화면은 국민재난안전포털의 행동요령 페이지로 연결하여 사용자가 해당 URL에 접속해 필요한 정보를 열람하는 방식을 사용하고 있다. 하지만 재난 상황에서 통신 상태가 원활하지 않을 가능성을 고려하여, 사용자들이 인터넷 연결 없이도 필요한 대피 요령을 확인할 수 있도록 어플리케이션 자체에 관련 내용을 내재화하는 방향으로 개선하고자 한다. 이를 통해 긴급 상황에서도 신속하고 효율적으로 정보를 제공할 수 있는 안정성을 확보할 수 있다.
