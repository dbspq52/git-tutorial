# 교통 사고 시각화 및 분석 시스템

## 설치 방법

1. **Python 가상 환경 설정**:
    - **Mac/Linux**:
      ```bash
      python -m venv venv
      source venv/bin/activate
      ```
    - **Windows**:
      ```bash
      python -m venv venv
      venv\Scripts\activate
      ```

2. **의존성 설치**:
    ```bash
    pip install -r requirements.txt
    ```

---

## 프로젝트 구조
```plaintext
.
├── data/                   # 원본 및 전처리된 데이터 파일
│   ├── metr-la.h5          # LA 교통 속도 원본 데이터
│   ├── collision.csv       # 교통 사고 데이터
│   ├── Filtering.ipynb     # 데이터 매핑 및 필터링 노트북
│   ├── Collision_preprocessing.ipynb  # 사고 데이터 전처리 노트북
├── templates/              # 시각화를 위한 HTML 템플릿
├── static/                 # CSS, JS 등 정적 파일
├── app.py                  # API 서버
├── requirements.txt        # 의존성 패키지 리스트
└── README.md               # 프로젝트 설명 파일
