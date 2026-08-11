# 프로젝트 이름
- AI Health
- 100세 건강 생활 정보 가이드라인 내비게이션

## 주요 기능 및 취지
- 기능: 노후 시니어 건강 공공데이터 시각화 대시 보드 개발 과정 공유 및 토론
- 대상: Senior Health Dashboard based on AI data 
- 취지: 정년퇴직후 60대 중반에 노후 건강이 걱정입니다. 마음은 청춘인데 몸은 청춘이 아닙니다. 저와 지인들을 위해 파이썬 딥러닝 코딩으로 믿을 수 있는 건강 생활 정보 가이드라인 내비게이션을 만듭니다. 정부에서 제공하는 공공데이터를 알기 쉽고 공감할 수 있는 시각화 대시보드를 개발합니다. 100세 건강 생활을 위해, 행복한 시니어 노후 생활을 위해, 초고령사회 걱정을 해소하기 위해 오늘도 갑니다.

## 환경 구성
- README.md : Streamlit public 목록 및 운영 방향
- Issues : 기술적인 고군분투 사항들
- Journal : 소회, 느낀점, 앞으로 방향
- Discussions : 무병장수 100세를 위한 AI 개발, 사업화, 파트너십 토론

## 공개 Streamlit lists
- https://share.streamlit.io/user/etritgkang

### AI 딥러닝 모델
- https://health-labs.streamlit.app/

### AI 데이터 시각화 : 시군구 분포
- 고혈압 https://health-go02.streamlit.app/
- 당뇨병 https://health-dang02.streamlit.app/
- 이상지질혈증(콜레스테롤) https://health-chol02.streamlit.app/
- 치매 https://health-chi02.streamlit.app/
- 안전손상질환(산업재해) https://health-ann02.streamlit.app/
- 근골격계 https://health-geun02.streamlit.app/

### AI 데이터 시각화 : 연령별 년도별
- 고혈압 https://health-go02.streamlit.app/

### AI 데이터 시각화 : 진행중
- chatbot
- RAG, Retrieval-Augmented Generation, 검색 증강 생성
- AI Agent
- 무병장수 100세 노인 시니어 건강 예측 모델

### 특징
- 데이터출처: https://www.data.go.kr/
- 데이터제공기관: 국민건강보험공단
- 대시보드 제작자: (주)라이팅랩스 https://sites.google.com/view/lightinglabs

#### 데모 전 체크리스트
- 데모 10분 전 해당 주소에 미리 접속하여 앱 깨우기
- 스마트폰 '홈 화면에 추가' 기능으로 바로가기 아이콘 생성

#### 설치 및 실행 방법
1. 가상환경 활성화 : .venv/bin/activate
2. 패키지 설치 : pip install -r requirements.txt
3. 앱 실행 : streamlit run main_web.py

#### 디렉토리 구조

project-root
├── 📂 src/
│   ├── data_loader.py    # API 데이터 수집 및 전처리 파이프라인
│   └── utils.py          # 공통 유틸리티 함수
├── .streamlit/
│   └── secrets.toml      # API Key 보안 관리 (Gitignore 처리)
├── main.py               # Streamlit 메인 UI 및 대시보드 로직
├── requirements.txt      # 패키지 의존성 관리
└── asset/                # (주)라이팅랩스 logo_2  

## 행복한 오늘
무병장수 100세 노인 시니어 건강을 위해 AI 데이터 코딩하는 이순간 행복합니다.