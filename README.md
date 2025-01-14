# 🏦 은행 창구 매니저 Project

## 🌈 commit 규칙

```
# [타입] 제목

##### 제목은 최대 50 글자까지만 입력 ############## -> |

# 본문은 위에 작성
######## 본문은 한 줄에 최대 72 글자까지만 입력 ########################### -> |

# 꼬릿말은 아래에 작성: ex) #이슈 번호

# --- COMMIT END ---
# [타입] 리스트
#   feat    : 기능 (새로운 기능)
#   fix     : 버그 (버그 수정)
#   refactor: 리팩토링
#   style   : 스타일 (코드 형식, 세미콜론 추가: 비즈니스 로직에 변경 없음)
#   docs    : 문서 (문서 추가, 수정, 삭제)
#   test    : 테스트 (테스트 코드 추가, 수정, 삭제: 비즈니스 로직에 변경 없음)
#   chore   : 기타 변경사항 (빌드 스크립트 수정 등)
# ------------------
#     제목 첫 글자를 대문자로
#     제목은 명령문으로
#     제목 끝에 마침표(.) 금지
#     제목과 본문을 한 줄 띄워 분리하기
#     본문은 "어떻게" 보다 "무엇을", "왜"를 설명한다.
#     본문에 여러줄의 메시지를 작성할 땐 "-"로 구분
# ------------------
```

## Step1

UML 큰 틀 정하기(내부 로직 X)

<img width="986" alt="스크린샷 2021-04-27 오후 12 18 34" src="https://user-images.githubusercontent.com/70311145/116179811-ed942d00-a752-11eb-9c02-d01c76906b64.png">

### Step1에 필요한 내용

- 프로세스와 스레드 이해
- 동시성 프로그래밍 이해
- 동기 비동기에 대한 이해
- GCD, `Operation` 사용

### 코드 구현과 이유
