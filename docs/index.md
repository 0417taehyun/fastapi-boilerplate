---
title: "FastAPI Boilerplate Collection"
description: "The List of FastAPI Boilerplate like using Sentry, CircleCI, Alembic, GitHub Actions, WebSocket, etc."
---

# FastAPI Boilerplate Collection

## Boilerplate List

Here is a list of boilerplate.

* **Description** : A short description of boilerplate. You can move to specification of it by click.
* **Branch** : You can clone a specific boilerplate by branch.
* **Status** :
    * :white_check_mark: which means **Complete**
    * :construction: which means **Work In Progress**
    * :see_no_evil: which means **Not Start**  
* **Last Updated** : Last updated date.



|Description|Branch|Status|Last Updated|
|:--------:|:-----:|:----:|:----------:|
|[Plain synchronous RESTful API](plain-synchronous-restful-api.md)|`plain-synchronous-restufl-api`|:construction:|November 18th, 2021|
|[Plain asynchronous RESTful API](plain-asynchronous-restful-api.md)|`plain-asynchronous-restufl-api`|:construction:|November 18th, 2021|

## Clone a specific boilerplate

Clone a specific boilerplate using branch which looks like ...

<div class="termy">
    ```sh
    $ git clone -b plain-synchronous-restful-api https://github.com/0417taehyun/fastapi-boilerplate.git

    Cloning into 'fastapi-boilerplate'...
    remote: Enumerating objects: 138, done.
    remote: Counting objects: 100% (138/138), done.
    remote: Compressing objects: 100% (98/98), done.
    remote: Total 138 (delta 30), reused 127 (delta 19), pack-reused 0
    Unpacking objects: 100% (138/138), 318.56 KiB | 652.00 KiB/s, done.
    Resolving deltas: 100% (30/30), done.
    ```
</div>

## Install packages

Install packages which looks like ...

!!! warning

    It used [Poetry](https://python-poetry.org/) for managing pacakges.

    So before you install all the packages in each boilerplate by `pyproject.toml` file, you shoud install Poetry first.

    Ex. `pip install poetry`

    Also, it is recommended to user virtual environment [MiniConda](https://docs.conda.io/en/latest/miniconda.html) for managing serveral projects' packages.

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