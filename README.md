### Use Ink 
https://substrate.dev/substrate-contracts-workshop/#/


### pre install

### rust for wasm
rustup component add rust-src --toolchain nightly
rustup target add wasm32-unknown-unknown --toolchain nightly

### test env (canvas-node)
cargo install canvas-node --git https://github.com/paritytech/canvas-node.git --tag v0.1.9 --force --locked

sudo apt install binaryen
cargo install cargo-contract --vers ^0.13 --force --locked
canvas --dev --tmp

cargo contract new erc20
cargo +nightly test
cargo +nightly contract build

### Canvas UI url
https://paritytech.github.io/canvas-ui/#/instantiate


