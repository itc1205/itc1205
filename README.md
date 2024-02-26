## Hello, i'm Ivan Aksenov!

*I am a self-study tryhard!*

### My personal block of code

```rust
    #[derive(TellAboutYourself)]
    struct Person<'a> {
        nickname: &'a str,
        favoriteAnimal: &'a str,
        age: i8,
        activities: Vec<&'a str>,
        languages: Vec<&'a str>,
        development_areas: Vec<&'a str>,
        currentChallenge: &'a str,
    };

    fn main() {
        let me = Person {
            nickname: "ItC",
            favoriteAnimal: "Red Panda",
            age: 20,
            activities: vec!["Games", "VC", "Code", "Learn", "Music", "Tech"],
            languages: vec!["Russian/N", "English/B2-B3"],
            development_areas: vec!["Games", "GUI's", "Backend", "A little bit of mobile apps", "Graphical programming"],
            currentChallenge: "[26.02.2024] Git gud at coding!"
        }
        tell_about_yourself!(&me);
    }
```

### Ways to contact with me

* TG: https://t.me/itc1205
* Email: 
    * ivan120536@gmail.com - Personal
* Discord: itc1205


### Education
* [2011-2022] *[Lyceum](https://liczej45ulyanovsk-r73.gosweb.gosuslugi.ru/) at [UlTSU](https://ulstu.ru/)*
* [2021-2022] *[Yandex.Lyceum](https://lyceum.yandex.ru/)*
* [2022-2026] *[UlSU](https://ulsu.ru/ru/)* 


### Projects of interest

* [Simbir-go](https://github.com/itc1205/simbir-go), a python-powered rental service backend for [VolgaIT](https://volga-it.org/) olympiad
* [My try at engine/shaders development](https://github.com/itc1205/sandbox_game)
* [ShootEmUp](https://github.com/itc1205/idk-gj-project), a game for [Pygame Community Easter Jam](https://itch.io/jam/pygame-community-easter-jam-2023) - [link](https://itc1205.itch.io/shotemup) for itch.io
* [RoboHackaton](https://github.com/itc1205/RoboHackaton), a project for local hackaton at [UlSU](https://ulsu.ru/ru/)


-- Thanks for reading! --
