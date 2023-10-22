## Hello, i'm Ivan Aksenov!

*Self-study software engineer, who loves to create art with code*

### My personal block of code

```rust
    #[derive(TellAboutYourself)]
    struct Person<'a> {
        nickname: &'a str,
        favoriteAnimal: &'a str,
        age: i8,
        activities: Vec<&'a str>,
        languages: Vec<&'a str>,
        code: Vec<&'a str>,
        currentChallenge: &'a str,
    };

    fn main() {
        let me = Person {
            nickname: "ItC",
            favoriteAnimal: "Red Panda",
            age: 19,
            activities: vec!["Games", "VC", "Code", "Learn", "Music", "Tech"],
            languages: vec!["Russian/N", "English/B2-B3"],
            code: vec!["Python", "Rust", "C/C++", "GLSL", "Flutter"],
            currentChallenge: "[20.10.2023] Be a study tryhard for 100 days!"
        }
        tell_about_yourself!(&me);
    }
```

### Education

* [2021-2022] *[Yandex.Lyceum](https://lyceum.yandex.ru/)*
* [2022-2026] *[UlSU](https://ulsu.ru/ru/)* 


### Jobs
* Empty for now...