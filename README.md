# yew-starter

A template for starting a Yew.

# Pre-reqs

Install rust if necessary

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Install node if necessary

```
brew install node
```

# Getting started

- Clone the repository

```
git clone --depth=1 https://github.com/SASUKE40/yew-starter.git <project_name>
```

## Install dependencies

```
cargo install wasm-pack
cargo install cargo-web
npm i
```

## Local development

```
npm start
# navigate to http://localhost:1234
```

```
npm build
```

## Serve

```
npm i serve -g
serve dist
# navigate to http://localhost:5000
```
