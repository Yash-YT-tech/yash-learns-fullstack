# 📝 Learning Summary: IDs and Classes in HTML  
*Sigma Web Dev Tutorial #9*

---

## 🌟 Core Idea
- **ID** → unique identifier for a single element (used once).  
- **Class** → reusable label that can be applied to multiple elements.  
- Both are attributes used for **styling (CSS)** and **scripting (JavaScript)**.

---

## 🎨 How to Use in CSS
- **ID selector:** `#id` → `#first { color: blue; }`  
- **Class selector:** `.class` → `.red { color: red; }`  
- **Specificity:** IDs have **higher priority** than classes if both apply.

---

## 🔹 Multiple Classes vs Single ID
- An element can have **multiple classes** → `class="red bg-yellow"`  
- An element should have **only one unique ID**.  
- IDs should not repeat across different elements in the same page.

---

## 🛠️ Practical Demonstration
- Use **classes** to share styles across multiple elements (less duplication).  
- Use **IDs** for unique cases (e.g., a special card, header, or section).  

---

## 🔗 Linking to Specific Sections (Fragment Identifiers)
- Append `#id` to a URL to jump directly to that element:  
  Example: `page.html#top`  
- Useful for **table of contents, anchors, and deep links**.

---

## ✅ Why This Matters
- Classes → **grouping & reusability**.  
- IDs → **uniqueness & special targeting**.  
- Mixing both wisely keeps code **clean, predictable, and maintainable**.

---

## 📌 Quick Rules of Thumb
- Use **class** for shared styles across many elements.  
- Use **multiple classes** for composable styling.  
- Use **id** for a unique element needing special style, JS targeting, or anchor linking.

---

## 📂 Project/Code Files (Suggested for Practice)
- `index.html` → create multiple elements with classes & one unique ID.  
- `style.css` → test different selectors (`.class` vs `#id`).  
- `anchors.html` → practice in-page navigation with `#id` links.  
