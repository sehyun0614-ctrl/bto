# BTO FAB Simulator

졸-겔 BaTiO₃ 강유전 커패시터 공정·측정 시뮬레이터.

- 공정: 기판 세척(아세톤·IPA·DI·SC-1) → 졸 합성·숙성 → UV 처리 → 후드 환경 → TiO₂ 버퍼 → 스핀코팅(ACE-200) → 예비 건조(홈매트)·면봉 하부전극 확보·하드베이크 → 퍼니스(Yokogawa UP351, 장입·인출) → Pt 상부전극
- 분석: 광학 현미경, XRD(Rigaku 측정 → HighScore 분석), SEM(ImageJ 측정)
- 측정: 프로브 스테이션, B1500A·4284A(EasyEXPERT 형식)
- 품질: 수율·SPC, 공정 조건 Split 비교, 고객 품질 리포트
- 포함 데이터: 11/17·11/19 전기 측정, XRD 원데이터, SEM 측정값, 현장 사진

국민대학교 UROP · 지도교수 심인보 · 박세현, 김지우, 병욱

## 배포 방법 1: GitHub Pages (가장 간단, 추천)

1. GitHub에서 새 저장소 만들기 (예: `bto-fab`). **무료 계정은 Public이어야 Pages가 됩니다.**
2. 이 폴더의 `index.html`, `.nojekyll`, `README.md`를 업로드하고 Commit.
3. 저장소 **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**, 폴더: **/(root)** → **Save**
4. 1~2분 뒤 `https://<아이디>.github.io/bto-fab/` 주소로 열립니다.

## 배포 방법 2: Streamlit Community Cloud (Private 저장소도 가능)

1. 이 폴더 전체(`index.html`, `streamlit_app.py`, `requirements.txt`)를 GitHub 저장소에 올립니다.
2. https://share.streamlit.io → **Create app** → 저장소 선택
   → Main file path: **`streamlit_app.py`** → **Deploy**.
3. `https://<이름>.streamlit.app` 주소가 생깁니다.

## 로컬에서 열기

`index.html`을 더블클릭하면 브라우저에서 바로 열립니다(설치 불필요).

## 값의 출처 표시

- 실측: 팀 측정값 (SEM 두께, XRD 결정립, 11/19 CSV, 패드 지름)
- 문헌: 논문 값 (레퍼런스 페이지)
- 가정: 문헌 범위에서 고른 값 → 실험노트 값으로 교체 필요 (졸 농도, rpm, 중탕 조건, 습도 기준, 유지시간)
- 모델: 위 값으로 계산한 결과

## 주의

앱 안에 연구실 미발표 측정 데이터가 들어 있습니다. 공개(Public) 배포 전에 지도교수님 확인을 받으세요.


## 주의

미발표 실험 데이터·현장 사진 포함. 지도교수 승인 전 Public 공개 지양 → Private 저장소 + Streamlit 배포 권장.
