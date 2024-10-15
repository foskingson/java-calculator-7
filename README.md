# 📑 java-calculator-precourse 문자열 덧셈 계산기 
> 입력받은 문자열에서 쉼표(,) 또는 콜론(:)을 구분자로 숫자를 추출하고, 각 숫자를 더하여 결과를 반환하는 계산기를 구현한다. 커스텀 구분자를 지원하며, 입력이 잘못된 경우 예외 처리를 한다.

<br>

---

### 🛠️ **구현할 기능 목록**

1. **입력받은 문자열 처리**
   - `readInput()` 함수에서 사용자 입력을 받는다.
   - 입력값이 비어 있으면 0을 반환한다.

2. **기본 구분자(쉼표, 콜론) 처리**
   - `splitByDefaultDelimiters()` 함수에서 쉼표(,)와 콜론(:)을 구분자로 입력 문자열을 분리한다.
   - 분리된 숫자를 리스트로 반환한다.

3. **커스텀 구분자 처리**
   - `splitByCustomDelimiter()` 함수에서 커스텀 구분자를 인식하고 이를 기준으로 문자열을 분리한다.
   - 커스텀 구분자가 있으면 이를 사용해 숫자를 추출하고, 숫자의 합을 반환한다.

4. **숫자 추출 및 합산**
   - `sumNumbers()` 함수에서 숫자로 변환 가능한 항목만 추출하고, 숫자들의 합을 계산한다.
   - 숫자가 없는 경우 0을 반환한다.

5. **예외 처리**
   - `validateInput()` 함수에서 입력 문자열의 유효성을 검사한다.
   - 음수나 숫자가 아닌 값이 있을 경우 `IllegalArgumentException`을 발생시키고 애플리케이션은 종료

---

### 🧩 **예외 처리**
- **잘못된 구분자**: 커스텀 구분자가 제대로 지정되지 않은 경우 예외를 발생시킨다.
- **음수 입력**: 입력값에 음수가 포함될 경우 예외를 발생시킨다.
- **잘못된 형식**: 구분자 외의 문자가 있거나, 숫자가 아닌 값이 포함된 경우 예외를 발생시킨다.

---

### 📌 **프로그래밍 요구 사항**
- JDK 21에서 실행 가능해야 한다.
- `camp.nextstep.edu.missionutils` 라이브러리를 사용하여 사용자 입력을 받아야 한다.
- 프로그램 종료 시 `System.exit()`를 호출하지 않는다.



<br>
<br>

## 주요 커밋 타입 (AngularJS Git Commit Message Conventions을 참고)
   - **feat**: 새로운 기능 추가
   - **fix**: 버그 수정
   - **refactor**: 코드 리팩토링 (기능 변경 없이 구조 개선)
   - **test**: 테스트 관련 코드 추가 또는 수정
   - **docs**: 문서 관련 작업 (예: README 수정)
   - **chore**: 빌드 및 설정 관련 작업, 외부 라이브러리 변경 등
   - **style**: 코드 포맷팅, 세미콜론 누락 등 기능과 관련없는 스타일 변경


