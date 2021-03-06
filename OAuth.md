- OAuth는 Open Authorization, Open Authentication을 뜻하는 것으로, 애플리케이션(페이스북,구글,트위터)의 유저의 비밀번호를 타 앱에 제공없이 인증, 인가를 할 수 있는 오픈 스탠다드 프로토콜이다. 
- OAuth 인증을 통해 애플리케이션 API를 유저 대신에 접근할 수 있는 권한을 얻을 수 있다.
- OAuth가 사용되기 전에는 외부 사이트와 인증 기반의 데이터를 연동할 때 인증방식의 표준이 없었기 때문에, 기존의 기본인증인 아이디와 비밀번호를 사용하였다.
- 이는 유저의 비밀번호가 노출될 가망성이 크기 때문에 보안상 취약한 구조였다. 
- 이를 보안하기 위해 OAuth의 인증은 API를 제공하는 서버에서 진행하고, 유저가 인증되었다는 Access Token을 발급한다. 
- 발급된 Access token으로 타 애플리케이션에서는 API를 안전하고 쉽게 사용할 수 있다.
