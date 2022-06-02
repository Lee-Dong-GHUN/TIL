6월 2일/3일 

---

![image-20220602174359542](README.assets/image-20220602174359542.png)

### Git : 분산 버전 관리 프로그램/ 







![image-20220602093010773](README.assets/image-20220602093010773.png)

![image-20220602093040834](README.assets/image-20220602093040834.png)

![image-20220602093114238](README.assets/image-20220602093114238.png)![image-20220602093117441](README.assets/image-20220602093117441.png)

![image-20220602093345625](README.assets/image-20220602093345625.png)

![image-20220602093437242](README.assets/image-20220602093437242.png)

![image-20220602093601851](README.assets/image-20220602093601851.png)

![image-20220602093703980](README.assets/image-20220602093703980.png)

- 용량이 너무 만다면?

![image-20220602093800094](README.assets/image-20220602093800094.png)

![image-20220602093807162](README.assets/image-20220602093807162.png)

![image-20220602093850900](README.assets/image-20220602093850900.png)

- Git이 버전을 관리하는 방식

![image-20220602093916570](README.assets/image-20220602093916570.png)

![image-20220602094031698](README.assets/image-20220602094031698.png)

- 이게 우리가 배울 깃이다.![image-20220602094056749](README.assets/image-20220602094056749.png)

![image-20220602094158480](README.assets/image-20220602094158480.png)

- 핑크색은 작성해주고 파란색 체크만 내가 표시하면 된다.

![image-20220602094315383](README.assets/image-20220602094315383.png)

![image-20220602094353101](README.assets/image-20220602094353101.png)

- (분산) 버전 관리 프로그램

![image-20220602094531534](README.assets/image-20220602094531534.png)

![image-20220602094606139](README.assets/image-20220602094606139.png)

- 백업을 중앙서버에만 해두어서 복구가 어려운데 분산버전은 괜찮음.

![image-20220602094724845](README.assets/image-20220602094724845.png)

- 인스타 포트폴리오 제출하세요 하면 A,B중에 누구 뽑겠습니까.

![image-20220602094750503](README.assets/image-20220602094750503.png)

- 카드뉴스, 케시물 3천개면 열정, 포스팅 다하려면 매일매일하려면 모자랄텐데 3400개면 엄청 성실하구나.

![image-20220602094854569](README.assets/image-20220602094854569.png)

https://github.com/jojoldu

- 일일히 물어보지 않고 개발자 채용은 그냥 깃허브 아이디 주세요한다.

![image-20220602095258906](README.assets/image-20220602095258906.png)

- 버전관리 프로그램으로 기록물이나 작업물로 개별 각각 보기 힘들다. 그래서 깃허브상에 변경사항 올리고 친구가 보고 나도 친구거 보고, 서로 카카오톡 클론코딩한다고 하면 A가 사인업기능 만들었으면 그거 끌어와서 B가 추가로 만든다.

![image-20220602095407229](README.assets/image-20220602095407229.png)

- 깃은 분산 버전 관리, 내 컴퓨터 로컬상에서 깃을 가지고 버전을 기록받고 관리. 그리고 서버라고 할 수 있는 깃허브상에 내 관리기록을 업로드한다. 이 버전들을 B가 가져와서 깃으로 쌓은 것을 서버컴퓨터로 옮겨서 협업을 할 수 있다. 깃은 버전을 관리하는 프로그램, 깃허브는 서비스!

![image-20220602095549695](README.assets/image-20220602095549695.png)

- 3개나 있지만

![image-20220602095600449](README.assets/image-20220602095600449.png)

- 동작이 완전 다르지는 않지만 처음시작이니 많이 쓰는 깃허브 먼저 배우자. 취업 후에 회사에서 관리하는 서비스를 이용하면 됨.

![image-20220602095638284](README.assets/image-20220602095638284.png)

- 지금까지 두 가지를 알아보았고 이 두 가지 때문에 깃허브를 배워야한다. 두 가지 장점이 있다.

