# Setting up the project
## Setup Yew
### To setup yew
```
rustup target add wasm32-unknown-unknown
cargo install --locked trunk
cargo install wasm-bindgen-cli
```

## Setup Tauri
### install the Tauri cli
```
cargo tauri init
```

## Run the project
```
cargo tauri dev
```