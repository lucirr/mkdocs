# Overview

[PaaSXpert 4.1](https://poratl.openstack.doxpert.co.kr)

## Role

* `개발자 (USER)` - 파이프라인과 배포된 어플리케이션을 조회.
* `배포담당자 (DEPLOYER)` - 파이프라인을 실행하고 승인.
* `책임자 (MANAGER)` - Git 생성 및 Git에 사용자를 할당하며 파이프라인을 생성하고 실행.
* `관리자 (ADMIN)` - 사용자를 생성하고 권한을 부여.
* `시스템관리자 (MASTER)` - 최초 설치시 지정한 시스템관리자, ADMIN 관리자를 생성.

## Main Process

1. **시스템관리자**가 포털에 로그인 한 후 사용자 관리에서 신규 관리자를 등록하고, 그 관리자에게 클러스터 권한을 할당한다.
2. **관리자**는 포털에 로그인 한 후 네임스페이스를 등록하고, 사용자 관리에서 책임자, 배포담당자, 개발자를 등록한다
3. **책임자**는 포털에 로그인 한 후 Git을 생성하고 Git에 사용자를 할당한다. 파이프라인을 생성하고 파이프라인을 실행한다.
4. **배포담당자**는 포털에 로그인 한 후 운영배포 승인을 처리한다.
5. **개발자**는 포털에 로그인 한 후 배포된 파드 상태를 확인하고, 파이프라인 처리 상태를 확인한다.

<!-- ```
    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
```         -->
