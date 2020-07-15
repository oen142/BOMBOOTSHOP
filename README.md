## 봄 부트 샵
- 봄 부트샵은 스프링부트 기반으로 만들어진 공개형 쇼핑몰 솔루션입니다.
- 첫 개발에 발을 디딘 개발자들이 솔루션을 만들때 과정을 알아볼수 있게 공부하면서 작성한 코드들입니다.
- 씨아이보드에서 착안했습니다.
- 라이선스는 MIT라이선스를 따르고 있습니다.
- 프로젝트 진행에 따라 ReadMe 업데이트 예정입니다.

# 기능정의


## 환경
- DevOps
    - MariaDB
        - AWS RDS
        - ElastiCache
    - Jenkins
    - Docker
    - Kubernetes
    - AWS EC2
    - AWS ELB
    - AWS REDIS
    - GIT
    - nGrinder
- WEB/BE
    - SpringFramework
        - SpringBoot 2.2.x
        - SpringSecurity
        - SpringCloudAws
    - Gradle    
    - ORM
        - JPA
    - Lombok
   
- WEB/FE
    - 리액트
    
    
## 깃 브랜치 전략

>git flow 사용

- master : 배포시 사용할 브랜치
- develop : 다음 상용버전을 개발하는 브런치, 기능 개발이 끝났을때에 master 브랜치에 merge합니다.
- feature : develop에서 브랜치를 파서 기능을 개발하는 브랜치 이슈하나당 하나의 feature를 따오는것을 목표로합니다.
- release : 배포를 준비하는 브랜치
- hotfix : 실서버에서 돌아갈때 생긴 버그를 급히 수정하는 브랜치

> 참고 : https://woowabros.github.io/experience/2017/10/30/baemin-mobile-git-branch-strategy.html

## 프로젝트 고민거리

## API명세
