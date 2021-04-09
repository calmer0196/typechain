# typechain

node.js는 타임스크립트를 이해하지 못하기 때문에 일반적인 자바스크립트 코드로 컴파일하는 작업이 필요하다.

먼저 github에 기본 셋팅을 한다.
yarn을 셋팅한다.
yarn init을 하고 package.json 파일을 생성한다.
yarn global add typescript를 쳐준다.
tsconfig.js / index.ts 파일 생성
tsc나 npx tsc를 콘솔에 쳐서 index.js / index.js.map 파일을 생성한다.
yarn start로 ts를 실행한다.
yarn add tsc-watch --dev를 실행하여 yarn lock / node_modules 파일을 생성한다.
yarn add crypto-js 설치