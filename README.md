# Jun Choi 개인 사이트 (Quarto)

## 파일 구성
- `_quarto.yml` : 사이트 제목, 메뉴, 테마 설정
- `index.qmd` : 첫 화면 (소개, 학력, 연락처)
- `research.qmd` : 연구
- `cv.qmd` : CV
- `teaching.qmd` : 강의 경력
- `files/` : 사진, CV PDF, 논문 PDF를 넣는 폴더
- `docs/` : 변환된 실제 웹사이트 (직접 수정하지 않음)

## 내 컴퓨터에서 미리 보기
1. https://quarto.org 에서 Quarto 설치
2. 터미널에서 이 폴더로 이동 후 `quarto preview` 실행

## GitHub Pages에 올리기
1. GitHub에 가입하고 `아이디.github.io` 이름으로 공개(Public) 저장소 생성
2. 이 폴더 전체를 저장소에 업로드 (`docs` 폴더와 `.nojekyll` 파일 포함)
3. 저장소 Settings → Pages → Source를 "Deploy from a branch", Branch를 `main`, 폴더를 `/docs`로 선택 후 Save
4. 1~2분 뒤 `https://아이디.github.io` 로 접속

## 내용 수정할 때
1. `.qmd` 파일 수정
2. `quarto render` 실행 (docs 폴더가 갱신됨)
3. 변경된 파일을 GitHub에 다시 업로드
