임진왜란 디지털 학습자료 - GitHub Pages 배포용 패키지

구성
- index.html
- assets/ (이미지 및 GIF 파일)
- .nojekyll

중요
- ZIP 파일 자체를 올리지 말고, 압축을 푼 뒤 이 폴더 안의 파일들을 그대로 GitHub 저장소 최상단에 업로드하세요.
- index.html 과 assets 폴더가 같은 위치에 있어야 합니다.
- 기존 GitHub Pages 주소를 유지하고 싶다면, 기존 저장소의 같은 위치에 이 파일들로 덮어쓰면 됩니다.

권장 Pages 설정
- Branch: main
- Folder: /(root)

이번 배포용 버전에서 한 일
- HTML 내부 base64 이미지/GIF를 assets 폴더로 분리
- 모바일 메타 태그 추가
- iPad/Safari/Android 대응을 위한 터치 보정 추가
- 우측 '사용 방법' / '침입 경로' 패널의 sticky 동작 유지 보강
- 태블릿 폭에서도 우측 패널이 우측에 유지되도록 반응형 기준 조정

문제가 생기면 확인할 것
1) index.html 이 저장소 최상단에 있는지
2) assets 폴더가 함께 올라갔는지
3) GitHub Pages 설정이 main / (root) 인지
4) 브라우저에서 강력 새로고침했는지
