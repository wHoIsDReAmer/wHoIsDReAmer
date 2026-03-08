# 👋 Hello, I'm DevLCW

Curious about Hacking or Security and Developer, DevOps
so, it's more information of me
```rust

#[derive(Debug)]
struct Me<'a> {
    name: String,
    tech: Vec<&'a str>,
    favorite_lang: Vec<&'a str>,
}

impl<'a> Default for Me<'a> {
    fn default() -> Self {
        Me {
            name: "LCW".to_string(),
            tech: vec![
                "Javascript",
                "Typescript",
                "Rust",
                "Go",
                "C++",
            ],
            favorite_lang: vec![
                "C++", "Rust", "Go", "Javascript", "Typescript"
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