---

10시12분

![image-20220602102230796](README.assets/image-20220602102230796.png)

- bash창 터미널 (~ :사용자)

![image-20220602102317004](README.assets/image-20220602102317004.png)

- I 는 인터페이스(접점), 유저가 컴퓨터와 마주보는 접점(command line interface, graphic user interface)

- 그럼 왜 CLI를 배워야하나?

  > ![image-20220602102854407](README.assets/image-20220602102854407.png)
  >
  > - __mkdir__ 똑같은 동작을 하는데 GUI보다 CLI가 더빠르게 만들 수 있다.
  >
  > ![image-20220602102930457](README.assets/image-20220602102930457.png)
  >
  > - 여러개 만들때는 훨씬 더 빠르다.
  >
  > - 그럼 왜 CMD 말고 Bash를 하나요? 윈도우가 73프로 점유율이라고 알고 있는데 
  >
  >   > ![image-20220602103036467](README.assets/image-20220602103036467.png)
  >   >
  >   > - __ls__: 내가 보는곳 전체보기/ 윈도우가 명령어에서 독자 노선을 사용하고 있다. 그래서 리눅스가 주인데 이거롤 약간 통일시켜주기 위해서 bash를 사용한다.

- ~ : Home, 내가 로그인하고 있는 계정

  > ![image-20220602103306486](README.assets/image-20220602103306486.png)
  >
  > - 윈도우는 사용자하단 C:user/ 등등 
  >   맥은:/user
  > - pwd(print working directory) : 현재위치,
  >
  > - / : 최상위 폴더
  >
  > ![image-20220602103521747](README.assets/image-20220602103521747.png)

- pwd : 절대경로, 뿌리에서 시드라이브에 유저에 스튜던트에 있어

  > ![image-20220602103631337](README.assets/image-20220602103631337.png)
  >
  > - cd .. : 상대경로
  >
  >   > ![image-20220602103724728](README.assets/image-20220602103724728.png)
  >
  > - ![image-20220602103813722](README.assets/image-20220602103813722.png)

### command line 명령어

바탕화면 - 내PC - C드라이브 - User - lovez - 마우스 오른쪽 Git bash here로 켜준다.

1. 폴더 만들기 : mkdir (make directory)

   > 스크롤 올리기 : ctrl + l

2. 디렉토리 목록확인 : ls (list segments)

   > ls - a / ls -l (숨김항목,언제 만들어졌는지 + 용량까지)

3. 경로 이동 : cd (change directory)

   > cd test/ (/ 는 생략해도 되지만 붙여주는 의미는 이 친구 디렉토리야 알려줌.)

4. 파일 생성 : touch

   > touch a.txt
   > ![image-20220602104933899](README.assets/image-20220602104933899.png)

5. 파일 이동 : mv (move)

   > a.txt 를 상위로 보내려고 한다면
   > ![image-20220602105149763](README.assets/image-20220602105149763.png)
   >
   > .. 

6. 삭제 : rm (remove)

   > *주의 : 검색하다보면 r, rf 옵션등이 있는데 rm등으로 홈폴더등을 완전 잘못 삭제할 수도 있으니 알아만 두시고 되도록 gui 상에서 삭제를 해라. 

> 1. 폴더 만들기
>    mkdir
>    (make directory)
>
> 2. 목록확인
>    ls
>    (list segments)
>    -a : 숨김항목까지
>
> 3. 경로 이동
>    cd
>    (change directory)
>
> 4. 파일 생성
>    touch 
>
> 5. 파일 이동
>    mv
>    (move)
>
> 6. 삭제
>    rm
>    (remove)
>
> * 주의!!!
>   되도록 gui 상에서 삭제
>
> ctrl + l : 스크롤 올리기
>
> ![image-20220602110806290](README.assets/image-20220602110806290.png)
>
> ![image-20220602111414392](README.assets/image-20220602111414392.png)
>
> ![image-20220602111537714](README.assets/image-20220602111537714.png)
>
> ![image-20220602111619810](README.assets/image-20220602111619810.png)

