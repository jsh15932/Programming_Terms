- Gitflow Workflow에서는 항상 유지되는 메인 브랜치들(master, develop)과 일정 기간 동안만 유지되는 보조 브랜치들(feature, release, hotfix)을 포함하여 총 5가지의 브랜치를 사용한다. 
- Master Branch는 제품으로 출시될 수 있는 브랜치다.
- 배포(Release) 이력을 관리하기 위해 사용. 즉, 배포 가능한 상태만을 관리한다.
- Develop Branch는 다음 출시 버전을 개발하는 브랜치다.
- 기능 개발을 위한 브랜치들을 병합하기 위해 사용. 즉, 모든 기능이 추가되고 버그가 수정되어 배포 가능한 안정적인 상태라면 develop 브랜치를 ‘master’ 브랜치에 병합(merge)한다. 
- 평소에는 이 브랜치를 기반으로 개발을 진행한다.
- Feature branch는 기능을 개발하는 브랜치다.
- feature 브랜치는 새로운 기능 개발 및 버그 수정이 필요할 때마다 ‘develop’ 브랜치로부터 분기한다. 
- feature 브랜치에서의 작업은 기본적으로 공유할 필요가 없기 때문에, 자신의 로컬 저장소에서 관리한다. 
- 개발이 완료되면 ‘develop’ 브랜치로 병합(merge)하여 다른 사람들과 공유한다.
- Release Branch는 이번 출시 버전을 준비하는 브랜치다.
- 배포를 위한 전용 브랜치를 사용함으로써 한 팀이 해당 배포를 준비하는 동안 다른 팀은 다음 배포를 위한 기능 개발을 계속할 수 있다. 
- 즉, 분리된 개발 단계를 정의하기에 아주 좋다. 
- Hotfix Branch는 출시 버전에서 발생한 버그를 수정 하는 브랜치다.
- 배포한 버전에 긴급하게 수정을 해야 할 필요가 있을 경우, ‘master’ 브랜치에서 분기하는 브랜치다. 
- ‘develop’ 브랜치에서 문제가 되는 부분을 수정하여 배포 가능한 버전을 만들기에는 시간도 많이 소요되고 안정성을 보장하기도 어렵다.
- 그러므로 바로 배포가 가능한 ‘master’ 브랜치에서 직접 브랜치를 만들어 필요한 부분만을 수정한 후 다시 ‘master’브랜치에 병합하여 이를 배포해야 하는 것이다. 
- 배포한 버전에 긴급하게 수정을 해야 할 필요가 있을 경우, ‘master’ 브랜치에서 hotfix 브랜치를 분기한다. (‘hotfix’ 브랜치만 master에서 바로 딸 수 있다.)
- 문제가 되는 부분만을 빠르게 수정한 후, 다시 ‘master’ 브랜치에 병합(merge)하여 이를 안정적으로 다시 배포한다.
- 이후, 새로운 버전 이름으로 태그를 매긴다.
- hotfix 브랜치에서의 변경 사항은 ‘develop’ 브랜치에도 병합(merge)한다.
- 버그 수정만을 위한 ‘hotfix’ 브랜치를 따로 만들었기 때문에, 다음 배포를 위해 개발하던 작업 내용에 전혀 영향을 주지 않는다. 
- ‘hotfix’ 브랜치는 master 브랜치를 부모로 하는 임시 브랜치라고 생각하면 된다.
