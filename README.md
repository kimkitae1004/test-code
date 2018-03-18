# git 설치
1. https://git-scm.com 에 접속하여 다운로드하여 설치
2. 두 번째 대화상자의 기본 옵션에서 Use Git from the Windows Command Prompt 두 번째 라디오버튼 선택
3. 설치가 다되면 윈도우 시작 버튼의 검색창에 git bash를 검색하여 실행
4. 버전 확인 명령 : git --version
5. 도움말 확인 명령 : git --help 

6. https://github.com 접속 후 sign up을 클릭하여 회원가입
7. 회원가입시 Username, Email Address, Password 등을 입력하고, Create an account를 클릭하여 가입
8. git hub에 Sign in(로그인)을 하고, 이메일 인증을 합니다.
9. 가입시 입력했던 이메일 수신함에서 github에서 온 인증이메일을 열고, github사이트 링크 버튼을 클릭한다.
10. Edit Profile 버튼이나 화면의 상단 가장 오른쪽에 있는 목록(▼)에서 Settins를 선택한다.
11. Name 입력 칸에 영문으로 이름을 입력하고, 맨 아래 Update profile 버튼을 눌러 설정값을 변경한다.
12. 화면의 상단 가장 오른쪽에서 두 번째 메뉴인 +(Create a new repository)를 선택하여 레포시토리를 추가한다.
13. repository 생성 화면에서 Repository name, Description을 입력하고, Public을 선택 후 Create repository 버튼을 클릭하여 레포시토리를 생성한다.
14. 윈도우 탐색기를 이용해 d:\ex4 폴더를 생성하고,  ex4폴더를 선택한 후 마우스 오른쪽 버튼을 눌러 나오는 메뉴에서 Git Bash Here를 눌러 git bash의 실행위치를 정하여 실행한다.
15. git bash에서 key를 생성하기 -> ssh-keygen
16. ssh-keygen 명령 후 나오는 옵션에서는 모두 엔터를 쳐서 비밀번호 입력칸을 비워두고, 나오는 내용중에서 Enter file in which to save the key()의 괄호안에 ssh-key가 저장된 폴더를 확인한다.
17. ssh-key가 저장된 폴더인 c:\Users\사용자명\.ssh 폴더에 있는 id_rsa.pub 파일을 에디터에서 열고, 그 내용을 복사하기 한다.
18. github에서 화면의 상단 가장 오른쪽에 있는 목록(▼)에서 Settings를 누르면 나오는 화면에서 여섯 번째 항목인 SSH and GPG keys의 링크를 누르고, New shh key 버튼을 누른다.
19. title 항목에 ssh-key 라고 입력하고, key 항목에 에디터에서 복사하기 한 key값을 붙여넣기 하고, Add Shh key를 눌러 키를 추가한다.

20. git bash에서 사용자 설정을 한다. 
git config --global user.name "사용자이름"
git config --global user.email email@example.com
21. git bash에서 d:\ex4\test-code 폴더를 만들고, 이 폴더로 이동(cd test-code)한다.
22. d:\ex4\test-code에서 버전관리를 시작 -> git init
23. README.md 파일 생성 -> touch README.md
24. 편집기를 이용하여 README.md의 내용을 마크다운 언어로 작성하고, 저장한다.
25. git 상태 확인 -> git status
26. git 관리 대상 및 추적 대상자 추가 -> git add README.md
27. git의 모든 폴더 및 파일 관리 대상자 추가 -> git add .
28. git의 작업내용을 기록하고 관리 대상자를 확정 -> git commit -m '커밋할 메시지'
29. 원격 저장소 지정 -> git remote add origin 해당git의repository주소
30. 원격 저장소에 업로드 -> git push -u origin master
31. 해당하는 아이디나 이메일, 패스워드를 물어볼 경우 제대로 입력해야 업로드가 성공한다.

32. git으로 원격저장소의 내용을 로컬컴퓨터에 복제하기 -> git clone 레포시토리주소
33. git 대상자 추가 및 메시지기록 -> git -a -m '커밋메시지'
34. 원격 저장소에 내용을 로컬컴퓨터에 가져오기 -> git pull 레포시토리주소
35. 로컬컴퓨터의 내용을 원격 저장소에 넣기 -> git push 레포시토리주소



