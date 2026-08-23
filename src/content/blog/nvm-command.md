---
title: '자주 쓰는 nvm 명령어'
description: '제가 자주쓰는 nvm 명령어를 설명합니다.'
pubDate: '2026-08-23'
heroImage: '../../assets/default-image.png'
---

##### nvm install 관련 명령어

```bash
nvm install [<version>] # `nvm install 24.19.0` 또는 `nvm install 24`와 같이 사용해서, 특정버전의 Node.js를 설치

nvm install node # 가장 최신버전의 Node.js를 설치

nvm install --lts # 가장 최신버전의 lts Node.js를 설치
```

##### nvm ls 관련 명령어

```bash
nvm ls # 설치된 Node.js 버전들 확인

nvm ls-remote # 설치할 수 있는 모든 Node.js 버전 조회 (너무 많아서, 이런게 있구나 정도로만 사용하시면 될 것 같습니다.)
```

##### nvm alias default 관련 명령어

```bash
nvm alias default node # 설치되어 있는 Node.js 버전들 중에서 가장 최신버전을 기본으로 사용

nvm alias default [<version>] # 설치되어 있는 Node.js 버전들 중에서 인자값으로 넘어온 특정버전을 기본으로 사용
```


##### 나머지

```bash
nvm use [<version>] # 사용하는 Node.js의 버전을 수정하기

nvm current # 현재 사용중인 Node.js 버전 확인하기

nvm uninstall [<version>] # 인자값으로 넘어온 특정버전의 Node.js 삭제하기
 ```
