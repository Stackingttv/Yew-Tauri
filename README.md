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
cargo install tauri-cli --locked --version "^1.0.0-rc"
```

### Check to make sure Tauri is installed properly
```
cargo tauri info
```

## Run the project
```
cargo tauri dev
```