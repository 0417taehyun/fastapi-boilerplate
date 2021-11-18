---
title: "FastAPI 보일러플레이트 모음"
description: "Sentry, CircleCI, Alembic, GitHub Actions, WebSocket 기타 등등을 사용한 FastAPI 보일러플레이트 목록."
---

# FastAPI 보일러플레이트 모음

<a href="https://github.com/0417taehyun/fastapi-boilerplate" target="_blank"><img src="/images/background.png" /></a>

## 보일러플레이트 목록

여기 보일러플레이트 목록이 있습니다.

* **설명** : 보일러플레이트에 관한 간단한 설명입니다. 클릭하여 상세 설명 페이지로 이동할 수 있습니다.
* **브랜치** : 브랜치를 사용하여 특정 보일러플레이트를 복제할 수 있습니다.
* **상태** :
    * :white_check_mark: **완성**을 의미합니다.
    * :construction: **작업 진행 중**을 의미합니다.
    * :see_no_evil: **시작하지 않음**을 의미합니다.
* **마지막 수정** : 마지막 수정 일자를 의미합니다.

|설명|브랜치|상태|마지막 수정|
|:--------:|:-----:|:----:|:----------:|
|[간단한 동기적 RESTful API](simple-synchronous-restful-api.md)|`simple-synchronous-restufl-api`|:construction:|2021년 11월 18일|
|[간단한 비동기적 RESTful API](simple-asynchronous-restful-api.md)|`simple-asynchronous-restufl-api`|:construction:|2021년 11월 18일|

## 특정 보일러플레이트 복제

브랜츠를 사용하여 특정 보일러플레이트를 복제하는 건 다음과 같습니다 ...  

<div class="termy">
    ```sh
    $ git clone -b simple-synchronous-restful-api https://github.com/0417taehyun/fastapi-boilerplate.git

    Cloning into 'fastapi-boilerplate'...
    remote: Enumerating objects: 138, done.
    remote: Counting objects: 100% (138/138), done.
    remote: Compressing objects: 100% (98/98), done.
    remote: Total 138 (delta 30), reused 127 (delta 19), pack-reused 0
    Unpacking objects: 100% (138/138), 318.56 KiB | 652.00 KiB/s, done.
    Resolving deltas: 100% (30/30), done.
    ```
</div>

## 패키지 설치

패키지 설치는 다음과 같습니다 ...  

!!! warning

    패키지 관리를 위해 [Poetry](https://python-poetry.org/)를 사용합니다.  

    따라서 `pyproject.toml`을 활용하여 각 보일러플레이트의 모든 패키지를 설치하기 이전에, 먼저 Poetry를 설치해야 합니다.  

    예를 들어 `pip install poetry`와 같습니다.

    또한, 여러 프로젝트의 패키지 관리를 위해 [미니콘다](https://docs.conda.io/en/latest/miniconda.html)와 같은 가상 환경을 사용하는 걸 추천드립니다.


<div class="termy">
    ```sh
    $ poetry install

    Installing dependencies from lock file

    Package operations: 29 installs, 0 updates, 0 removals

    • Installing idna (3.3)
    • Installing sniffio (1.2.0)
    • Installing anyio (3.3.4)
    • Installing greenlet (1.1.2)
    • Installing markupsafe (2.0.1)
    • Installing pyasn1 (0.4.8)
    • Installing pyparsing (2.4.7)
    • Installing six (1.16.0)
    • Installing typing-extensions (4.0.0)
    • Installing asgiref (3.4.1)
    • Installing attrs (21.2.0)
    • Installing click (8.0.3)
    • Installing ecdsa (0.17.0)
    • Installing h11 (0.12.0)
    • Installing iniconfig (1.1.1)
    • Installing mako (1.1.5)
    • Installing packaging (21.2)
    • Installing pluggy (1.0.0)
    • Installing py (1.11.0)
    • Installing pydantic (1.8.2)
    • Installing rsa (4.7.2)
    • Installing sqlalchemy (1.4.27)
    • Installing starlette (0.16.0)
    • Installing toml (0.10.2)
    • Installing alembic (1.7.5)
    • Installing fastapi (0.70.0)
    • Installing pytest (6.2.5)
    • Installing python-jose (3.3.0)
    • Installing uvicorn (0.15.0)
    ```
</div>