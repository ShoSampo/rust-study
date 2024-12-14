# rust-study
Rustの学習用リポジトリ

## Cargoを使ってみる

```
cargo new hello_world
cd hello_world
cargo run
```

## rustfmtとclippyを使ってみる

```
cargo clippy
```

```
cargo clippy --fix --allow-dirty
```

```
cargo fmt
```

## rustfmt, clippyを設定する

自動フォーマットを有効にするための設定を.vscode/settings.jsonに追加する。

```
{
    "[rust]": {
        "editor.defaultFormatter": "rust-lang.rust-analyzer",
        "editor.formatOnSave": true
    }
}
```
