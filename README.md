# Pocket os

It is pet project to educate how create OS in Rust.

## Commands

```bash
cargo build --target thumbv7em-none-eabihf
```

```bash
cargo rustc -- -C link-args="-e __start -static -nostartfiles"
```

```bash
qemu-system-x86_64 -drive format=raw,file=target/x86_64-blog_os/debug/bootimage-blog_os.bin
```

## Links

- [Blogs os](https://os.phil-opp.com/)