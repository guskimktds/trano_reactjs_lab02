# trano_reactjs_lab01

Lab 01 : 전화번호부 (이름, 전화번호) 

	1. 구현목적 : React 기본 CRUD 구현, npm 을 통한 라이브러리 설정, git을 통한 소스 관리
	
	2. 요구사항 :
		1. 이름 검색,
		2. 목록 선택 시 상세정보(이름, 전화번호)표시,  
		3. 등록, 수정
		4. 삭제
		
	3. 개발환경 : React.js, jshint, atom, webpack, webpack-dev-server 등 구성
		1. 웹서버(static) 설치 : sudo npm install -g webpack webpack-dev-server webpack-cli
		2. 노드 프로젝트 생성 : npm init
		3. Dependency & Plugin 설치 : npm install --save react react-dom 
			i. --save 키워드는 package.json 에 기록해줌
			예시) 
			"dependencies": {
			    "react": "^16.8.1",
			    "react-dom": "^16.8.1"
			  }
			
		4. 개발 의존모듈(dev Dependency) 설치 : 
			i. npm install --save-dev babel-core babel-loader babel-preset-es2015 babel-preset-react
			ii. npm install --save-dev react-hot-loader webpack webpack-dev-server
		5. 웹팩 설정
      webpack.config.js 참고
  
  
  git clone https://github.com/guskimktds/trano_reactjs_lab01.git 
  프로젝트를 로컬에 clone 하고 npm run dev-server 를 실행한 후
  웹브라우저를 띠우고 주소창에 localhost:4000 으로 접속하면 'Hello' 가 표시 되면 정상적인 react 개발환경이 생성된 겁니다.
  
  
