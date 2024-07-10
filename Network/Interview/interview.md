## Network Interview Questions

### OSI
- L3 switch와 router의 차이?
- 각 헤더의 packing order?
- ARP란?

### TCP/UDP
- ACK, SYN같은 정보를 전달하는 방법?
- 두 호스트가 동시에 연결을 시도한다면?
- SYN Flooding이란?
- 0-RTT 기법이란?
- 통신을 빨리 끊어야할 경우, 어떻게 해야하는지?
- 흐름제어/혼잡제어란?
- TCP/UDP가 오류를 정정하는 방법?
- HTTP/3.0에서 UDP를 사용하는 이유?

### DHCP
- DHCP에서 UDP를 사용하는 이유?

### DNS
- DNS Recursive Query, Iterative Query?
- 쿼리 과정에서 손실이 발생했을 때 처리 방법?
- 캐싱된 쿼리가 잘못되는 경우에 대한 보장 방법?
- 레코드 타입 중 A, CNAME, AAAA의 차이?
- hosts 파일의 역할?

### IP
- IPv4의 주소 고갈문제 해결 방법?
- 유동 IP와 고정 IP의 차이?
- IPv4를 사용하는 장비와 IPv6을 사용하는 장비가 같은 네트워크 내에서 통신이 가능한지?
- IPv4의 checksum과 TCP checksum의 차이?
- IP주소와 MAC주소의 차이?

### Router
- Routing과 Forwarding의 차이?

### Subnet Mask, Gateway
- NAT란?
- 서브넷 마스크의 표현 방식?

### HTTP/HTTPS
- TCP의 keep-alive와 HTTP의 keep-alive의 차이점?
- HTTPS handshake과정에서 인증서를 사용하는 이유?
- HTTPS에서 사용하는 암호화 기법?
- HTTP 버전별 차이점?
- HOL Blocking이란?
- POST, PATCH, PUT의 차이?
- 401과 403의 차이?
- 302와 301의 차이?
- 200과 201의 차이?
- GET에 body를 실을 수 있지만 지양하는 이유?

### TLS/SSL

### Load Balancing
- L4, L7 로드밸런서의 차이?
- 로드밸런싱 알고리즘?
- 로드밸런서로 장애를 대비하는 방식?
- 로드밸런서 장치를 사용하지 않고 DNS를 활용해서 유사하게 로드밸런싱을 하는 방법?

### Browser
- 브라우저가 동작하는 과정? (http://github.com을 주소창에 입력했을 때 화면에 보이는 과정)
- DNS 쿼리를 통해 얻어진 IP가 가리키는 것?
- URL, URI, URN의 차이?

### Cookie/Session/JWT
- 서버가 여러개일때 세션을 관리하는 방법?
- 쿠키와 세션은 HTTP의 stateless 특성을 위배하는 것은 아닌가? 대체방안이 있나?
- JWT의 암호화/복호화 과정?
- 토큰 인증 방식에서 Refresh Token, Access Token을 구분해서 사용하는 이유?
- 토큰을 사용했을 때의 장점? HTTP의 특성을 위배하는 것은 아닌지?

### REST API
- API와 REST API의 차이점?

### Web Server/WAS
- 구분해서 사용하는 이유?

### Socket
- 웹 소켓과 소켓 통신의 차이?
- 소켓과 포트의 차이?
- 여러 소켓이 있다면 그 소켓의 포트 번호는 모두 다른가?
- 사용자 요청이 무수히 많으면 소켓도 무수히 많이 생성되는가?

### OAuth
- OAuth로 인증하는 과정?

### Security
- SOP 정책?
- CORS 오류란?
- Preflight란?
- CSRF, XSS?
- 대응하기 위한 방법?

### Multiplexing/Demultiplexing
