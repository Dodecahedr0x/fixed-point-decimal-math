# Fixed Point Decimal Math

This library facilitates decimals fixed point mathematical operations in [Solana](https://solana.com/) programs using the [Anchor Framework](https://www.anchor-lang.com/).

Unlike [fixed](https://docs.rs/fixed/latest/fixed/), which uses some bits of the integer type to represent the decimal part, this library considers the decimal part as a base-10 integer.