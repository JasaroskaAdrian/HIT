# Rust Tipps & Tricks

## Glossary (Q/A)

### General Rust Knowledge
| Question           | Answer                                           |
| ------------------ | ------------------------------------------------ |
| What are Crates?   | In Rust, we often refer to packages as “crates.” |
| What is crates.io? | Crates.io is the package Registry for Rust       |

### Rust Functions
| Question           | Answer                                           |
| ------------------ | ------------------------------------------------ |
| mut                | &mut means that the value of this Variable may change, otherwise Variables are Read-only (just like final or readonly in other languages) |
| .unwrap()          | If it's an error or empty, crash. Otherwise give me the value. |
| &variable_name     | In Rust a Variable has only one Owner, therefore if you pass a variable without & to a function, that function takes ownership of that variable and that variable isnt accessible anymore outside of the function. Similar to Cut/Pasting a Folder |