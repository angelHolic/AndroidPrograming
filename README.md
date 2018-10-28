# AndroidPrograming

github 명령어 정리
=================

usage 
-----

git [--version] [--help] [-C <path>] [-c <name>=<value>]
   
[--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
   
[-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
 
[--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]

example: git --version
  

start a working area (see also: git help tutorial)
--------------------------------------------------
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one
   
   작업공간을 만드는 명령어이다.
   
   clone: 새로운 directory에 저장소를 복사하는 작업
   
   init: 빈 저장소를 생성하거나 기존에 존재하는 저장소를 초기화하는 

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
