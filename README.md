# SyntaX (for C#) 🚀

**SyntaX** is a lightweight, easy-to-use utility library designed to bring the **simplicity of Python's syntax** to the **C# / .NET Ecosystem**.

Are you tired of C#'s verbose boilerplate code like `Console.WriteLine` or complex `Random` object instantiations just to get a simple result? **SyntaX** allows you to write cleaner, more readable code. It serves as a versatile tool for developers who want to focus on logic rather than syntax.

---

## 🌟 Key Features

* **Python-like Syntax:** Familiar functions like `print()`, `input()`, and `randint()`.
* **Static Import Support:** Use functions directly without class prefixes thanks to C# `using static` directives.
* **Zero Dependencies:** Built entirely on the standard .NET `System` libraries.
* **Optimized I/O:** Simplified console handling with built-in support for multiple arguments in `print()`.
* **Human-Readable Math:** Simplified factorial, power, and square root functions.

---

## 🛠️ Usage & Examples

To keep this documentation clean, we have provided a dedicated example file. You can find comprehensive usage examples covering:

* **Simplified I/O** (print and input with optional prompts)
* **File Operations** (read_file and write_file using System.IO)
* **Logic & Math Helpers** (randint, square_root, factorial)
* **System Utilities** (clear screen and sleep)

👉 **Check out [samples.cs](./samples.cs) for ready-to-use code snippets!**

---

## 📂 Installation

1. Download the **bettersyntax.cs** file.
2. Place it in your project's directory.
3. Ensure the file is included in your project (VS Code or Visual Studio will detect it).
4. For the cleanest experience, add **`using static bettersyntax.SyntaX;`** at the top of your code to start coding like Python!

---

## 🚀 Advanced Installation (System-wide)

If you want to use **SyntaX** across multiple projects:

1. Compile the library into a **DLL**: `csc /target:library bettersyntax.cs`
2. Reference the `bettersyntax.dll` in your other .NET projects.
3. Use the namespace to access all features globally!

---

## 💻 Technical Details

The library is wrapped in the `bettersyntax` namespace and utilizes a `static class` structure. By using the `params object[]` keyword in the `print()` function, SyntaX allows for an unlimited number of arguments of any type, mirroring Python's flexible output system while maintaining C#'s type safety.

---

## Development Comparison

| Feature | Standard C# (Vanilla) | **SyntaX for C#** (`bettersyntax`) |
| :--- | :--- | :--- |
| **Output** | `Console.WriteLine(x + " " + y);` | `print(x, y);` |
| **User Input** | `string s = Console.ReadLine();` | `string s = input("Name: ");` |
| **Random Number** | `new Random().Next(min, max + 1);` | `randint(min, max);` |
| **Sleep/Wait** | `Thread.Sleep(1000);` | `sleep(1.0);` |
| **File Reading** | `File.ReadAllText("data.txt");` | `read_file("data.txt");` |
| **List Search** | `list.Contains(element);` | `contains(list, element);` |
| **Math (Factorial)** | *(Requires manual loop or recursion)* | `factorial(n);` |
| **Clear Screen** | `Console.Clear();` | `clear();` |

---

### 👨‍💻 Programmer
**hypernova-developer**
