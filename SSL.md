- Secure Socket Layer의 약자로, SSL 프로토콜은 웹 서버와 브라우저 사이의 보안을 위해 만들어졌다.
- 대칭키를 이용하여 암호화 통신을 한다는 특징이 있다.
- HTTP에 SSL 적용을 하여 Https 통신을 하게 되는데, 이러한 암호화 통신을 하기 위해서는 SSL 인증서가 필요하다.
- SSL 인증서는 해당 웹 사이트가 신뢰할 수 있는 사이트인지, 안전한 통신을 하는 사이트인지를 구분하기 위해, 누군가가 이 사이트를 신뢰할 수 있는 사이트라고 인증할 수 있도록 하기 위한 인증서이다.
- 인증서에는 인증서 소유자의 이메일, 소유자 이름, 인증서 용도, 인증서 유효기간, 발행기관, 공개키 등이 포함되어 있다.
- 인증서에 서명한 사람을 신뢰한다면, 서명된 인증서 또한 신뢰할 수 있다.
- 또한, 인증서가 다른 인증서에 서명을 해주는 트리 구조로 되어 있다.
- 구글 크롬, 파이어폭스 등에서 이미 https가 적용되지 않은 사이트는 안전하지 않은 사이트로 경고를 보여주고 실제로 많은 사이트들에 https가 적용되어 있다.