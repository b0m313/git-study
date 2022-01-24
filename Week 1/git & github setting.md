# git & github Setting

해당 Setting은 Window 10 를 기준으로 작성되었습니다. 

1. Git 설치 파일 [Download](http://git-scm.com/download/win)

2. Git Setup 설치
* ☑ Additional icons  > ☑ On the Desktop <br>
: 바탕 화면에 바로가기 icons을 추가

* ☑ Windows Exporer integration > <br>
    1. ☑ Git Bash Here : Git Bash 기능 <br>
    2. ☑ Git GUI Here : Git GUI 기능 <br>
    → folder에서 git을 바로 연결할 수 있는 기능들 <br>
    
    → 설치한 후 folder에서 우클릭하면 확인 가능.

* ☑ Git LFS (Large File Support) <br>
: 용량이 큰 file 지원 여부

* ☑ Associate .git configuration files with the default text editor <br>
: git 구성 파일을 default text editor와 연결

* ☑ Associate .sh files to be run with Bash <br>
: `.sh` 확장자 파일 Bash와 연결

* ☑ Check daily for Git for Windows updates <br>
: Windows용 git Updates를 매일 check할지 여부

3. [Github 가입](https://github.com/)

4. Repository 추가 <br>
    * new > Repository Name 작성 > ☑ Add a README file

5. 토큰 생성
현재 Github의 보안 정책은 ID/PW으로 login하는 것보단 token으로 login하는 것을 권장.
    * 우상단 프로필 > Setting > Developer Settings > Personal access tokens <br> > Generate new token > Note 작성 > Expiration 설정 <br> > ☑ repo > Generate token <br> > token 복사해서 메모장 저장

    > ❗ tip 1 ❗ Note 작성 시 자신이 나중에 알아보기 쉽게 작성.
    
    > ❗ tip 2 ❗ Expiration 설정 시 90 days 추천 

    > ❗ tip 3 ❗ 새로고침하면 두 번 다시 못보고 안녕할 수도 있으므로 꼭 복사해서 저장

6. git 자격 증명 관리자 설정
    * 🔎 > '자격증명관리자' > Windows 자격 증명 > 일반 자격 증명 추가 <br> > 
![GitSetting1](https://user-images.githubusercontent.com/76231561/150728783-01fb497b-ef89-400b-a091-9984c5907f4b.jpg)
