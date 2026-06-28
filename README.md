# Calculator-With-History# 🧮 Calculator-With-History

**A calculator that actually remembers what you calculated.**

A simple terminal-based Python calculator that handles all your basic math — but with a twist: every calculation gets logged to a persistent history file, so you can revisit, review, or wipe your past calculations anytime.

---

## ⚡ Why This Exists

Regular calculators forget everything the moment you close them. This one doesn't. Every equation you solve gets saved automatically — so whether you're double-checking last week's math or just curious what you calculated five minutes ago, it's all right there.

---

## 🚀 Features

- ➕➖✖️➗ **Basic arithmetic** — addition, subtraction, multiplication, division
- 📜 **Persistent history** — every calculation is saved to `history.txt`
- 🔁 **View history** anytime with a single command
- 🧹 **Clear history** whenever you want a clean slate
- 🛑 **Safe division** — built-in protection against divide-by-zero errors
- 🔢 **Clean output** — automatically displays whole numbers without unnecessary decimals

---

## 🛠️ Usage

```bash
git clone https://github.com/deepanshu-bisht-dev/Calculator-With-History.git
cd Calculator-With-History
python main.py
```

Once running, just type your calculation in the format:

```
8 + 8
10 * 5
20 / 4
```

**Special commands:**
| Command | What it does |
|---------|--------------|
| `history` | Shows all past calculations (most recent first) |
| `clear` | Wipes the entire calculation history |
| `exit` | Closes the calculator |

---

## 📦 Tech Stack

- **Language:** Python 3
- **Storage:** Plain text file (`history.txt`) — no database needed

---

## 🔮 Future Improvements

- [ ] Support for more operators (exponents, modulo, square root)
- [ ] Timestamp each entry in the history log
- [ ] Add a GUI version using Tkinter
- [ ] Export history as CSV for easy tracking

---

## 🤝 Connect

Found this useful or have ideas to improve it? Feel free to fork, star ⭐, or connect with me on [LinkedIn](#).

---

*Simple math. Smart memory.* 🧮
