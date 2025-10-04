# 🃏 Blackjack Game (C++ Console Version)

A simple yet complete **Blackjack game** built using **Object-Oriented Programming (OOP)** principles in **C++**.  
This project simulates the classic casino card game, letting you play against a computer-controlled dealer in the terminal.

---

## 🎯 Features

- 🂡 Fully functional Blackjack game logic  
- ♣️ 52-card deck with random shuffling  
- 🧠 Smart ace-handling logic (Ace can count as 1 or 11)  
- 💥 Player and Dealer turns with hit/stand options  
- 🧩 Clean modular design using structs, enums, and helper functions  
- 🧾 Simple and clear console interface  

---

## 🛠️ Technologies Used

- **C++17 or later**
- Standard Template Library (**STL**)
- `<array>`, `<vector>`, `<algorithm>`, `<random>`, `<cassert>`

---

## 🚀 How to Run

### 🧩 1. Clone the repository
```bash
git clone https://github.com/<your-username>/blackjack-cpp.git
cd blackjack-cpp
```

### ⚙️ 2. Compile the program
Using **g++**:
```bash
g++ main.cpp -o blackjack
```

Or using **clang++**:
```bash
clang++ main.cpp -o blackjack
```

### ▶️ 3. Run the game
```bash
./blackjack
```

---

## 🎮 How to Play

1. At the start, both **you** and the **dealer** are dealt two cards.  
2. Your goal is to get as close to **21** as possible **without going over**.  
3. You can choose to:
   - **Hit (y)** → Draw another card  
   - **Stand (n)** → End your turn and let the dealer play  
4. The dealer must hit until their score reaches **17 or more**.  
5. The winner is decided based on who has the higher score without exceeding **21**.

---

## 🧠 Rules Recap

| Card | Value |
|------|--------|
| 2–10 | Face value |
| J, Q, K | 10 |
| A | 11 (or 1 if total exceeds 21) |

---

## 🧩 Example Gameplay

```
You got a: 10C
And a: 8H
Your total score is: 18

Dealer got a: 7S
Dealer's score is: 7

Do you want to hit or stand? (y/n): n

Dealer got a: 9D
Dealer's score is: 16
Dealer got a: 6H
Dealer's score is: 22

Dealer busted! You win 😎
```

---

## 🧱 Project Structure

```
📁 blackjack-cpp
│
├── main.cpp        # Main game code
├── README.md       # Project documentation (this file)
└── .gitignore      # Optional (ignore compiled files)
```

---

## 🧰 Concepts Practiced

- Object-Oriented Design  
- Enumerations and Structs  
- Function decomposition  
- Random number generation  
- Input handling and validation  
- Code organization and readability  

---

## ✨ Future Improvements

- 🖼️ Add graphical version using **SFML**  
- 🎵 Add sound effects and animations  
- 💾 Track win/loss statistics  
- 🔁 Support multiple rounds  
- 🧍‍♂️ Add multiplayer mode  

---

## 🤝 Contributing

Pull requests are welcome!  
If you'd like to improve the game logic, UI, or structure — feel free to fork the repo and submit your ideas.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 💡 Author

**[0xSubhan]**  
📧 [sksubhanahmed0321@gmail.com]  
🌐 [https://github.com/0xSubhan](https://github.com/0xSubhan)

---
⭐ If you like this project, don’t forget to **star the repo** on GitHub!
