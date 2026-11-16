# Airflow KRUG 행사 스태프 업무 분장 & 안내 사이트

이 저장소는 **Airflow KRUG (Apache Airflow Korea User Group)** 밋업 및 행사 현장에서 스태프분들이 모바일 및 웹에서 손쉽게 업무 분장과 공지 사항을 확인할 수 있도록 제작된 정적 웹사이트(GitHub Pages)입니다.

---

## 📁 디렉토리 구조

```text
event-announce/
├── index.html          # 메인 페이지 (공통 공지 + 전체 스태프 배정표 + 검색 + 바로가기)
├── style.css           # 모바일 가독성 중심 스타일시트
├── roles/              # 파트별 상세 안내 가이드
│   ├── photo.html      # 📸 사진 보조 (강민석, 김혜진)
│   ├── reception.html  # 🎟️ 리셉션 보조 (김도율, 조우형)
│   ├── stage.html      # 🎤 발표자/사회 보조 (김광현, 정수진)
│   ├── floor.html      # 🚶 현장 보조 (김지훈, 정소미)
│   └── media.html      # 🎬 미디어 (신지호)
└── README.md
```

---

## 🚀 GitHub Pages 활성화 방법

1. GitHub 저장소(`AirflowKorea/event-announce`)로 이동합니다.
2. 상단 탭에서 **Settings** → 좌측 메뉴 **Pages**를 클릭합니다.
3. **Build and deployment** 항목의 **Source**를 `Deploy from a branch`로 설정합니다.
4. **Branch**를 `main` 브랜치 / `/ (root)` 폴더로 선택하고 **Save**를 누릅니다.
5. 1~2분 후 제공되는 GitHub Pages URL(예: `https://airflowkorea.github.io/event-announce/`)로 접속하실 수 있습니다.

---

## ✨ 주요 기능
- **모바일 최적화 UI:** 현장에서 스마트폰으로 이동하며 편하게 볼 수 있는 카드형 디자인
- **스태프 검색 기능:** 메인 화면에서 본인 이름 또는 업무 키워드로 즉시 필터링
- **원클릭 이동:** 담당자 배정표 및 상단 퀵 버튼에서 본인 파트 상세 가이드로 즉시 이동
- **파트별 체크리스트:** 사전 준비, 행사 진행 중, 행사 종료 후 할 일 단계별 정리
