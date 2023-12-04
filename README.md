# stock-alerts(주식 특정가,공시 알림)
## 개발하게된 이유 : 직장인 혹은 학생 등 투자를하는데 있어 실시간으로 주가를 확인하지못하는 상황에있는 사람을위해 원하는 목표가 혹은 원하는 매입가를 알림으로 사이트에서 한번 설정을 하게된다면 실시간으로 가격을 체크하여 사이트에 다시 로그인 하지 않더라도 설정해놓은 가격에 도달하였을때 알려주는 기능을 만들고자하였다

필요로 하는기능
1. 사용자 로그인
2. 주가를 가져올수있는 api연결(한국투자 증권에서 제공하는 open API사용)
3. 메인페이지 회사명/종목코드으로 검색하여 찾는 검색창
4. 검색한 회사를 관심종목에 추가할수있는 "관심종목"
5. 관심종목에서 특정가에 알림설정할수 있는 기능
6. 관심종목의 공시를 알림으로 받을수있는 기능(DART 에서 제공하는 open API사용)
7. 내가 설정한 특정가, 공시 알림목록을 관리 할수있는기능
8. 각종 UI를 설정할수 있는 기능

페이지 구성
1.로그인페이지
2.메인페이지
 회사명/종목코드로 검색할수있는 검색창->검색창에입력시 해당회사의 정보를 메인페이지에 띄운다->여기서 어떤정보를 띄울지 생각
 
 목차 구성 좌측 화면에  목차 관심종목,내가 설정한 특정가 알림목록, UI 및 세부 설정, 회원정보
3.세부 목차 페이지
관심종목 : 메인페이지에서 내가 설정한 관심종목을 모아놓음
내가 설정한 특정가,공시 알림목록 관리페이지
각종  UI설정 페이지
입한 회원정보 확인 페이지