---

11시 15분

vscode 열기 > file > openfolder > CLI 선택
ctrl + ` : 뉴 터미널
![image-20220602112314827](README.assets/image-20220602112314827.png)

![image-20220602112521323](README.assets/image-20220602112521323.png)

> 누르고, select default profiles> git bash선택

![image-20220602113020556](README.assets/image-20220602113020556.png)

> vscode 는 코드 작성 편하게 해주는 에디터인데 
> ![image-20220602113055510](README.assets/image-20220602113055510.png)
>
> 

---

# 2022_06_02_깃허브

오후 1:04

# 제목

h1 ~ h6

# 을 이용한다!(#뒤에 한칸 스페이스)

# 제목1

## 제목2

### 제목3

#### 제목 4

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/70a64dbf-cfd6-4514-b68d-22ef10b4054a/Untitled.png)

# 목록

------

순서 없는 목록

> -,*,+ 한칸띄고 목록(혼용해도 상관이 없음)

- 목록
  - 목록2(tab 들여쓰기)
- 목록 (shift + tab 내어쓰기)

순서가 있는 목록

1. 순서있는 목록

# 강조

------

글자를 감싸서 강조함

글자

*글자*

**글자**

***글자***

글자

# 코드

------

- 한줄 코드 ⇒ 인라인코드
  - `(백틱)dmfh rkaTkrl
- 여러줄 코드 ⇒ 코드블록
  - 백틱으로 감싼다. 백틱의 갯수 = 3개

```bash
ls
cd test/
코드
print(’hello world!’)
```

# 링크

------

https:///bit.ly/dse-1516

[git 특강 페이지] (https:///bit.ly/dse-1516 )

[ 보여질 글자 ](url)

\ 넣으면 역할을 하지 않게한다.

# 이미지

------

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/53ea79ce-2d1a-4bfe-9ea6-62d8af4c81b9/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc30a719-3298-45c9-932d-d970ce52a91b/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/82a27b60-2d4b-49ce-bb3e-a861dbd604d2/Untitled.png)

이미 환경설정해두어서 왼쪽 마크다운 기초.assets 폴더에 asset 으로 이미지가 저장

그리고 상대경로로 __

# 인용

------

> 꺽쇠로 사용, 인용문 안에서 중첩될 수 도 있어요! shift tab 하면 내어쓰기로 나갈 수 있다.

# 구분선

------

- 구분선 —— 으로 만들 수 있다.

  - 구분선

  ------

  구간으로도 만들 수 있다.

------

# 표

------

마크다운에서 타이포라를 왜 사용하냐? 표때문이라고 생각한다.

본문 표 (ctrl + T)

ctrl + / 하면 소스코드 볼 수 있다.

표는 마크다운으로 그리지말고 타이포라에서 편하게 하는게 나을듯 하다.

------

타이포라에서 알아야하는 문법은 이 정도가 끝.

------

순서

1. 0.9.79 버전이 있었음 알려주신 설정대로 트리만들고 파일에서 이미지 항목도 선택함.
2. 0.11.18 버전 다운받고 설치함 (문제발생_파일 메뉴에 항목들이 아무것도 안눌림, 이전파일 안열림, 저장안됨)

> 제가 생각한 문제점 전버전이 32비트가 아니었을까 생각이들었음![image-20220602140114827](README.assets/image-20220602140114827.png)

> 이전 버전거를 지우고 다시 다운받으니 해결. 충돌나서 그런것 같다.

> 실습 진행 14:18끝

---

깃 배쉬, cli 실습도 같이 했는데 이쯤에서 의문이 생겼을것. 깃을 설치했는데 내 컴퓨터의 모든 파일 버전관리가 되는걸까? > 아니겠죠!

깃은 내가 깃한테 직접 명령을 내려야한다. 그때서야 깃이 버전을 관리한다.

![image-20220602142313774](README.assets/image-20220602142313774.png)

