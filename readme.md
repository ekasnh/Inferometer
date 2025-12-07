# 🚀 Inferometer
A modern, interactive inference latency measurement tool built as a **single-file web application**. Easily test API endpoints, visualize latency, inspect responses, and simulate mock inference.

> **⚠️ Educational Use Only**  
> This project is created purely for **engineering academic purposes** and is not intended for production deployment.

---

## 🎯 Features
- 📡 **Test inference APIs** with POST/GET support
- ⏱️ **Real-time latency visualization** (animated canvas graph)
- 🧪 **Mock inference engine** when no endpoint is provided
- 🧵 **Multiple calls, repeat mode, configurable delay**
- 📦 **JSON request & headers editor**
- 🔧 **Advanced panel** (Timeout, Repeat, Delay)
- 🔍 **Pretty-printed response viewer**
- 🎨 **Modern UI with gradients, SVG styling, and glass-effect cards**

---

## 🖼️ Modern UI Preview
```svg
<svg width="100%" height="80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0%" stop-color="#7c3aed" />
      <stop offset="100%" stop-color="#4c1d95" />
    </linearGradient>
  </defs>
  <rect x="0" y="0" width="100%" height="80" fill="url(#g1)" rx="12" />
  <text x="50%" y="55%" fill="white" font-size="26" font-family="Inter" text-anchor="middle">Inferometer UI</text>
</svg>
```

---

## 📦 Installation / Usage
### **Option 1 — Download ZIP**
Download the packaged project and open `index.html` in any browser.

### **Option 2 — Deploy Anywhere (Netlify / Vercel / GitHub Pages)**
Since the entire app is a **single file**, you only need to upload `index.html`.

---

## 🧠 How It Works
Inferometer sends an HTTP request to the specified endpoint and collects:
- Latency (ms)
- Response body
- Status
- Aggregated averages
- Graph-based visualization

When no endpoint is specified, the **mock engine** simulates realistic latency between 80–300 ms.

---

## 🎨 Design Elements
### **Buttons**
```html
<button class="cool-btn">Run Inference</button>
```

### **Cool Button CSS**
```css
.cool-btn {
  background: linear-gradient(90deg, #7c3aed, #4c1d95);
  padding: 12px 18px;
  border-radius: 10px;
  color: white;
  font-weight: 600;
  border: none;
  cursor: pointer;
  transition: 0.25s;
}

.cool-btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 20px rgba(124, 58, 237, 0.4);
}
```

---

## 🔧 Project Structure
```
Inferometer/
│── index.html   # Main application
│── README.md    # You're reading it
```

---

## 💡 Educational Notice
This tool is part of an **engineering academic project** and is intended solely for **learning and demonstration purposes**.

---

## 🧑‍💻 Author
**Ekansh Agarwal**  
GitHub: https://github.com/ekasnh

### ⭐ Repository
Follow the project:  
https://github.com/ekasnh/Inferometer

---

## 📝 License
MIT License — Free to modify and learn from.
