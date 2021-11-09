# rust-simple-web-server

Rust で作るシンプルな Web サーバーです

```console
cargo run
```

http://localhost:7878/ でアクセスできます。3 リクエストを受け取るとサーバーを終了します。

```console
   Compiling hello v0.1.0 (/.../rust-simple-web-server)
    Finished dev [unoptimized + debuginfo] target(s) in 0.55s
     Running `target/debug/main`
Sending terminate message to all workers.
Shutting down all workers
Shutting down worker 0
Worker 0 got a job; executing.
Worker 3 was told to terminate.
Worker 1 got a job; executing.
Worker 2 was told to terminate.
Worker 1 was told to terminate.
Worker 0 was told to terminate.
Shutting down worker 1
Shutting down worker 2
Shutting down worker 3
```
