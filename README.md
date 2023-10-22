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
* [2011-2022] *[Lyceum](https://liczej45ulyanovsk-r73.gosweb.gosuslugi.ru/) at [UlTSU](https://ulstu.ru/)*
* [2021-2022] *[Yandex.Lyceum](https://lyceum.yandex.ru/)*
* [2022-2026] *[UlSU](https://ulsu.ru/ru/)* 


### Jobs
Empty for now...

But i've tried to apply:

* **[SMIT](https://smit.studio/)** - *[Tech-task](https://github.com/itc1205/SMIT-tech-task)*
* **[MediaSoft](https://mediasoft.team/)** 
    - *[First tech-task](https://github.com/itc1205/mediasoft_test_task)* 
    - *[Second tech-task](https://github.com/itc1205/mediasoft-part-2)* - (*poorly made*)
    - *[Second tech-task, but improved]()* - I'll upload it soon

### Projects of interest

* [Simbir-go](https://github.com/itc1205/volga-it), a project for [VolgaIT](https://volga-it.org/) olympiad - right now closed, because semi-finals is going
* [My try at engine/shaders development](https://github.com/itc1205/sandbox_game)
* [ShootEmUp](https://github.com/itc1205/idk-gj-project), a game for [Pygame Community Easter Jam](https://itch.io/jam/pygame-community-easter-jam-2023) - [link](https://itc1205.itch.io/shotemup) for itch.io
* [RoboHackaton](https://github.com/itc1205/RoboHackaton), a project for local hackaton at [UlSU](https://ulsu.ru/ru/)


-- Thanks for reading! --