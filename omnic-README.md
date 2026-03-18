# Omnic 🌐

> An AI-powered compiler that auto-detects programming languages, compiles without headers, and enables seamless cross-language variable sharing.

**Status:** 🚧 Early Development (Learning Phase)

---

## 🎯 Vision

Imagine writing code in Python, Rust, C++, and JavaScript — all in the **same file** — without worrying about:
- Manual language detection
- Writing headers or imports
- FFI boilerplate for sharing data
- Complex build systems

**Omnic** makes this possible using AI to understand your code and a unified runtime to execute it.

---

## ✨ Features (Planned)

| Feature | Description | Status |
|---------|-------------|--------|
| 🤖 **AI Language Detection** | Automatically identifies which language each code block is written in | 🔴 Not Started |
| 📦 **Headerless Compilation** | Compiles code without explicit imports/headers | 🔴 Not Started |
| 🔗 **Cross-Language Variables** | Share variables and logic between languages seamlessly | 🔴 Not Started |
| ⚡ **Unified Runtime** | Execute multiple languages together efficiently | 🔴 Not Started |
| 🛠️ **Multi-Language Support** | Python, JavaScript, C/C++, Rust, Go, and more | 🔴 Not Started |

---

## 🚀 Quick Start (Future)

```bash
# Install Omnic
pip install omnic

# Compile a polyglot file
omnic compile main.poly

# Run it
omnic run main
```

**Example `main.poly`:**
```poly
# Python - Auto detected
x = 5
y = [1, 2, 3]

# JavaScript - Auto detected
function add(a, b) {
    return a + b;
}

# Rust - Auto detected
#[export]
fn compute(data: &[i32]) -> i32 {
    data.iter().sum()
}

# Back to Python
result = compute(y)
print(add(result, x))  # Output: 11
```

---

## 🗺️ Roadmap

### Phase 1: Foundation (Current)
- [ ] Learn Python programming
- [ ] Learn compiler fundamentals
- [ ] Build simple language detector
- [ ] Design Unified IR (Intermediate Representation)

### Phase 2: Single Language Support
- [ ] Python parser → UIR → Python bytecode
- [ ] Auto-import detection
- [ ] Basic compilation without headers

### Phase 3: Cross-Language Interop
- [ ] Add C/Rust support
- [ ] Shared memory manager
- [ ] FFI bridge implementation
- [ ] Cross-language function calls

### Phase 4: Multi-Language & Optimization
- [ ] JavaScript/TypeScript support
- [ ] Unified runtime
- [ ] Performance optimization
- [ ] Production-ready release

---

## 🛠️ Tech Stack (Planned)

- **Core:** Rust (performance, LLVM integration)
- **Parsers:** tree-sitter, rustpython-parser
- **ML:** ONNX Runtime or Candle (Rust ML)
- **Code Generation:** LLVM (via Inkwell)
- **Runtime:** Custom shared memory + FFI bridge

---

## 🤝 Contributing

This is an **open-source learning project**. Whether you're a beginner or expert, you're welcome to contribute!

### How to Contribute

1. **Star** this repo to show support
2. **Open issues** for ideas, bugs, or questions
3. **Submit PRs** for code, docs, or tests
4. **Share** this project with others

### Learning Together

- 💡 Have an idea? Open an issue!
- 🐛 Found a bug? Report it!
- 📚 Want to learn compilers? Join the discussion!
- 🔧 Want to code? Check out [good first issues](../../issues)

---

## 📚 Resources

### Learning Path
1. **Python Programming** - [Automate the Boring Stuff](https://automatetheboringstuff.com/)
2. **Compiler Basics** - [Crafting Interpreters](https://craftinginterpreters.com/)
3. **CS Fundamentals** - [CS50](https://cs50.harvard.edu/x/)
4. **ML for Code** - Research papers on code classification

### Inspiration
- [GraalVM](https://www.graalvm.org/) - Polyglot runtime
- [WebAssembly](https://webassembly.org/) - Portable compilation target
- [tree-sitter](https://tree-sitter.github.io/tree-sitter/) - Parser generator

---

## 🎯 Why This Project?

Modern software development often requires using multiple languages:
- **Python** for ML/data science
- **Rust/C++** for performance-critical code
- **JavaScript** for web frontends
- **Go** for cloud services

Currently, integrating these requires:
- Complex build systems
- Manual FFI bindings
- Header files and boilerplate
- Separate compilation steps

**Omnic aims to eliminate this friction.**

---

## 📄 License

[MIT License](LICENSE) - Free to use, modify, and distribute.

---

## 🙏 Acknowledgments

- Built with passion by [Seju Vaibhav](https://github.com/vaibhavseju221207)
- Inspired by the open-source community
- Learning in public

---

## 📬 Contact

- **GitHub Issues:** For bugs and feature requests
- **Discussions:** For questions and ideas

---

> **Note:** This project is in early development. The architecture and features are subject to change as we learn and iterate. Join us on this journey! 🚀
