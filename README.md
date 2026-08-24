# KOBACO 공공광고 업무지원 · 데이터 탐색

Streamlit 없이 GitHub Pages에서 실행하는 정적 웹 버전입니다.

## 구성
- `index.html`: 업무지원 + DuckDB 데이터 탐색
- `raw_data/parquet_db/`: KOBACO Parquet 34종
- `.nojekyll`: GitHub Pages 정적 배포용

## GitHub Pages
저장소 루트에 이 폴더 안의 파일을 그대로 업로드한 뒤:
Settings → Pages → Deploy from a branch → main / root

주의: `index.html`을 파일 탐색기에서 직접 더블클릭(`file://`)하지 말고 GitHub Pages 또는 HTTP 서버에서 실행하세요.
