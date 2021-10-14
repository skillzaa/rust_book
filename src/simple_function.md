# Simple Function

Rust is strongly typed. Strong typing means that functions clearly express the types you’re allowed to pass to them. 
The program fails to compile if you’re trying to pass a type that’s not compatible. However during run time all the types are removed so there is no run time penalty for having more types in rust.

```rust

fn main() {
let no1:u16 = 33;
let no2:u16 = 3433;
let result = add(no1, no2);
println!("the result is :: {}",result);
}// main ends here

fn add(no1:u16,no2:u16)->u16{
    no1 + no2
}
```