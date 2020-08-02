# 파워 에디팅

* 텍스트가 프로그래밍의 기본적인 원재료
* 텍스트를 별로 힘들이지 않고 조작하고 싶음
* 텍스트 에디팅을 강력하게 잘하는 것이 필요함


## 하나의 에디터

* 하나의 에디터에 대해 매우 잘 알고, 코드, 문서화, 메모, 시스템 관리 등 모든 편집 작업에 그것을 사용하는 것이 좋다고 생각함
* 단일 에디터가 없다면 바벨탑의 혼란을 오늘날 다시 접하게 될 것임
* 서로 다른 편집 명령을 사용해야 한다면 이 중 어느 환경에도 능숙해지기가 어렵움 (언제는 IDE 봐꿔가면서 써보라매...)
* 한 에디터에 능숙해질 필요가 있음
* 필요한 키입력을 반사운동 수준이 되어야 함

## 에디터의 기능

* 설정변경 가능
  * 폰트, 색깔, 윈도우 크기, 키입력 바인딩 등을 여러분의 기호에 맞게 다시 설정할 수 있음
  * 키입력이 마우스보다 빠르다, 키보드에서 손이 떨이지지 않기 때문에

* 확장 가능
  * 단지 새로운 프로그래밍 언어가 나왔다 하더라도 에디터가 쓸모없는 구식이 되어선 안됨
  (새로운 JVM 언어가 나오면, IntelliJ에서 지원되는 것임? 혹은 Plugin으로 열심히 잘 지원하도록 만들어 볼 순 있지만 ROI가 나올지...)

* 프로그램 가능
  * 복잡하고 다단계의 작업을 수행할 수 있도록 에디터를 프로그램할 수 있어야함
  * 매크로를 통해 가능함

* 다른 기능
  * 구문 강조
  * 자동 완성
  * 자동 들여쓰기
  * 코드나 문서 상용어구 지원
  * 관련 도움말 시스템 (JavaDoc?)
  * IDE 기능 (컴파일, 디버그 등)

구문 강조는 생산성을 높여주는데 큰 영향을 준다.

## 생산성

* 윈도우 메모장을 소스코드 편집기로 사용하는 사람이 있다. 삽대신 티스푼을 사용하는 것돠 별반 차이가 없다.
* 기본 데이터로 불가능한 것들
  * 커서 이동 - 단어 단위, 줄 단위를 한번에 하기가 힘들다
  * 특정 줄들을 소팅하는 것
    * Before
    ```
    import java.util.Vector;
    import java.util.Stack;
    import java.net.URL;
    import java.awt.*;
    ```

    * `vi: :.,+3!sort`
    * 그냥 visual mode에서 block 설정한다음 `:sort` 해도됨

    * After
    ```
    import java.awt.*;
    import java.net.URL;
    import java.util.Stack;
    import java.util.Vector;
    ```

    * 새로운 파일을 생성하는 경우, 에디터가 자동으로 템플릿을 제공할 수 있음
    * 자동 들여쓰기

## 여기에서 어디로 가나

* 나는 여러 개의 에디터에서 기본적인 기능만 사용한다.
  * 강력한 에디터 하나를 골라서 그걸 제대로 익혀라.
* 선호하는 에디터가 있긴 한데, 그 기능을 모두 사용하진 않는다.
  * 그걸 배워라. 입력해야 하는 키 개수를 줄여라.
* 선호하는 에디터가 있고 가능하다면 그걸 사용한다.
  * 이미 하는 작업 외에 좀 더 많은 작업에 사용하도록 확장해 보라.
* 나는 여러분들이 바보라고 생각한다. 윈도우 메모장은 이제까지 만들어진 에디터 가운데 최고다.
  * 여러분이 그 에디터를 사용하면 행복하고, 또 생상적이라면 그걸 사용해라. 
  하지만 스스로가 '에디터 선망'에 걸릴 수 있다는 생각이 들면 스스로의 위치를 재평가할 필요가 있을 것이다.

## 어떤 에디터가 있나?

* 에디터의 선택은 개인적임 