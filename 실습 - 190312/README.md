# 190312

1. html은 줄바꿈을 무시한다 -> 각각의 항목들을 리스트로 표현하려면?

   ```html
   <li> </li>
   리스트로 표현하는 방법
   ```

   - 시각적으로 띄워두고 싶은데, 어떻게 해야 하는가? -> 그것이 태그의 중첩

   ```html
   <ul>
       <li> </li>
       <li> </li>
       <li> </li> ...
   </ul>
   
   <li></li> 태그만으로는 그룹핑을 할 수 없으니, <ul> </ul>로 그룹핑을 해준다.
   li : list
   ul : unordered list
   ```

   - 태그라는 것은 그 태그 안에 다른 태그가 존재할 수 있음. - 190312_1.html

   ```html
   <ol>
   	<li> </li>
   </ol>
   
   <ul> </ul> 밑에 있는 <li> </li> 들은 숫자가 붙지 않고,
   <ol> </ol> 밑에 있는 <li> </li> 들은 숫자가 붙는다
   ol : ordered list, - 190312_2.html
   ```

2. DOCTYPE : DOCument TYPE
   - 자신이 작성한 html 코드가 어떤 방식의 html 코드로 작성되었는가? 를 선언하는 문자
   - 브라우저에게 이 html은 어떠한 표준을 따르고 있는 태그들이다. 를 알려주는 것

   ```html
   <!DOCTYPE html> - 190312_3부터 추가
   ```

3. [실전 with 생활코딩 - 1](https://opentutorials.org/course/2039/10938) - 190312_3 폴더