### Hello! <img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" width="30"/> 
<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="350" align="right"/>

- <img src="https://user-images.githubusercontent.com/74038190/216656967-625b2a52-e638-4c21-a8ae-180560386f96.gif" width="40"/> **Currently**, I'm dedicating my efforts as a maintainer for the [Strimzi](https://strimzi.io/) project.
- <img src="https://user-images.githubusercontent.com/74038190/235294012-0a55e343-37ad-4b0f-924f-c8431d9d2483.gif" width="25"/> **Reach out** via [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/majkl-orsak/)
- <img src="https://user-images.githubusercontent.com/74038190/216656971-9a208a88-e6ad-4b7a-88eb-c410e4cf0e00.gif" width="40"/> **Exploring** formal verification methods and system validation.
- <img src="https://user-images.githubusercontent.com/74038190/216122003-1c7d9078-357a-47f5-81c7-1c4f2552e143.png" width="25"/> **Blog:** [see-quick.github.io](https://see-quick.github.io/)
### Latest Blog Posts

| Date       | Title                                                                 | Link                                                           |
|------------|-----------------------------------------------------------------------|----------------------------------------------------------------|
| 2025-03-29 | 14 🔍 Safety in Formal Verification: Nothing Bad Ever Happens         | [Read more](https://see-quick.github.io/posts/safety/) |
| 2025-03-22 | 13 🐞 Formal Verification 101: What, Why, and How                     | [Read more](https://see-quick.github.io/posts/formal-verification-101/) |
| 2025-03-01 | 12 🚀 Supercharge Your Dev Setup with Neovim, Starship, and WezTerm   | [Read more](https://see-quick.github.io/posts/nvim-sharship-wezterm/) |
| 2024-12-24 | 11 My Advent of Code 2024 Journey                                     | [Read more](https://see-quick.github.io/posts/advent-of-code-2024/) |

- 💻 Actively contributing to various interesting open-source projects, always looking for new challenges and collaborations.

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=see-quick&show_icons=true&count_private=true&theme=tokyonight)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=see-quick&theme=tokyonight&layout=compact&langs_count=10)](https://github.com/anuraghazra/github-readme-stats)

```markdown
🛠️ Formal Verification
┌──────────────────────────────────────────────────────┐
│  ∀x, y ∈ S. (x ≠ y) → ¬(P(x) ∧ P(y))                 │  (Uniqueness)
│  □(φ → ◇ψ)  →  ¬◇(¬ψ ∧ φ)                            │  (Temporal Logic)
│  ⊢ {P}  Code_Block  {Q}                              │  (Hoare Triple)
│                                                      │
│  ✅ Liveness Example                                 │
│  System ⊨ □(Button_Pressed → ◇Light_On)              │  (If the button is pressed, the light will turn on)
│                                                      │
│  🛡️ Safety Property                                  │
│  System ⊨ □(¬Bad_State)                              │  (System never reaches an invalid state)
│                                                      │
│  🔄 Mutual Exclusion                                 │
│  System ⊨ ¬◇(Critical1 ∧ Critical2)                  │  (Two processes can’t be critical at once)
│                                                      │
│  📜 Proof:                                           │
│   1️⃣ Assume φ holds at time t                        │
│   2️⃣ By transition rules, ◇ψ holds at t+1            │
│   3️⃣ Therefore, □(φ → ◇ψ) is valid                   │
│   4️⃣ Since □(¬Bad_State), no invalid state           │
│   ✅ Q.E.D.                                          │
│                                                      │
│  ⏳ Temporal Logic Operators                         │
│                                                      │
│  1️⃣  □φ (Globally) - φ holds in all future states    │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✔──✔──✔──✔──✔──✔──                      │
│                                                      │
│  2️⃣  ◇φ (Eventually) - φ holds at some future state  │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✘──✘──✔──✘──✘──✘──                      │
│                                                      │
│  3️⃣  ◯φ (Next) - φ holds in the next state           │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✘──✔──✘──✘──✘──✘──                      │
│                                                      │
│  4️⃣  φ U ψ (Until) - φ holds until ψ holds           │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✔──✔──✔──✘──✘──✘──                      │
│      ψ:    ──✘──✘──✘──✔──✔──✔──                      │
│                                                      │
│  5️⃣  φ W ψ (Weak Until) - φ holds, but ψ may never   │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✔──✔──✔──✔──✘──✘──                      │
│      ψ:    ──✘──✘──✘──✘──✔──✔──                      │
│                                                      │
└──────────────────────────────────────────────────────┘

Legend:
✔ = True  
✘ = False  
── = Continuation over time  
```

NOTE: Top Languages does not indicate my skill level or anything like that, it's a GitHub metric of which languages have the most code on GitHub. It's a new feature of github-readme-stats.


