
## 복합 패턴 핵심정리

- 모델-뷰-컨트롤러(MVC)는 옵저버, 전략, 컴포지트 패턴으로 이루어진 복합 패턴이다.

- 모델은 옵저버 패턴을 사용해서 의존성을 없애면서도 옵저버들에게 자신의 상태가 변경되었음을 알릴 수 있다.

- 컨트롤러는 뷰의 전략 객체이다. 뷰는 컨트롤럴를 바꿔서 또 다른 행동을 할 수 있다.

- 뷰는 컴포지트 패턴을 사용해서 사용자 인터페이스를 구현한다. 보통 패널이나 프레임, 버튼과 같은 중첩된 구성 요소로 이루어진다.

- 모델, 뷰, 컨트롤러는 방금 말한 3가지 패턴으로 서로 느슨하게 결합되므로 깔끔하면서도 유연한 구현이 가능하다.

- 새로운 모델을 기존의 뷰와 컨트롤러에 연결해서 쓸 때는 어댑터 패턴을 활용하면 된다.

- MVC는 웹에도 적용된다.

- 클앙이언트-서버 애플리케이션 구조에 MVC를 적응시켜 주는 다양한 웹 MVC 프레임워크가 있다.


## 테스트
```
python chapter_12/main.py
```