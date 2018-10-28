# AndroidPrograming

github 명령어 정리
=================

usage 
-----

git [--version] [--help] [-C <path>] [-c <name>=<value>]
   
[--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
   
[-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
 
[--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]

예시: git version
  

start a working area (see also: git help tutorial)
--------------------------------------------------
   clone      Clone a repository into a new directory
   
   init       Create an empty Git repository or reinitialize an existing one
   
   작업공간을 만드는 명령어이다.
   
   clone: 새로운 directory에 저장소를 복사하는 작업
   
   init: 빈 저장소를 생성하거나 기존에 존재하는 저장소를 초기화하는 


work on the current change (see also: git help everyday)
--------------------------------------------------------

   add        Add file contents to the index
   
   
   mv         Move or rename a file, a directory, or a symlink
   
   
   reset      Reset current HEAD to the specified state
   
   
   rm         Remove files from the working tree and from the index
   
   현재 바뀐것을 적용하는 명령어이다.
   
   add: 파일을 저장하는 명령어이다.
   
   mv: 링크, 디렉토리. 파일의 이름을 변경하거나 이동시키는 명령어.
   
   reset: 특정상태를 다시 원래상태로 초기화 시키는 명령어
   
   rm : 파일을 삭제하는 
   
   

examine the history and state (see also: git help revisions)
------------------------------------------------------------
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status
   
   이전에 했던것들과 현재상태를 확인하는 명령어
   
   bisect: 특정버그를 어느위치에서 시작이 되었는지 확인이 가능한 명령어
   
   grep: 특정패턴에 해당하는 라인의 수를 출력한다.
   
   log: 변경된 기록들을 보여주는 명령어
   
   show: 객체의 다양한 형태를 출력한다.
   
   status: 작업의 하위상태를 보여주

grow, mark and tweak your common history
----------------------------------------
   branch     List, create, or delete branches
  
   checkout   Switch branches or restore working tree files
   
   commit     Record changes to the repository
   
   diff       Show changes between commits, commit and working tree, etc
   
   merge      Join two or more development histories together
   
   rebase     Reapply commits on top of another base tip
   
   tag        Create, list, delete or verify a tag object signed with GPG
   
   
   history를 표시, 수정들을 하는 명령어
   
   branch: 하위목록을 생성, 삭제, 목록을 생성시키는 명령어
   
   checkout: 하위목록의 위치를 변화시키거나 변화를 저장시키는 명령어
   
   commit: 저장소의 변화를 저장
   
   diff: 다른 하위목록들과의 비교를 위한 명령어
   
   merge: 2개 이상의 이력을 하나로 합치는 명령어
   
   rebase: 다른 베이스에 변경된 사항들을 다시 적용하는 
   
   tag: 태그를 만들고 목록화하고 지우는 명령어

collaborate (see also: git help workflows)
------------------------------------------

   fetch      Download objects and refs from another repository
   
   pull       Fetch from and integrate with another repository or a local branch
   
   push       Update remote refs along with associated objects
   
   협업에 관련된 명령어
   
   fetch: 다른 저장소로 부터 객체와 참조같은 것을 다운로드하는 명령어
   
   pull: 다른 저장소나 로컬 branch를 통합하고 fetch하는 명렁어
   
   push: 객체와 관련된 다른 참조를 업데이트 하는 명령어
   

# markdown 명령어 정리

큰 제목
------

this is title
=============

작은 제목
--------

this is subtitle
-----------------

글머리(실질적으로 글자의 크기를 나태내데 사용하는 것으로 추정)
-----------------------------------------

# h1

## h2

### h3

#### h4

##### h5

###### h6

글머리는 최대 1에서 6까지 지원.

블록인용
----

> 인용하는 방법을 
>> 인용하는 방
>>> 인용하는 방법을

순서에 번호를 입력을 할 떄
----------------
1. 첫번째
2. 두번째
3. 세번째

순서에 숫자가 아닌 문양을 표시할 경우
*
+ 
-
