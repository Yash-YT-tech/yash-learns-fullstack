# 📝 Learning Summary: Video, Audio & Media in HTML  
*Sigma Web Dev Tutorial #10*

---

## 🌟 Core Concepts
- HTML provides elements to embed media: **`<video>`**, **`<audio>`**, **`<svg>`**, and **`<iframe>`** for external content.  
- Common attributes: `src`, `controls`, `autoplay`, `loop`, `muted`, `poster`, `width`, `height`, `preload`.

---

## 🎬 The `<video>` Element
- **Purpose:** Embed a video player.  
- **Key Attributes:**  
  - `src` → file path/URL  
  - `controls` → browser playback UI  
  - `autoplay` → start automatically (requires `muted`)  
  - `loop` → restart after ending  
  - `muted` → start silent (needed for autoplay)  
  - `poster` → thumbnail before playback  
  - `width/height` → display size  

💡 **Tip:** Use `autoplay + muted (+ loop)` for reliable auto-play.

---

## 🎵 The `<audio>` Element
- **Purpose:** Embed audio player.  
- **Key Attributes:**  
  - `src` → file path/URL  
  - `controls` → play/pause/volume UI  
  - `autoplay`, `loop`, `muted` → playback settings  
  - `preload` → loading strategy:
    - `none` → don’t fetch ahead  
    - `metadata` → fetch info only (duration, etc.)  
    - `auto` → may preload fully for smoother start  

---

## ⚡ Preload Explained
- `none` → saves bandwidth.  
- `metadata` → quick info only.  
- `auto` → faster playback, more data used.  

---

## 🖼️ SVG for Media Graphics
- Vector format → scales crisply at any resolution.  
- Can be inline or external.  
- Stand-alone SVGs need proper **namespace declaration**.  

---

## 🌍 `<iframe>` for External Content
- Embeds another webpage or app inside the page.  
- Common for YouTube videos → copy “Embed code” from YouTube.  
- Supports parameters (e.g., start time).  

---

## 🛠️ Practical Usage
```html
<!-- Video -->
<video controls autoplay muted loop poster="thumb.jpg" width="640" height="360" src="movie.mp4"></video>

<!-- Audio -->
<audio controls preload="metadata" src="track.mp3"></audio>

<!-- YouTube iframe -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xyz123?start=30" frameborder="0" allowfullscreen></iframe>

✅ Key Takeaways
•	Use controls for playback UI.
•	Combine autoplay + muted for silent auto-start; add loop for continuous playback.
•	Use poster for thumbnails & width/height for stable layouts.
•	Choose preload wisely → none, metadata, or auto.
•	SVG = crisp graphics, resolution-independent.
•	iframe = embed external sites/videos (e.g., YouTube).

---


📂 Project Files 
Click to view the files directly:  
✅ [index.html](./index.html)  
✅ [style.css](./style.css)  
