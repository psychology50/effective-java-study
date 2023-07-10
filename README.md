[^1]: 링크 다는 법 -> [표시할 내용](링크)

# effective-java-study
> ### 한 문장이라도 모르는 것을 대충 넘어가지 말자.  

**기간**  
한 주 1장 씩 (3월 시작, 시험 기간 제외 12주)  

**발표 방식**  
스터디 당일 사다리 타기로 발표 파트 분배  
발표 시작 전에 발표자가 이슈를 연다.  

**Gitgub Issue**  
issue를 활용하여 질의응답. 질문 내용은 파트 담당자가 답변을 달아둔다.  
  - 처음 보는 용어에 대한 설명 요구
  - 글로만 적혀있는 기술에 대한 사용법 요규
  - 예제 코드에 대한 설명
  - 문단 문맥 이해
  - 코드에 대한 분석 요구 (주로 JDK  구현 방식에 대한 상세 설명)
  - 관련 기술 사용 예제 요구

## 2장. 객체 생성과 파괴  
|아이템|발표자|
|:---|:---:|
|1. 생성자 대신 정적 팩터리 메서드를 고려하라 | [안형준](https://com-squadleader.tistory.com/195) |  
|2. 생성자에 매개변수가 많다면 빌더를 고려하라 | [조예림](https://joyerim.tistory.com/44) |
|3. private 생성자나 열거 타입으로 싱글턴임을 보증하라 | [양재서](https://jaeseo0519.tistory.com/146) |
|4. 인스턴스화를 막으려거든 private 생성자를 사용하라 | [안형준](https://com-squadleader.tistory.com/195) |
|5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라 | [조예림](https://joyerim.tistory.com/45) |
|6. 불필요한 객체 생성을 피하라| [양재서](https://jaeseo0519.tistory.com/149) |
|7. 다 쓴 객체 참조를 해제하라| [조예림](https://joyerim.tistory.com/46) |
|8. finalizer와 cleaner 사용을 피하라| [양재서](https://jaeseo0519.tistory.com/151) |
|9. try-finally보다는 try-with-resources를 사용하라| [안형준](https://com-squadleader.tistory.com/199) |

## 3장. 모든 객체의 공통 메서드  
|아이템|발표자|
|:---|:---:|
|10. equals는 일반 규약을 지켜 재정의하라 | [양재서](https://jaeseo0519.tistory.com/153) |
|11. equals를 재정의하려거든 hashCode도 재정의하라 | [안형준](https://com-squadleader.tistory.com/201) |
|12. toString을 항상 재정의하라 | [조예림](https://joyerim.tistory.com/51) |
|13. clone 재정의는 주의해서 진행하라 | [양재서](https://jaeseo0519.tistory.com/158) |
|14. Comparable을 구현할지 고려하라 | [안형준](https://com-squadleader.tistory.com/219) |

## 4장. 클래스와 인터페이스  

|아이템|발표자|
|:---|:---:|
|15. 클래스와 멤버의 접근 권한을 최소화하라 | [조예림](https://joyerim.tistory.com/55) |
|16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라 | [조예림](https://joyerim.tistory.com/56) |
|17. 변경 가능성을 최소화하라 | [양재서](https://jaeseo0519.tistory.com/162) |
|18. 상속보다는 컴포지션을 사용하라 | [안형준](https://com-squadleader.tistory.com/223) |
|19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라 | [양재서](https://jaeseo0519.tistory.com/171) |
|20. 추상 클래스보다는 인터페이스를 우선하라 | [양재서](https://jaeseo0519.tistory.com/172) |
|21. 인터페이스는 구현하는 쪽을 생각해 설계하라 | [양재서](https://jaeseo0519.tistory.com/173) |
|22. 인터페이스는 타입을 정의하는 용도로만 사용하라 | [양재서](https://jaeseo0519.tistory.com/174) |
|23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라 | [양재서](https://jaeseo0519.tistory.com/175) |
|24. 멤버 클래스는 되도록 static으로 만들라 | [양재서](https://jaeseo0519.tistory.com/176) |
|25. 톱레벨 클래스는 한 파일에 하나만 담으라 | [조예림](https://joyerim.tistory.com/65) |

## 5장. 제네릭  

|아이템|발표자|
|:---|:---:|
|26. 로 타입은 사용하지 말라 | [안형준](https://com-squadleader.tistory.com/235) |
|27. 비검사 경고를 제거하라 | [양재서](https://jaeseo0519.tistory.com/179) |
|28. 배열보다는 리스트를 사용하라 | [조예림](https://joyerim.tistory.com/68) |
|29. 이왕이면 제네릭 타입으로 만들라 | [안형준](https://com-squadleader.tistory.com/238) |
|30. 이왕이면 제네릭 메서드로 만들라 | [양재서](https://jaeseo0519.tistory.com/182) |
|31. 한정적 와일드카드를 사용해 API 유연성을 높이라 | [안형준](https://com-squadleader.tistory.com/240) |
|32. 제네릭과 가변인수를 함께 쓸 때는 신중하라 | [조예림](https://joyerim.tistory.com/72) |
|33. 타입 안전 이종 컨테이너를 고려하라 | [양재서](https://jaeseo0519.tistory.com/185) |

## 6장. 열거 타입과 애너테이션

|아이템|발표자|
|:---|:---:|
|34. int 상수 대신 열거 타입을 사용하라|[조예림](https://joyerim.tistory.com/74)|
|35. ordinal 메서드 대신 인스턴스 필드를 사용하라|[양재서](https://jaeseo0519.tistory.com/187)|
|36. 비트 필드 대신 EnumSet을 사용하라|[안형준](https://com-squadleader.tistory.com/245)|
|37. ordinal 인덱싱 대신 EnumMap을 사용하라|[조예림](https://joyerim.tistory.com/77)|
|38. 확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라|[양재서](https://jaeseo0519.tistory.com/198?category=1131919)|
|39. 명명 패턴보다 애너테이션을 사용하라|[안형준](https://com-squadleader.tistory.com/254)|
|40. @Override 애너테이션을 일관되게 사용하라|[조예림](https://joyerim.tistory.com/80)|
|41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라|[안형준](https://joyerim.tistory.com/81)|

## 7장. 람다와 스트림

|아이템|발표자|
|:---|:---:|
|42. 익명 클래스보다는 람다를 사용하라|[양재서](https://jaeseo0519.tistory.com/209)|
|43. 람다보다는 메서드 참조를 사용하라|[양재서](https://jaeseo0519.tistory.com/212)|
|44. 표준 함수형 인터페이스를 사용하라|[조예림]()https://joyerim.tistory.com/84|
|45. 스트림은 주의해서 사용하라|[안형준](https://com-squadleader.tistory.com/262)|
|46. 스트림에서는 부작용 없는 함수를 사용하라|[조예림](https://joyerim.tistory.com/86)|
|47. 반환 타입으로는 스트림보다 컬렉션이 낫다|[안형준](https://com-squadleader.tistory.com/264?category=1093428)|
|48. 스트립 병렬화는 주의해서 적용하라|[양재서](https://jaeseo0519.tistory.com/222?category=1131919)|

## 8장. 메서드  

|아이템|발표자|
|:---|:---:|
|49. 매개변수가 유효한지 검사하라| [-]() |
|50. 적시에 방어적 복사본을 만들라| [-]() |
|51. 메서드 시그니처를 신중히 설계하라| [-]() |
|52. 다중정의는 신중히 사용하라| [-]() |
|53. 가변인수는 신중히 사용하라| [-]() |
|54. null이 아닌, 빈 컬렉션이나 배열을 반환하라| [-]() |
|55. 옵셔널 반환은 신중히 하라| [-]() |
|56. 공개된 API 요소에는 항상 문서화 주석을 작성하라| [-]() |

## 9장. 일반적인 프로그래밍 원칙  

|아이템|발표자|
|:---|:---:|
|57. 지역변수의 범위를 최소화하라|[-]()|
|58. 전통적인 for문보다는 for-each문을 사용하라|[-]()|
|59. 라이브러리를 익히고 사용하라|[-]()|
|60. 정확한 답이 필요하다면 float와 double은 피하라|라|[-]()|

## 10장. 예외  

|아이템|발표자|
|:---|:---:|
|||

## 11장. 동시성  

|아이템|발표자|
|:---|:---:|
|||

## 12장. 직렬화  

|아이템|발표자|
|:---|:---:|
|||

## 참고 자료
