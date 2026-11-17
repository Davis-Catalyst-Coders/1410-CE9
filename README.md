# ⚔️ CE9: Shadow Clone Jutsu

Unit 9: Black Magic. Build a `Ninja` class whose clones fuse, power up, compare, and print with overloaded operators. **Instructions are on the Canvas assignment page.**

## 📁 Files

| File | What is in it | What you do |
|---|---|---|
| `Ninja.hpp` | The two constructor declarations | Add the 3 private variables and the 7 operator declarations where the `TO DO`s are |
| `Ninja.cpp` | Empty | Define every function of **5 or more lines** here. Shorter ones may stay in the `.hpp` |
| `main.cpp` | A `main` with a header for each test | Create clones, then test every operator under its header |

- **Do not rename** the files, the class, or the constructors. The autograder calls them by name.
- Names and signatures you add must match the **Program Design** tab **exactly**, case included.
- `<<` and `>>` are **friend** functions. Every other operator is a **member**.
- **No `std::cout` or `std::cin`** inside the class. Only `<<` and `>>` use streams, through their parameters.
- The **only** user input is the `>>` test.

## 🖥️ Compile and Run

```
g++ -o test *.cpp
./test
```

**Compile again after every change.** `./test` runs the last version you compiled.

## 💾 Commit and Sync

Not committed and synced = **not saved**, and not graded.

```
git add .
git commit -m "Describe what you changed"
git push
```

Or use the **Source Control** panel: type a message, **Commit**, then **Sync Changes**.

Commit at the **end of every work session** and before you submit. Commit history is checked for original work.
