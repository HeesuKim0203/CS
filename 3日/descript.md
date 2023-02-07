# 팩토리 패턴

면접을 위한 CS 전공지식 노트에서..  

팩토리 패턴은 객체를 사용하는 코드에서 객체 생성 부분을 떼어내 추상화한 패턴이자 상속 관계에 있는 두 클래스에서 상위 클래스가 중요한 뼈대를 결정하고, 하위 클래스에서 객체 생성(constructor)에 대한 내용을 결정하는 패턴입니다.

상위 클래스와 하위 클래스가 분리 되기 때문에 느슨한 결합을 가지며 상위 클래스에서 인스턴스 생성 방식에 대해 전혀 알 필요가 없기 때문에 더 많은 유연성을 갖게 됩니다. 그리고 객체 생성 로직이 따로 떼어져 있기 때문에 코드를 리팩터링하더라도 한 곳만 고칠 수 있게 되니 유지 보수성이 증가됩니다.

라고 소개하고 있습니다.  

http-proxy, Restify 등에 많이 사용되어 지고 있습니다.

팩토리 패턴이란?

[https://readystory.tistory.com/117](https://readystory.tistory.com/117)

자바의 추상 클래스와 인터페이스의 차이

[https://wildeveloperetrain.tistory.com/112](https://wildeveloperetrain.tistory.com/112)