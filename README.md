### Hello! 👋

- 🚀 Currently, I'm dedicating my efforts as a maintainer for the Strimzi project. Explore more at [Strimzi.io](https://strimzi.io/).
- 📬 Reach out to me via my LinkedIn: [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=LinkedIn&logoColor=white&link=https://www.linkedin.com/in/majkl-orsak/)](https://www.linkedin.com/in/majkl-orsak/).
- 🌐 On a journey of discovery about formal verification methods, always eager to absorb new knowledge and explore rigorous system validations.
- ✍️ Visit my Blog: [see-quick.github.io](https://see-quick.github.io/)

### Latest Blog Posts

| Date       | Title                                                                 | Link                                                           |
|------------|-----------------------------------------------------------------------|----------------------------------------------------------------|
| 2025-03-01 | 12 🚀 Supercharge Your Dev Setup with Neovim, Starship, and WezTerm   | [Read more](https://see-quick.github.io/posts/nvim-sharship-wezterm/) |
| 2024-12-24 | 11 My Advent of Code 2024 Journey                        | [Read more](https://see-quick.github.io/posts/advent-of-code-2024/) |

- 💻 Actively contributing to various interesting open-source projects, always looking for new challenges and collaborations.

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=see-quick&show_icons=true&count_private=true&theme=tokyonight)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=see-quick&theme=tokyonight&layout=compact&langs_count=10)](https://github.com/anuraghazra/github-readme-stats)

```markdown
🛠️ \033[1;34mFormal Verification\033[0m
┌──────────────────────────────────────────────────────┐
│  ∀x, y ∈ S. (x ≠ y) → ¬(P(x) ∧ P(y))                 │  (\033[1;36mUniqueness\033[0m)
│  □(φ → ◇ψ)  →  ¬◇(¬ψ ∧ φ)                            │  (\033[1;36mTemporal Logic\033[0m)
│  ⊢ {P}  Code_Block  {Q}                              │  (\033[1;36mHoare Triple\033[0m)
│                                                      │
│  ✅ \033[1;32mLiveness Example\033[0m                                  │
│  System ⊨ □(Button_Pressed → ◇Light_On)            │  (If the button is pressed, the light will turn on)
│                                                      │
│  🛡️ \033[1;31mSafety Property\033[0m                                │
│  System ⊨ □(¬Bad_State)                            │  (System never reaches an invalid state)
│                                                      │
│  🔄 \033[1;33mMutual Exclusion\033[0m                               │
│  System ⊨ ¬◇(Critical1 ∧ Critical2)                │  (Two processes can’t be critical at once)
│                                                      │
│  📜 \033[1;35mProof:\033[0m                                         │
│   1️⃣ Assume φ holds at time t                      │
│   2️⃣ By transition rules, ◇ψ holds at t+1          │
│   3️⃣ Therefore, □(φ → ◇ψ) is valid                 │
│   4️⃣ Since □(¬Bad_State), no invalid state         │
│   ✅ Q.E.D.                                        │
│                                                      │
│  ⏳ \033[1;34mTemporal Logic Operators\033[0m                         │
│                                                      │
│  1️⃣  □φ (\033[1;32mGlobally\033[0m) - φ holds in all future states │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✔──✔──✔──✔──✔──✔──                     │
│                                                      │
│  2️⃣  ◇φ (\033[1;32mEventually\033[0m) - φ holds at some future state │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✘──✘──✔──✘──✘──✘──                     │
│                                                      │
│  3️⃣  Xφ (\033[1;32mNext\033[0m) - φ holds in the next state         │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✘──✔──✘──✘──✘──✘──                     │
│                                                      │
│  4️⃣  φ U ψ (\033[1;32mUntil\033[0m) - φ holds until ψ holds        │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✔──✔──✔──✘──✘──✘──                     │
│      ψ:    ──✘──✘──✘──✔──✔──✔──                     │
│                                                      │
│  5️⃣  φ W ψ (\033[1;32mWeak Until\033[0m) - φ holds, but ψ may never │
│      Time:  0   1   2   3   4   5                    │
│      φ:    ──✔──✔──✔──✔──✘──✘──                     │
│      ψ:    ──✘──✘──✘──✘──✔──✔──                     │
│                                                      │
└──────────────────────────────────────────────────────┘

Legend:
✔ = True  
✘ = False  
── = Continuation over time  
```

NOTE: Top Languages does not indicate my skill level or anything like that, it's a GitHub metric of which languages have the most code on GitHub. It's a new feature of github-readme-stats.


