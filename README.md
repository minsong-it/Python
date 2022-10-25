# Python

<div align='center'>
  <strong>😍 Python </strong> <br><br>
    Python 내장함수 정리 및 알고리즘 이해 및 문제해결로 구성된 Repository입니다.<br>
    알고리즘 중 스택을 사용한 문제해결에 중점을 두고 있습니다. 
  
  <br><br>
  <strong>:computer: 실행환경</strong><br><br>
  ­IDE : <b>googleColab</b><br>
  ­Language : <b>Python</b> <br>
  <br><br>
  
  <strong> :one: 후위 수식 계산 </strong>
    <li> 스택을 활용하여 계산기 로직을 구현함
    <li> stack에 차례대로 int형 숫자를 push하여 연산자가 push될 경우,<br>stack에 남아있는 숫자를 pop 해서 계산하고. 이후 연산 결과를 출력함
    <br><p> <문제> <br>
    <img src='https://user-images.githubusercontent.com/113004260/197695696-fb7408e0-9ffd-47b3-a6ca-480110b465fb.png'><br>
    <p> <결과> <br>
    <img src='https://user-images.githubusercontent.com/113004260/197695670-95353d9a-8f13-42ad-acbb-12dd11f3da96.png'><br>
  <br>
  <br>
  <strong> :two: 미로탐색 (깊이 우선 탐색) </strong>
    <li> 스택을 활용해 시작점 e에서부터 출구 x까지 도달하는 알고리즘 작성
    <li> 0은 접근 가능한 루트, 1은 접근 불가능한 벽이라는 가정
    <li> 시작점부터 상하좌우를 탐색하여 0이 있는 list 좌표를 stack에 push
    <li> stack에 들어간 값은 *로 표시, 접근 가능한 루트를 연속으로 만났을 때 stack에서 해당 좌표를 pop 한 뒤 5로 표시함
    <li> 출구를 만날 경우, **로 출구를 표시하고 해당 좌표 값과 출구 값을 출력
      <br><p><문제><br>
      <img src='https://user-images.githubusercontent.com/113004260/197696113-a355ad77-5164-411d-9203-608e574a4ffa.png'><br>
      <br><p><결과><br>
      <img src='https://user-images.githubusercontent.com/113004260/197696257-0a822df0-14d5-441b-a9a3-2d9afeb5008d.png'>
</div>
