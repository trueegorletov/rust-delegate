# 0.5.1 (6. 1. 2021)
- fix breaking change caused by using `syn` private API (https://github.com/chancancode/rust-delegate/issues/28) 

# 0.5.0 (16. 11. 2020)
- `self` can now be used as the delegation target
- Rust 1.46 introduced a change that makes it a bit difficult to use `rust-delegate` implementations
generated by macros. If you have this use case, please use [this workaround](https://github.com/chancancode/rust-delegate/issues/25#issuecomment-716774685).