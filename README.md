# Hogarth Technical Test

A web project demonstrating responsive design and cross-browser compatibility solutions.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Browser Compatibility Report](#browser-compatibility-report)
- [Solution](#solution)
- [Project Structure](#project-structure)

## 🌟 Project Overview

This project implements a responsive web design with focus on cross-browser compatibility, particularly addressing Internet Explorer limitations.

## 🔍 Browser Compatibility Report

### Task 3: Internet Explorer Compatibility Issues

#### CSS Grid Issues
- **`grid-column` property**: ❌ Not supported in Internet Explorer
  - Used on gallery-photo elements
  - 📚 [Browser Support Reference](https://caniuse.com/?search=grid-column)

- **`grid-template-columns` property**: ⚠️ Partially supported in Internet Explorer
  - Used on gallery-grid element
  - 📚 [Browser Support Reference](https://caniuse.com/?search=grid-template-columns)

#### Flexbox Issues
- **Flexbox support**: ⚠️ Limited support with known bugs in Internet Explorer
  - 🐛 [Known Issues Discussion](https://stackoverflow.com/questions/43979702/display-flex-not-working-on-internet-explorer/43979973)
  - 📚 [Browser Support Reference](https://caniuse.com/?search=flex)

## 💡 Solution

### Recommended Approach: HTML Tables

**Why tables are a good alternative:**
- ✅ **Grid-like layout**: Can mimic CSS Grid behavior using rows and columns
- ✅ **Intuitive structure**: Natural tabular data representation
- ✅ **Wide browser support**: Compatible with legacy browsers including Internet Explorer
- ✅ **Reliable rendering**: Consistent behavior across different browser versions

