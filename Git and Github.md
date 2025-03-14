# 2025 / 01 / 24
-------------------------------------------------------

 ## 오늘 배운 TIL 첫 작성!
 
 1. 깃을 다운로드 받아 작성을 시작하였습니다
 2. 깃허브의 리포지토리를 따로 만들어서 타임라인 별로 끊어서 작성하는 법을 알게되었습니다
 3. VCS(Version Control System)의 일종으로 프로그램의 버전 관리를 위한 툴입니다
 4. Commit, Push, Pull의 과정을 알게되었습니다

 # Git
  * 시간(시간에 따른 버전 변화 -> V1에서 V2로 변경시)과 차원(원본과 복사본, 추가 업데이트본) 두 축으로 관리를 해준다 
 # Github
 * Git으로 관리하는 프로젝트들을 온라인 공간에 공유해서 프로젝트 구성원들이 함께 소프트웨어를 만들어나갈 수 있도록 돕는 코드 공유 및 협업 서비스 
 * 온라인 git 저장소는 모든 업로드와 다운로드를 커밋 단위로 주고 받는다!
 + ex ) 팀원 A가 커밋을 해서 버전을 만들어 업로드를 하면 깃헙 상의 프로젝트는 해당 버전으로 최신화되고, 팀원 B가 완료한 작업을 커밋해서 올리기 위해서는 반드시 깃헙 상의 최신 커밋을 먼저 다운받아서 자기 PC에 있는 프로젝트 적용부터 하도록 강제가 된다, 커밋 상의 충돌사항이 있다면 그것도 팀원 B의 컴퓨터에서 병합 등으로 해결 하여야 비로소 자신이 작업한 커밋을 공유 공간에 올릴 수 있다!

__정리하자면 작업은 개개인이 원하는 공간에서 원하는 시간에 하되 공유공간에 올릴 때에는 깃헙이 중간에서 교통 정리를 하여 서로의 작업 간 loss가 발생하지 않도록 해준다!__

+ 전세계의 많은 오픈소스 프로젝트들이 깃헙에서 공유되고 있다는 점!

# Commit
* 커밋을 통하여 새롭게 변경된 부분만 추출하여 시간에 따라 변화하는 내용만 관리하고, 코드가 변화된 시간의 순서에 따라서 영구적으로 저장이 된다!
해당 기능을 통하여 코드의 변경 전 내용, 변경된 내용을 동시에 확인하고 오류를 쉽게 파악할 수 있다!

 # Push 
 * 원격으로 커밋 밀어올리기 
 
 # Pull 
 * 원격으로 커밋 당겨오기

### 그외...
> _원한다면 vsCode나 이클립스를 활용하여 직접적으로 Git과 연결하여, 해당 md 파일 혹은 html 파일을 직접적으로 관리하는 것이 가능하다!
하지만 자칫 복잡해지고 코드 공유과정에서 문제가 생길 수 있으니, 협업을 한다면 사용하지 않는 것이 좋다!
개인적으로 글을 정리할때 사용하도록하자!_

 `해당 글은 WD파일로 작성되었습니다 wd 작성법은 익숙해진뒤 따로 문서화 하여 작성하겠습니다! `
