크로스플랫폼 배포용 패키지 안내

이 폴더는 iPad/iPhone/Android에서 더 안정적으로 보이도록, 원본 HTML의 큰 base64 이미지를 분리한 웹 배포용 버전입니다.

구성
- index.html : 메인 파일
- assets/page-main.jpg : 교과서 페이지 이미지
- assets/dongnae-detail.jpg : 동래부 순절도 확대 이미지

중요
- Apple 기기에서는 HTML 파일을 "로컬 파일"로 직접 열면 제대로 실행되지 않을 수 있습니다.
- 가장 안정적인 방법은 이 폴더 전체를 웹 서버, LMS, 학교 홈페이지, GitHub Pages, Netlify 같은 정적 호스팅에 올린 뒤 URL로 여는 것입니다.

사용 방법
1. 이 폴더 전체를 그대로 업로드합니다.
2. index.html 이 웹에서 열리도록 배포합니다.
3. 학생들은 Safari/Chrome에서 URL로 접속합니다.

다른 페이지로 바꾸는 법
- 메인 페이지 이미지를 assets/page-main.jpg 로 교체
- 확대 이미지를 assets/dongnae-detail.jpg 로 교체
- index.html 안의 텍스트/좌표 데이터 수정

오프라인이 꼭 필요하면
- 로컬 파일 열기보다, 학교 앱/웹뷰 앱/간단한 로컬 서버 앱을 사용하는 편이 더 안정적입니다.
