## 설치하기
```sh
curl https://sh.rustup.rs -sSf | sh

source $HOME/.cargo/env # 터미널을 재시작하면 적용되나, 수동 진행

rustc --version
cargo --version # 러스트의 빌드 시스템 및 패키지 매니저. 같이 설치됨
```

<br>

## 실행하기
```sh
# rust 진행하기
mkdir hello_world
cd hello_world
touch main.rs
rustc ./main.rc
./main

# cargo 진행하기
cargo new hello_cargo --bin
cd hello_cargo
cargo build
# 또는 ./target/debug/hello_cargo
cargo run
# 컴파일 여부 확인
cargo check
```