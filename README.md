# 문자열 덧셈 계산기
## 소개
덧셈 연산기 만들기
- 덧셈 할 숫자들을 한 문자열로 입력
- 연산 할 각 숫자들을 `:` 이나 `/` 구분자로 구분
- 구분자를 커스터마이징 할 수 있다 
  - 커스텀 구분자는 앞에 `//`와 `\n` 사이에 입력 한다 
## 기능 목록
0. 프로그램 실행 시 사용자가 연산 할 숫자들을 입력 할 수 있다
1. 쉼표(,) 또는 콜론(:)로 연산 할 숫자들을 분리한다
2. 분리한 숫자들의 합을 구한다
3. 사용자가 커스텀 구분자를 지정 할 수 있게
   1. `//`와 `/n` 사이에 넣은 문자열을 인식하고
   2. 커스텀 구분자는 문자열 앞에만 지정 할 수 있게 한다
   3. 커스텀 구분자를 사용 시 숫자들이 분리 되는지 확인
   4. 컴스텀 구분자를 사용 시 연산이 되는지 확인
4. 사용자에게 보여 줄 오류 메세지 구성
   1. 사용자가 잘 못 된 값을 입력 하는 경우, 프로그램에 오류가 나게 만든다
   2. 오류 메세지 앞에 `[ERROR]` 문구가 뜨게 한다
   3. 오류 메세지가 뜨고 난 후 프로그램을 종료한다 
## 기타 주의 사항
- 연산 할 숫자들은 양수만 가능
- 잘 못 입력하면 오류 메세지와 함께 프로그램이 종료된다
