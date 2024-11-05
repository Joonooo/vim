# Vim 단축키 학습 노트

## 목차
- [기본 이동 명령어](#기본-이동-명령어)
- [편집 명령어](#편집-명령어)
- [검색 및 바꾸기](#검색-및-바꾸기)
- [매크로 및 반복](#매크로-및-반복)
- [플러그인 관련 명령어](#플러그인-관련-명령어)

---

## 기본 이동 명령어

| 단축키 | 설명             | 예시 |
| ------- | ---------------- | ---- |
| `h`     | 왼쪽으로 이동    |      |
| `j`     | 아래로 이동      |      |
| `k`     | 위로 이동        |      |
| `l`     | 오른쪽으로 이동  |      |

### 추가 설명
- `w`: 다음 단어의 시작으로 이동
- `b`: 이전 단어의 시작으로 이동

> **Tip**: `ctrl + f`와 `ctrl + b`는 페이지 단위로 이동할 때 유용합니다.

---

## 편집 명령어

| 단축키  | 설명                 | 예시 |
| -------- | -------------------- | ---- |
| `i`      | 입력 모드로 전환 (현재 커서 앞) |      |
| `a`      | 입력 모드로 전환 (현재 커서 뒤) |      |
| `dd`     | 현재 줄 삭제         |      |
| `yy`     | 현재 줄 복사         |      |

### 추가 설명
- `u`: 마지막 명령 취소 (undo)
- `ctrl + r`: 마지막 취소 복원 (redo)

> **Note**: 삭제한 내용은 `p`로 붙여넣을 수 있습니다.

---

## 검색 및 바꾸기

| 명령어         | 설명                          | 예시 |
| -------------- | ----------------------------- | ---- |
| `/pattern`     | `pattern`을 위에서 아래로 검색 |      |
| `?pattern`     | `pattern`을 아래에서 위로 검색 |      |
| `:s/old/new/g` | 현재 줄에서 `old`를 `new`로 모두 변경 |      |

### 추가 설명
- `n`: 다음 검색 결과로 이동
- `N`: 이전 검색 결과로 이동

> **Tip**: `:%s/old/new/g`로 파일 전체에서 바꿀 수 있습니다.

---

## 매크로 및 반복

| 명령어   | 설명                          | 예시 |
| -------- | ----------------------------- | ---- |
| `q<레지스터>` | 매크로 녹화 시작 (`q`로 종료) |      |
| `@<레지스터>` | 녹화된 매크로 실행            |      |

### 추가 설명
- 매크로는 반복적인 작업을 자동화하는 데 유용합니다.

> **Note**: 매크로를 자주 사용하면 작업 효율이 크게 향상됩니다.

---

## 플러그인 관련 명령어

| 플러그인 | 명령어            | 설명 |
| -------- | ----------------- | ---- |
| NerdTree | `:NERDTreeToggle` | 파일 트리 보기/숨기기 |
| Fzf      | `:Files`          | 파일 검색 |

### 추가 설명
- 플러그인 명령어는 Vim의 기능을 확장해줍니다. 자신에게 필요한 플러그인을 추가하고 관련 명령어를 학습해 보세요.

---

## 추가 학습 및 메모
- 특정 단축키가 익숙하지 않다면, 매일 몇 번씩 사용해보세요.
- 자주 사용하는 명령어와 그렇지 않은 명령어를 구분하여 정리해 보세요.

> **Suggestion**: 자신의 작업 흐름에 맞는 단축키를 따로 정리하고, 이를 효율적으로 사용할 수 있는 방법을 고민해 보세요.
