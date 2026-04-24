크로스플랫폼 배포용 패키지 안내

이 폴더는 GitHub Pages 같은 정적 호스팅에 바로 올릴 수 있도록 정리한 버전입니다.

구성
- index.html : 메인 파일
- assets/ : HTML 안에 들어 있던 모든 base64 이미지/GIF를 분리한 폴더
- .nojekyll : GitHub Pages용 설정 파일

권장 사용법
1. 이 폴더 안의 파일을 그대로 GitHub 저장소에 업로드합니다.
2. Settings > Pages 에서 main / (root) 로 배포를 켭니다.
3. 생성된 URL을 iPad Safari, iPad Chrome, Android Chrome에서 엽니다.

중요
- Apple 기기에서는 HTML 파일을 로컬로 직접 여는 것보다 URL로 여는 방식이 훨씬 안정적입니다.
- 반드시 index.html 과 assets 폴더를 함께 올려야 합니다.
- 파일명을 바꾸지 않는 것이 가장 안전합니다.

수정 시 주의
- index.html 안의 assets/ 경로를 임의로 바꾸면 이미지가 안 보일 수 있습니다.
- 새 버전으로 교체할 때는 같은 저장소, 같은 index.html 경로를 유지하면 기존 GitHub Pages 주소를 그대로 쓸 수 있습니다.
