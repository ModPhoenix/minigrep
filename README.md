# An I/O Project: Building a Command Line Program

Clone grep form The Rust Programming Language book, chapter 12.

## How use?

This tool works only for utf-8 contents.

### Case sensitive search

```shell
cargo run to poem.txt
```

### Case insensitive search

For case insensitive search you need to set environment variable `CASE_INSENSITIVE` to any value.

```shell
CASE_INSENSITIVE=1 cargo run to poem.txt
```