![image-20220602142323095](README.assets/image-20220602142323095.png)

![image-20220602142342957](README.assets/image-20220602142342957.png)![image-20220602142404137](README.assets/image-20220602142404137.png)

내 컴퓨터 A에서 하는 버전관리를 지금 할것이다. 깃허브는 조금 이따

![image-20220602143047516](README.assets/image-20220602143047516.png)

- 왜 Staging Area가 필요하나요 2가지 이유. 로그인 기록을 위한 파일들이 있을것 그것들을 한번에 묶어서 이유를 기록할때 하나의 덩어리로 의미가 있어야하기 때문에 Staging Area가 필요. 검토를 위해

![image-20220602143530623](README.assets/image-20220602143530623.png)

- 마우스 있는 곳 U 는 un 뭐시기라고 깃에 올라가지 않은 상태

![image-20220602143915358](README.assets/image-20220602143915358.png)

![image-20220602144245777](README.assets/image-20220602144245777.png)

![image-20220602144251846](README.assets/image-20220602144251846-16541485728449.png)

![image-20220602144305798](README.assets/image-20220602144305798.png)

![image-20220602144353852](README.assets/image-20220602144353852.png)

![image-20220602144408324](README.assets/image-20220602144408324.png)

![image-20220602144443847](README.assets/image-20220602144443847.png)

![image-20220602144542013](README.assets/image-20220602144542013.png)

![image-20220602144610470](README.assets/image-20220602144610470.png)

- 3이상 커지면 엄청 길어지기에 oneline으로!

![image-20220602144945292](README.assets/image-20220602144945292.png)

- 깃을 인잇한 레포지토리 한다음에 또 레포지토리하는 서브모듈 뭐시기하기 때문에 홈폴더X 그리고 홈폴더가 무거워진다.

![image-20220602145300122](README.assets/image-20220602145300122.png)

- .git 숨김폴더!

![image-20220602145545795](README.assets/image-20220602145545795.png)

- 깃 애드 하고 어디까지 했는지 기억안날때, git status 하면 다른 명령어실행을 알려주니 더 중요하다.
- git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
  git config --global --list
- ![image-20220602151104171](README.assets/image-20220602151104171-165415026790520.png)
- 이메일 잘못 입력했다면 
- git config --global --unset user.email
- git config --global...?



![image-20220602153118112](README.assets/image-20220602153118112-165415147864721-165415148015622.png)

---

1. git init
   git 으로 관리 시작
   -> 디렉토리당 한번만
   주의! 홈폴더나 바탕화면 x

2. git status (중요)
   파일 상태 확인

3. git add 파일명
   무대위로 올리기

4. git commit -m "커밋 사유"
   변경사항을 기록
   즉, 사진 찍기
   (vim 빠져 나오는 것 esc + :q )

5. config 설정 
   -> 한번만
   ->git에게 내가 누군지 알려주기 
   git config --global user.email "you@example.com"
   git config --global user.name "Your Name"
   git config --global --list

6. git log
   커밋의 내역 확인
   --oneline

---

깃 커밋 사유를 잘 못써서 고치고 싶을때는 어떻게 해야하나요?

네, 동건님 git commit --amend -m "변경사유" 를 통해 직전 커밋을 변경할 수 있으나, 크게 권장하고 있지는 않습니다. 이는 이후 수업때 말씀드리도록 하겠습니다.

---

log 하고 더 안넘어가면 q 누르면 넘어가짐

7. git diff 해시값 해시값 
   비교할 수 있다. 빠져나오고 싶으면 q 써서 나온다.

---

### GitHub

내 깃허브 lovezia007@gmail.com / 스릴 그거!

우측 상단 프로필 클릭 > settings > Repositories > master 변경
git config --global user.email "이메일"
git config --global user.name "닉네임"

이전의 커밋 내역은 이전버전으로 들어가있는데 이것은 크게 신경쓰지 않아도 괜찮다. 사이클 도는게 더 우선순위이기 때문에. 이거는 협엽시 이메일이랑 유저네임 때문인건데 중간에 바꾸셔도 괜찮습니다.

