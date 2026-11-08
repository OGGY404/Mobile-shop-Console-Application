# 📱 Mobile Shop – C++ Console Application

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![OOP](https://img.shields.io/badge/Concept-OOP-orange?style=flat-square)
![Code::Blocks](https://img.shields.io/badge/IDE-Code%3A%3ABlocks-41AD48?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?style=flat-square&logo=windows&logoColor=white)

A console-based mobile phone shop built in C++ to practise **Object-Oriented Programming**. Users can browse Android and Apple phones, choose a payment method and get a bill saved to a text file. There is also an admin area.

---

## 🧱 OOP Concepts Used

| Concept | Where it is used |
|---|---|
| **Classes and objects** | `welcome`, `device`, `choice`, `message` |
| **Inheritance** | `errormessages` inherits from `message` |
| **Polymorphism** | `errormessages` overrides the `errors()` method |
| **Encapsulation** | Shop logic is grouped inside the `choice` class |

---

## ✨ Features

- 📱 Browse Android and Apple phones
- 💳 Choose a payment method
- 🧾 Bill saved to `my-bill.txt` (file handling)
- 🔐 Admin section
- 🎨 Coloured console output

---

## ▶️ How to Run

**Option 1: Command line**

```bash
cd "OOP C++  Individual project"
g++ main.cpp -o mobileshop
./mobileshop
```

**Option 2: Code::Blocks**

Open the `.cbp` file in [Code::Blocks](https://www.codeblocks.org/) (free) and click **Build and run**.

> **Note:** It uses `windows.h` for the console colours, so it only runs on Windows.

---

## 📝 About

An individual OOP project from my early studies. The product data is written into the code (no database).
