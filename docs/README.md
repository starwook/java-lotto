#로또 게임

##기능 목록

### WinningNumber.java
- [ ] 문자열을 Integer<List>로 변경 후 사이즈가 6인지 확인하며 WinningNumber 클래스의 numbers로 설정하는 생성자 - WinningNumber(String string)
- [ ] Integer<List>의 사이즈가 6인지 확인하는 메소드 -validate(List<Integer> numbers)
- [ ] 사용자가 입력한 문자열을 Integer<List>로 돌려주는 메소드 - StringToIntegerList(String string)
   - [ ] ','가 나온다면 숫자가 0인지 확인하는 메소드 - checkIfNumberInRange(int i)
   - [ ] 숫자가 정해진 범위안에 있는 숫자인지 확인하는 메소드 -checkIfNumberInRange(int i)
   - [ ] 문자가 '0'~'9'사이인지 확인하는 메소드 -checkifCharIsNumber(char c)

- [ ] 중복되지 않는 6개의 숫자를 뽑아 Integer<List>를 만들어주는 메소드
- [ ] 로또 구입 금액이 1000원 단위로 나누어 떨어지는 확인하는 메소드
- [ ] 사용자의 로또 번호와 기존 로또 번호에서 몇개가 같은 지 돌려주는 메소드
- [ ] 전체적으로 입력을 받고 출력을 해주는 메소드
- [ ] 수익률을 계산해주는 메소드