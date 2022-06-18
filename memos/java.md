바이트디그리 듣다가 헷갈리거나 기억 안 나는 부분들 메모

###### utf

UTF-8: 1바이트에서 4바이트까지 다양하게 문자를 표현할 수 있음

UTF-16: 2바이트로 문자를 표현



###### type inference

java 10 부터 지원하는 기능

local variable에 대해 자료형 선언 없이 사용할 수 있음

단 추론 된 변수는 다른 타입 대입 불가

```java
public class LocalVariableType {
	public static void main(String[] args) {
		var i = 10;
		var s = "ten";
		
		// this occurs error
		s = 10;
	}
}
```



###### Literal

  상수, boolean 값 등을 말함

  메모리에 로드 될 때 미리 할당되고 프로그램 exit시에 반환

  미리 할당 되는 부분을 data area / constant pool 등으로 부름

cf) static 변수도 미리 할당됨