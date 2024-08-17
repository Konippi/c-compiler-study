# Learning C Compiler :gear:

This repository is to learn how to implement a simple C compiler. <br>
The code is based on the online book [低レイヤを知りたい人のためのCコンパイラ作成入門](https://www.sigbus.info/compilerbook) by [Rui Ueyama](https://github.com/rui314)-san.

## Requirements

- just only [Docker](https://www.docker.com/)

## Setup Environment

1. Run the docker container.

    ```bash
    $ docker-compose up -d
    ```

2. Enter the container.

    ```bash
    $ docker exec -it c-compiler-ubuntu bash
    ```

    - if you can already use `make`, you can use the following command.

        ```bash
        $ make in
        ```
