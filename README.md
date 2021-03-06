
## 실행 방법

### React 실행 방법
1.  https://nodejs.org/en/  노드js 설치  

3. 클라이언트 폴더에 들어간 후 명령어창 혹은 cmd 창을
 	 실행합니다.   

4..  cmd에서 - npm install 입력 완료 후 npm - start 입력합니다.  
5. (자동으로 창이 안켜지는 경우 인터넷 창에 http://localhost:3000 로 접속해줍니다.  

### Node 실행 방법  
1  서버 폴더에 들어간 후 명령어창 혹은 cmd 창을 실행합니다.   
2.  cmd에서 npm install 입력 완료 후 npm start 혹은 node server.js 를 입력합니다.  
3. (자동으로 창이 안켜지는 경우 인터넷창에 http://localhost:3000 로 접속해줍니다.  
	

### Frontend : React 	
		Vue, Angular 등을 사용하는 것도 좋지만 주로 사용하는 스택이면서 그리고 평소 독학을 하면서 나름 익숙하다고 생각하는 React를 사용하는 게 더욱 도움일 될 거라 생각해서 Front 부분으로는 React를 사용하였습니다. 
    
### Backend : Node.js  
		최근 프로젝트를 진행할 때 Node.js를 많이 사용했습니다. 그 이유로는 Javascript 기반인 것과 속도 부분에서 빠르게 개발할 수 있다는 장점이 있어서입니다. 그래서인지 기프팅팀의 과제를 진행할 때도 자연스럽게 NodeJs를 백 부분으로 사용하게 된 것 같습니다.  
그 외 툴 : Visual Studio Code , Atom , Github   

### 문제점

첫 번째는 nodejs에 접근 가능한 대상이 운영자뿐만 아니라 모든 곳에서 다 접속 가능한 것이 하나의 문제인 것 같습니다. 이 프로그램이 올라가게 된다면 대상 도메인을 제외한 나머지의 접근은 차단하여 접속에 안정성을 두고 싶습니다.
두 번째는 운송장 번호에 대한 테스트가 많이 부족했던 것이 다음 문제인 것 같습니다. 많은 데이터로 실험해보고 싶었지만 가지고 있는 데이터가 송장 번호 두 개밖에 없어서 혹시 모를 문제가 생길 것 같습니다. 만약 이걸 실제 서비스로 올리게 된다면 여러 데이터로 더 실험해보고 보완해보고 싶습니다. 

### 개선점 및 추가 기능 계획
 
첫 번째는 택배회사 정보가 아닌 그냥 송장번호만으로도 조회가 가능한 시스템을 추가하고 싶습니다. (어떤 식으로 동작시킬지는 더 고민이 필요할 것 같습니다) 현재 구조로는 택배 회사를 선택 후 송장 번호를 입력해야 하는데 송장번호만으로 조회가 가능하다면 속도나 효율 면에서 더욱 빠르게 조회할 수 있으며 편리할 것 같습니다. 
두 번째는 데이터에서 원하는 데이터를 뽑아 올 수 있는 커스텀 테이블을 제작하고 싶습니다. 현재는 정해진 내용만 가지고 올 수 있게 기능이 동작 된다면 차후에는 운영자가 원하는 정보를 선택해서 데이터를 불러오는 것이 가능하게 만들고 싶습니다. 

