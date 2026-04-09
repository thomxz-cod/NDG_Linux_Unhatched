# Regular Expressions

Regular expressions have two common forms: **basic** and **extended**.

Most commands that use regular expressions can interpret **basic regular expressions**. However, **extended regular expressions** are not available for all commands and typically require a specific option to work correctly.

---

## 🔹 Basic Regular Expressions

The following table summarizes basic regular expression characters:

| Character(s) | Meaning |
|-------------|--------|
| `.` | Any one single character |
| `[ ]` | Any one specified character |
| `[^ ]` | Not the specified character |
| `*` | Zero or more of the previous character |
| `^` | If first character, match must be at the beginning of the line; otherwise literal `^` |
| `$` | If last character, match must be at the end of the line; otherwise literal `$` |

---

## 🔹 Extended Regular Expressions

These must be used with the `egrep` command or the `-E` option with the `grep` command.

| Character(s) | Meaning |
|-------------|--------|
| `+` | One or more of the previous pattern |
| `?` | The preceding pattern is optional |
| `{ }` | Specify minimum, maximum, or exact matches of the previous pattern |
| `\|` | Alternation (logical **OR**) |
| `( )` | Used to create groups |
