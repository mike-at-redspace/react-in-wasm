# WASM Rust / React Todo

Example Using https://github.com/yishn/wasm-react

Install Rust & wasm-pack:

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh
rustup target add wasm32-unknown-unknown
```

Add target
```sh
rustup target add wasm32-unknown-unknown
```

Install dependencies and start the server:

```sh
$ yarn
$ yarn build
$ yarn start
```
