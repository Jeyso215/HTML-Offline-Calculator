Here's a detailed **README.md** file for your calculator project, emphasizing its use of local AI and **[bolt.diy](https://github.com/stackblitz-labs/bolt.diy)**.

---

## 📊 AI-Powered Scientific Calculator with Graphing

This is a fully **local AI-powered** **scientific calculator with graphing** capabilities, built using **[bolt.diy](https://github.com/stackblitz-labs/bolt.diy)**. The calculator provides **advanced mathematical functions**, **graph plotting in multiple modes (Cartesian, Polar, and Parametric)**, and **memory storage features** while maintaining a sleek, user-friendly interface.

⚡ **No external dependencies**—This project runs completely offline, making it **fast, private, and secure**.

---

## 🚀 Features

✅ **Scientific Calculator**  
- Supports basic operations (`+`, `-`, `×`, `÷`)  
- Advanced functions: `sin`, `cos`, `tan`, `log`, `ln`, `π`, `√`, `^` (exponentiation)  
- Hyperbolic functions: `sinh`, `cosh`, `tanh`  
- Memory storage (`M+`, `M-`, `MR`, `MC`)  
- Supports **parentheses** for complex calculations  

✅ **Graphing Calculator**  
- **Three graphing modes**:  
  - 📈 **Cartesian** (y = f(x))  
  - 🌀 **Polar** (r = f(θ))  
  - 🔄 **Parametric** (x = f(t), y = g(t))  
- Uses **Plotly.js** for interactive graph rendering  
- Input mathematical functions dynamically  
- **Toggle graphing mode** from the calculator interface  

✅ **Dark Mode & Responsive UI**  
- Optimized for both **desktop** and **mobile**  
- **Modern, minimalistic UI** with intuitive controls  

---

## 📌 Installation & Usage

This project is built to be **self-hosted** and does not require an internet connection after setup.

### **Option 1: Run Locally (Recommended)**
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB/calculator.git
   cd calculator
   ```
2. Open `calculator.html` in a web browser.
3. **Done!** You can now use the calculator locally.

### **Option 2: Host on Local Server**
If you want to run it on a **local server**, use:
```bash
python -m http.server 8080
```
Then, open your browser and visit `http://localhost:8080/calculator.html`.

---

## 🛠 Built With
- **[bolt.diy](https://github.com/stackblitz-labs/bolt.diy)** (for local AI execution)
- **HTML, CSS, JavaScript**
- **Plotly.js** (for graphing functionality)

---

## 📜 License
This project is open-source under the **MIT License**.

---

## 👤 Author
Developed by **Sam Bent**. If you found this useful, consider contributing or ⭐ starring the repo!
