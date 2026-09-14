# 🛡️ SafeWayHome (프로젝트 이름)

## 📝 프로젝트 소개
- 본 프로젝트는 [어떤 문제]를 해결하기 위해 [어떤 방식/기술]을 활용하여 안전한 귀갓길을 안내하는 서비스입니다.

## 📂 폴더 구조 및 규칙
- `data/raw/`: 원본 데이터 (형식: `데이터명_raw.csv`)
- `data/processed/`: 전처리 완료된 데이터
- `notebooks/`: 데이터 분석 및 실험용 주피터 노트북
- `src/`: 실제 서비스 구동에 필요한 파이썬 소스 코드

## 📊 데이터 출처
- CCTV 위치 데이터: [공공데이터포털 링크]
- 보안등 위치 데이터: [공공데이터포털 링크]

## 🚀 실행 방법
1. 저장소 클론: `git clone https://github.com/leeeojin2005/safewayhome.git`
2. 가상환경 활성화: `.\venv\Scripts\activate` (Windows 기준)
3. 필수 라이브러리 설치: `pip install -r requirements.txt`
4. 실행: `streamlit run src/app.py` (예시)