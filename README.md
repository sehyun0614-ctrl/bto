# BTO 공정·측정 진단 가상팹

실측 사례와 검증 절차를 연계한 졸-겔 BaTiO₃(BTO) 커패시터 공정·측정 진단 가상 실습 앱입니다.
국민대학교 UROP (지도교수 심인보)

## 구성
- 가상 공정 실습: 시편 선택 → 제작 → 검사·측정 → 원인 판단 → 조건 변경
- 측정 진단 과제: 원인을 숨긴 측정 이상 사례를 검사로 좁히고, 근거가 부족하면 판정 보류
- 실제 실험과 비교: 실제 레시피·측정 원데이터·Sentaurus TCAD 해석
- 연구 결과 요약: 확인한 사실 · 가정에 따른 해석 · 남은 검증 · 구조 선정
- 모든 수치에 출처 표기: 실측 / 문헌 / 가정 / 모델

## 실행
`index.html`을 PC의 Chrome 또는 Edge로 엽니다. 설치가 필요 없고 인터넷 없이도 동작합니다.
(메신저 미리보기·휴대폰 파일 뷰어에서는 스크립트가 실행되지 않습니다.)

## 배포 (Streamlit Community Cloud)
1. 저장소 루트에 `index.html`, `streamlit_app.py`, `requirements.txt`를 올립니다. 파일 이름은 반드시 `index.html`이어야 합니다.
2. https://share.streamlit.io → Create app → 저장소 선택 → Main file path `streamlit_app.py` → Deploy.
3. 이후 수정은 GitHub에서 `index.html`만 교체하면 자동 반영됩니다.

## 공개 범위
미발표 실험 자료가 포함되어 있습니다. 지도교수 확인 전까지 저장소는 Private, 앱은 초대한 사용자만 접근하도록 설정하십시오.
GitHub Pages(무료 계정)는 저장소가 Public이어야 하므로 사용하지 않습니다.
