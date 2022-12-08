# Overview

[PaaSXpert 4.1](https://poratl.openstack.doxpert.co.kr)

## 사용자 권한

* `개발자 (USER)` - 파이프라인과 배포된 어플리케이션을 조회.
* `배포담당자 (DEPLOYER)` - 파이프라인을 실행하고 승인.
* `책임자 (MANAGER)` - Git 생성 및 사용자를 등록하며 파이프라인을 생성하고 실행.
* `관리자 (ADMIN)` - 사용자를 생성하고 권한을 부여.
* `시스템관리자 (MASTER)` - 최초 설치시 지정한 관리자, ADMIN 관리자 생성.

## Project layout

```
    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
```        
