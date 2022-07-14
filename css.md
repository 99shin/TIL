# css 정리

- css는 html을 꾸며주는 것(html은 정보, css는 디자인)

  - html태그에서 디자인을 꾸며주는 것

- `<style>`태그 사용

  - 동급이면 뒤에 적어둔 코딩이 우선 적용
  - 예를들어 <style> h2{color:blue;} </style>
  - 타이포그라피, 색상, 박스모델
  - color 색깔 설정
  - text-decoration 밑줄 같은거 설정
  - font-size 크기 설정(rem 주로 사용, 사용자가 원하는 데로 크기를 변경 할 수 있게)
  - font-family 글꼴 변경
  - font-weight 두께 같은거 변경
  - line-height 줄 간격 변경
  - font: (이거를 쓸 때는 순서를 맞춰야됨, 순서는 필요할 때 확인 )
  - border
  - background-color
  - text-align
  - 참고 https://opentutorials.org/module/2367/13357

- id

  - id는 하나한테만 쓰는게 좋음
  - id="이름"하고 style 태그 안에 #이름{ 내용} 하면 반영 됨

- class(그룹핑)

  - class는 여러 대상들을 한번에 설정할 때 좋음
  - clsaa="이름"하고 style태그 안데 .이름{ 내용} 하면 반영 됨

- 상속

## 질문

- style은 꼭 head에만 해야되는가?