로컬에서는 디렉토리 만들고 init 하면 되었었다.

![image-20220602165003228](README.assets/image-20220602165003228.png)

- 우측 상단 + 버튼 누르면 new repository로 나온다.

> ![image-20220602165638301](README.assets/image-20220602165638301-165415659960424.png)
>
> working directory staging area / commit (지금 솔브 다섯개있고 밑에 두개정도 더있을 것이다.) 둘 사이에 다리를 놓아 준다. 이름을 origin 말고 다른거 해도 되지만 클론이라고 하는 명령어를 할 때 자동적으로 url 길의 이름을 origin이라고 하는데 헷갈림 방지를 위해.
>
> ![image-20220602165851627](README.assets/image-20220602165851627-165415673940125.png)
>
> git remote add origin URL(이건 깃허브 그 주소 복사)
>
> ![image-20220602171828995](README.assets/image-20220602171828995-165415791241726.png)git remote -v (이건 확인)
> remote는 원격 저장소!
> repository도 저장소인데 로컬이나 허브에 다 있을 수 있는데 둘다 동일한 리포지토리인데 변경사항 내역과 마지막 파일 백업을 위해 허브를 사용, 백업 협업 ? 3요소인데 내일 협업을 같이 배울것이다.
>
> 문제발생!
>
> > 홈에다가 만들었을때 .git 숨김폴더 다 없애면 정상적으로 돌아온다.
>
> 다리만 놓았다고 올라가지 않는다. 새로운 명령어를 해줘야한다.

- github에 local commits 올리기
  git push origin master

- / local에서 가지고 있었던 요 커밋들을 밀어올릴것

  > ![image-20220602172200400](README.assets/image-20220602172200400.png)
  >
  > - 너가 진짜 권한 있는 사람인지 확인하기 위해 로그인 절차가 필요. 로컬에서 남겼던거 올라가게된다.

- ![image-20220602172645318](README.assets/image-20220602172645318.png)

  > 이 친구 문서작성 능력 괜찮구나. 알고 있는 내용의 직무가 우리 회사와 일치하는구나. TIL을 통해서 이전에 작업했던 내용 추가 복습도 가능. 물론 프로젝트가 더 좋긴하지만/ TIL 레포지토리 만들어보자 우리도
  > https://github.com/cheese10yun/TIL > 참고

![image-20220602172813445](README.assets/image-20220602172813445.png)

![image-20220602173614984](README.assets/image-20220602173614984.png)

(github)

1. TIL 레포지토리를 만든다
2. URL 을 복사한다.

(local)

1. TIL 레포지토리를 만든다 (TIL 폴더 만든 후, git init)
2. README.md 파일을 만든다.
3. 편집 후,
   add -> commit으로 변경사항을 기록한다

(remote와 local 길 연결)

1. git remote add origin URL
2. git remote -v

(local에서 remote로 변경 사항 올리기)
git push origin master

* 주의 : URL은 .git으로 끝나야 함 
  origin의 오타주의

---

1. git init
   git 으로 관리 시작
   -> 디렉토리당 한번만
   주의! 홈폴더나 바탕화면 x

2. git status (중요)
   파일 상태 확인

3. git add 파일명
   무대위로 올리기

4. git commit -m "커밋 사유"
   변경사항을 기록
   즉, 사진 찍기
   (vim 빠져 나오는 것 esc + :q )

5. config 설정 
   -> 한번만
   ->git에게 내가 누군지 알려주기 
   git config --global user.email "you@example.com"
   git config --global user.name "Your Name"
   git config --global --list

6. git log
   커밋의 내역 확인
   --oneline

7. 커밋들을 비교하기
   git diff 해쉬값 해쉬값

8. github와 연결
   git remote add origin URL
   git remote -v

# remote 삭제

git remote rm origin

9. github에 local commits 올리기
   git push origin master