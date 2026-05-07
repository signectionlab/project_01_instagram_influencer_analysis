# Instagram Influencer Analysis 📊

아래 이미지를 클릭하시면 **인터랙티브 태블로 대시보드**를 직접 확인하실 수 있습니다.

[![인플루언서 분석 대시보드 미리보기](https://public.tableau.com/static/images/_2/_260506/_/1_rss.png)](https://public.tableau.com/views/_260506/_)

이 프로젝트는 인스타그램 최상위 인플루언서들의 데이터를 바탕으로 영향력을 분석하고 시각화하는 프로젝트입니다. 단순한 팔로워 수 외에 평균 좋아요 수, 참여율 등 다양한 지표를 바탕으로 인플루언서들의 실제 영향력을 파악하고자 하였습니다.

## 📂 프로젝트 구조

```
project_01_instagram_influencer_analysis/
├── README.md                                     # 프로젝트 개요 및 설명
├── notebooks/
│   └── instagram_influencer_preprocessing_eda.ipynb # 데이터 전처리 및 EDA
├── data/
│   └── processed/
│       └── insta_influencers_tableau_ready.csv   # 태블로 시각화를 위한 전처리 완료 데이터
├── dashboard/
│   └── tableau_public_link.md                    # 태블로 대시보드 링크
└── assets/
    └── dashboard_thumbnail.png                   # 대시보드 썸네일 이미지
```

## 🛠️ 사용 기술 및 도구

- **Data Analysis & Preprocessing:** Python, Pandas, Google Colab
- **Data Visualization:** Tableau Public

## 📈 데이터 소개

- `rank`: 순위
- `channel_info`: 인플루언서 계정 이름
- `influence_score`: 영향력 점수
- `followers`: 팔로워 수
- `avg_likes`: 평균 좋아요 수
- `60_day_eng_rate`: 최근 60일 참여율
- `country`: 국가

(데이터 출처: Kaggle 등 공개 데이터셋 활용)

## 📌 주요 분석 내용

1. **데이터 정제(Data Cleaning):**
   - 문자열로 된 숫자 데이터(예: 8.7m, 3.3k)를 숫자형으로 변환하는 등 전처리 수행
   - 결측치 처리 (예: country 값이 없는 경우 'None'으로 대체)

2. **EDA (탐색적 데이터 분석):**
   - 팔로워 수 대비 참여율 분석
   - 인플루언서들의 국가별 분포 파악

3. **태블로(Tableau) 시각화 연동:**
   - 전처리된 데이터를 기반으로 사용자 친화적인 대시보드 구성

## 🔗 대시보드 링크

위의 대시보드 미리보기 이미지를 클릭하시거나, 아래 링크를 통해 전체 대시보드를 확인해 보세요.
👉 [Tableau Public 대시보드 보기](https://public.tableau.com/views/_260506/_)
