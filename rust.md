The Quicker Rust Reference
==========================

## Types

### Primitive types
- signed integers: `i8` `i16` `i32` `i64` `isize`
- unsigned integers: `u8` `u16` `u32` `u64` `usize`
- floating point: `f32` `f64`
- unicode characters: `char`
- boolean: `bool` (`true` or `false`)
- unit type: `()`

### Other types
* [Tuples](#tuples): `(T1, T2, ...)`
Heterogenous collections of values.
* [Arrays](#arrays): `[T; N]`
Homogenous collections of values. An array is defined by the type of its elements `T` and their number `N`.
* [Slices](#slices): `&[T]`

## String types

`String` is built on `Vec<u8>`.

`&str` is really a `&[u8]`.

Only a `&'static str` can be constructed from a string literal.

But `&str` with another lifetime can be acquired as a reference to `String`:



## Tuples

## Arrays