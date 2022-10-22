#Instaclone

Instaclone Backend.

###########################
npm i apollo-server graphql

npm i nodemon --save-dev
# 1. nodemon ? 개발을 위한 옵저버 패키지
# 2. 만약 서버 파일에 뭔가 변화가 있다면 자동적으로 재실행 시켜준다.
# 3. nodemon 설치 후 package.json 에서 devDependencies에 nodemon 이 추가된 것을 확인
# 4. 여담으로 apollo-server관련된 사항들을 import 시키는 구문으로
# 5. const {ApolloServer, gql} = require("apollo-server");  <- 를 사용하는 것보다
# 6. import {ApolloServer, gql} from "apollo-server"; <- 를 사용하고 싶다면
# 7. package.json 에 type 을 module로 정의해 주어야 한다.(nodemon 은 ES모듈이 아니기 때문에 바꿔줘야 한다고 하는데, 사실 잘 모르겠다..)
# 8. 7번에 대한 구문으로 "type" : "module"  을 package.json에 추가
# 9. 그러나 7번 사항의 경우 babel을 설치하기 위해 해당 코드에서는 삭제처리

