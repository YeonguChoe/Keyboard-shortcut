# Vim 단축키

<img src="./Vim_modes.svg" width=500 />

## 공통 단축키
### 방향 이동 단축키
- `h`: 왼쪽으로 이동 
- `l`: 오른쪽으로 이동
- `k`: 위쪽으로 이동
- `j`: 아래쪽으로 이동

## 모드
- [Command Mode](Command%20mode.md)
- [Normal Mode](Normal%20mode.md)
- [Insert Mode](Insert%20mode.md)
- Replace Mode
    - `R`: Replace 모드로 진입
    - Replace 모드에 들어가면, 문자를 대체할수 있다.
- [Visual Mode](Visual%20mode.md)


### Window에 관한 단축키

#### Window는 편집기에서 위/아래로 분할되어 있는 화면을 말한다.

1. 새로운 window 만들기: :sp
1. 현재 있는 window 닫기: :quit or :q
1. 다른 window으로 이동: (control + w) + w or j/k
1. 현재 커서가 있는 window의 크기 증가: (control + w) + +
1. 현재 커서가 있는 window의 크기 감소: (control + w) + -

### 탭에 관한 단축키

1. 새로운 탭 만들기: :tabnew
1. 오른쪽 방향의 탭으로 이동: g + t
1. 왼쪽 방향의 탭으로 이동: g + T
1. n번째 tab으로 이동: n + g + t
1. 모든 탭 닫기: :qa!