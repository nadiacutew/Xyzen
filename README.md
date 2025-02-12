# xyzen  

**Xyzen** is a powerful Node.js module that provides over **250 colors**, including **neon colors**, **bold text**, and **text animations** for stylish terminal output.  

## 🚀 Features  
- 🎨 **50+ Basic Colors** (including background colors)  
- 🌈 **200 Neon Colors** from ANSI 256-color palette  
- 🔥 **Bold Text Support** (`.bold()`)  
- ⚡ **Text Animation Effect** (`blink()`)  

## </> Code
const xyzen = require('xyzen');

console.log(xyzen.red('Hello, World!'));
console.log(xyzen.blue.bold('Bold Blue Text'));
console.log(xyzen.bgGreen('Green Background'));
console.log(xyzen.neonblue.bold('Xyzen Ganteng'));

## 📦 Installation  
```sh
npm install xyzen

yarn add xyzen
