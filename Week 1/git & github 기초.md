# git & github Tutorial

## Git 
소스 코드를 효율적으로 관리하기 위해 만들어긴 분산형 버전 관리 시스템(DVCS, Distributed Version Control System)

> 원래는 Linux 소스 코드를 관리할 목적으로 개발.    

> 컴퓨터 파일의 변경 사항을 추적하고 사용자들 간에 파일에 대한 작업을 조율하는데 사용.

> 주로 여러 명의 개발자가 하나의 소프트웨어 개발 프로젝트에 참여할 때, 소스 코드를 관리하는 데 주로 사용.

<br>
✔️ Linux 창시자(리누스 토르발스)에 의해 개발. (현재 MS꺼) <br>
✔️ 무료 공개 소프트웨어
<br> <br>

* 버전 관리 : 파일들을 복사/백업/저장 등을 해서 관리하는 것.
> 클라이언트-서버(cvs,svn, ...), 분산 모델 
<br> <br>

📍 특징 <br>
1. 병렬 개발
> 별도로 주고 받는 작업 없이 같은 파일을 여러 명이 동시에 개발 가능.

2. 작업한 파일에 대한 변경된 정보를 실시간으로 저장.
> 소스 코드의 변경 이력을 쉽게 확인 가능.

3. 같은 파일에 대한 각각 다른 버전을 보관 가능.
> 특정 시점에 저장된 버전과 비교하거나 특정 시점으로 되돌아갈 수 있음.

<br>

## Github
: git을 사용하는 프로젝트를 지원하는 웹호스팅 서비스 시스템(클라우드).
> 버전 관리와 협업을 위한 코드 웹 호스팅 서비스.

> 언제 어디서나 협업 프로젝트를 쉽게 진행할 수 있도록 돕는 역할.
<br>

* Naver, Google 드라이브와는 개념이 다름. <br>
    > 이 친구들은 파일을 자신의 컴퓨터가 아닌 다른 인터넷 상 어딘가에 올려 놓는데 다른 사람과 작업할 때 파일을 누가 수정하고 있는지 알 수 있는 방법이 없음. <br>
    
    > 동시 수정 시 충돌 발생 가능성 존재.

<br>

## 관련 용어 정리
* Workflow (작업 흐름) : 작업 절차를 통한 정보·업무의 이동. <br>
    → 작업 절차의 운영적 측면. <br>
    → 업무들의 구성, 수행자, 순서의 흐름, 동기화 방식, 업무를 지원하기 위한 정보의 흐름, 업무의 추적, ...

* git에서의 Version (버전)<br>
    : 문서를 수정할 때 마다 간단한 메모와 함께 수정 내용을 snapshot으로 저장한 것.

* git의 3가지 영역

    * Working Tree (작업 트리)<br> 
    : 작업 공간으로 아직 git에 기록될 준비가 되지 않은 파일들이 위치하는 공간.<br>
    : Working Directory (작업 디렉터리) <br>
    : 파일 수정·저장 등 작업을 하는 디렉터리<br>
        → 저장소를 어느 한 시점을 바라 보는 작업자의 현재 시점.
    * Staging Area (대기 공간) <br>
    : 버전으로 만들 파일이 대기하는 곳
    : git에 기록될 준비가 된 파일들이 위치하는 공간. <br>
        → 저장소에 커밋하기 전에 커밋을 준비하는 위치.
    * Repository <br>
    : 파일·폴더를 저장해두는 저장소. <br>
    : stage에서 대기하고 있던 파일들을 버전으로 만들어 저장하는 곳 <br>
        → History, Tag, 소스의 Branch에 따라 버전 저장. <br>
        → 저장소를 통해서 작업자가 변경한 모든 히스토리 확인 가능.<br>
        * Local Repository(Local 저장소) : 나의 pc에 저장되는 개인 전용 저장소.
        * Remote Repository(Remote 저장소) : 원격 저장소 전용 서버에 저장되는 저장소.

* Commit : 파일을 추가·변경한 내용을 저장소에 저장하는 작업.<br>
    → 현재 변경된 작업 상태의 점검을 마친 뒤 확정하여 저장소에 저장.<br>
    → 변경사항을 local 저장소에 기록하는 것. <br>
        **"완성된 파일을 올리는 것이 아니다."** <br>
        **"자신의 개발 단계를 기록하는 것이다."**

* Push : 추가·변경한 내용을 원격 저장소에 업로드하는 작업 .<br>

* Index : Commit을 하기 전에 그 사이의 공간.<br>
    → 인덱스라는 공간에 파일의 상태를 기록.
    * index 등록 : 자신이 local 저장소에 추가·변경한 파일 중 선택하는 작업.

* Branch (분기점) : 일련의 작업을 독립적으로 만들기 위한 개념.<br>
    → 특정 시점(마지막 Commit)에서 여러 가지 작업을 해야할 때, 여러 작업을 동시에 진행할 수 있게 해줌.<br>
    → 복사하여 Branch에서 작업한 후 완전할 경우 Merge.

* Head : 현재 작업 중인 Branch. <br>

* Merge : Branch의 내용을 현재 Branch로 가져와서 합치는 작업.
