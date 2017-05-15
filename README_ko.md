CommandBridge
======
CommandBridge는 Command-line Interface를 통해 Local 환경에서 이기종 언어로 된 Application간 통신을 별도의 확장 모듈없이도 범용적이고, 안정적으로 할 수 있게 해주는 소프트웨어 아키텍처이다.

![Alt CommandBridge architecutre](images/commandbridge_architecture.png?raw=true "CommandBridge architecutre")

모든 프로그램 언어들이 장단점이 있기 때문에 하나의 언어로만 개발하기에는 효율성이 떨어질 때가 있다. 특정 기능에 특화되거나 잘 구현할 수 있는 언어와 연동하는 이유이다. 그러나, 실제로 연동을 하다보면 불편한 점이 많이 있다. 연동을 위해 확장 모듈을 설치해야 하는데 이 확장모듈이 프로그램 언어의 버전을 타는 경우도 있고, 설치가 생각보다 까다로운 경우도 있다. 사용법도 언어마다 확장모듈마다 제각각이라서 학습도 필요하다. 그러나, CommandBridge는 별도의 확장 모듈없이 Command-line Interface를 통하므로, 호출한 언어와 요청받을 언어간의 Coupling이 없고, 연동 방식이 범용적으로 공통된 방식을 제공한다.

### 사용 가이드
CommandBridge의 자세한 사용법은 아래의 CommandBridge 공식 사이트를 참조하기 바란다.

[http://commandbridge.org](http://commandbridge.org/)

### 지원 언어
현재, Java, jjs, Node.js, PHP, Python, R, Ruby 언어를 지원하는 모듈을 제공하고 있다.

### 기부 Donate
CommandBridge는 무료 소프트웨어 아키텍처이다! 만약 CommandBridge를 사용하면서 유용하다고 생각했다면, 자발적인 기부를 부탁드린다. 금액에 상관없이 참여한 기부금에 대해 보다 나은 소프트웨어 개발로 보답하겠다. 아울러 우리 나라에서도 공개 소프트웨어가 활성화되고, 기부문화도 활성화되는 계기가 되었으면 한다.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=U9DP9TFDL5VDC)

### 다른 언어로 읽기
[영어 (English)](https://github.com/gurumdari/commandbridge/blob/master/README.md)