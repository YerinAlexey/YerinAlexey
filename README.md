Instead of a thousand words, here's a definition of myself is Rust:

```rust
use internet::{
    fediverse,
    irc,
    email,
};
use world::{
    Person,
    Country,
};
use project::Project;

let me = Person {
    name: "Alexey",
    position: Country::Russia,
    fedi_handle: fediverse::User::from_handle("@yyp@fosstodon.org"),
    email: email::ask(),
    irc_nick: irc::Nick::new("chat.freenode.net", "yyp"),
    skills: vec!["rust", "golang", "linux", "shellscript"],
    
    projects: Project::from_srht("https://sr.ht/~yerinalexey"),
};
```

And below are some of the projects I like/work on:
