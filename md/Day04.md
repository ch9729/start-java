- 배열
    - 같은 타입의 변수를 사용하기 편하게 하나로 묶어둔 것
    - 일반적인 변수와 차이점은 대괄호([])가 들어간다는 점이다.
    - 자바는 배열을 생성할 때 그 내부값을 자동으로 초기화한다.
        - 숫자는 0, boolean은 false, String은 null로 초기화 된다.
    - 배열은 생성하고 나면 메모리 어딘가에 있는 이 배열에 접근할 수 있는 참조값(주소)을 반환한다.
    - 배열의 위치를 나타내는 숫자를 index라 한다.
        - index는 0부터 시작한다. index 범위는 0 ~ (n-1)
    - {}만 사용해서 생성과 동시에 편리하게 초기화 하는 기능도 제공한다.
- 기본형 vs 참조형
    - 기본형: 사용하는 값을 직접 넣을 수 있다.
        - int, double, boolean처럼 변수에 사용할 값을 직접 넣을 수 있는 데이터 타입
    - 참조형: 배열 변수와 같이 메모리의 참조값을 넣을 수 있다.
        - 데이터에 접근하기 위한 참조(주소)를 저장하는 데이터 타입, 객체나 클래스를 담을수 있는 변수들도 참조형이다. 
