## Learned
- 실시간 강의: JS 보충강의-Bundler
1. webpack으로 개발환경 설정
  - entry: 진입점 설정하기
  - ex) { main: './src/main.js' }
  - output: 결과물 설정하기
    - path: 결과 파일이 저장될 장소
    - filename: 결과 파일 이름
    - publicPath: html파일에 추가될 때 경로 앞에 붙여줄 내용
    - clean: 번들할 때마다 전에 했던거 청소하고 다시 할 수 있도록
  - module: loader 설정해주기
    - .js/.jsx파일 babel loader로 읽도록 설정
    - ex) { test: /\.jsx?$/, use: 'babel-loader', exclude: /node\_modules/
    - scss파일 읽을 수 있도록 style-loader, css-loader, scss-loader 설정
  - plugins: 정적 파일 갖고올 수 있는 플러그인들
    - html-webpack-plugin : 결과폴더에 html파일 복사해옴
    - copy-webpack-plugin : 정적 파일 복사해오기
  - devServer: 개발서버 설정(포트넘버 등)
  - resolve: 확장자 생략(extensions) 옵션, 경로 별칭(alias) 옵션 설정

## 다음 할 일
- 실시간: 
1. React 강의 잘 따라가기
