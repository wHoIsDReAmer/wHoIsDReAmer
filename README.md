# 👋 Hello, I'm Devlcw

Curious of Hacking or Security and Developer, DevOps (will)
so, it's more information of me
```rust

#[derive(Debug)]
struct Me<'a> {
    birth: String,
    name: String,
    tech: Vec<&'a str>,
    favorite_lang: Vec<&'a str>,
}

impl<'a> Default for Me<'a> {
    fn default() -> Self {
        Me {
            birth: "2006-04-03".to_string(),
            name: "LCW".to_string(),
            tech: vec![
                "Bun.js (not main)",
                "Rust",
                "Go (studying.. 60%)",
            ],
            favorite_lang: vec![
                "Rust", "Go", "Javascript", "Typescript", "Java",
            ],
        }
    }
}

fn main() {
    // "I want to study security or hacking more deeply
    // and love low-level languages or system engineering."
    println!("Btw, it's me! {:?}", Me::default());
}

```
