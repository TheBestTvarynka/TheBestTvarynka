```toml
[package]
name = "pavlo-myroniuk"
description = "A software developer from Ukraine"
authors = ["Father", "Mother"]
version = "21.8"
edition = "2001"
licence-file = "https://rm.coe.int/constitution-of-ukraine/168071f58b"

[dependencies]
# primary skills
programming-languages = { version = "0.2.0", features = ["Rust", "JavaScript"] }
databeses = { version = "0.2.0", features = ["PostgreSQL", "Redis"] }
operating-systems = { version = "0.2.0", features = ["Linux", "Windows"] }
cloud = { version = "0.2.0", features = ["GCP"] }
version-control = { version = "0.2.0", features = ["git", "github", "gitlab"] }
dev-ops = { version = "0.2.0", features = ["Docker", "K8s"] }

# other info
languages = { version = "0.2.0", features = ["EN", "UA"] }

[dependencies.contacts]
version = "0.2.0"
mail = "the.best.tvarynka@gmail.com"
telegram = "@TheBestTvarynka"
linkedin = "https://www.linkedin.com/in/thebesttvarynka"
github = "@TheBestTvarynka"
gitlab = "@TheBestTvarynka"
instagram = "@thebesttvarynka"

[dependencies.fun]
version = "0.2.0"
chess = "https://lichess.org/@/TheBestTvarynka"
workout = "calisthenics"

[dev-dependencies]
sleep = "0.8.0"
food = "0.2.0"
```
