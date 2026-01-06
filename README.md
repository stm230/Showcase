# 🏛️ Pokémon 3D API: Interactive Showcase

This is the official demonstration repository for the [Pokémon 3D API](https://github.com/Pokemon-3D-api). It serves as a real-world example of how to integrate web-optimized 3D assets into a responsive web application using vanilla JavaScript and Google's `<model-viewer>`.

## 🌟 Live Demo
[Link to your GitHub Pages URL here]

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3 (Responsive Grid), Vanilla JavaScript.
- **3D Rendering:** [Google <model-viewer>](https://modelviewer.dev/) (Web Components).
- **Data Source:** [Pokémon 3D API Server](https://github.com/Pokemon-3D-api/api-server) (Merged JSON).
- **Assets:** [Pokémon 3D Assets](https://github.com/Pokemon-3D-api/assets) (.glb models).

---

## 🔬 The Comparison: Optimized vs. Non-Optimized

This showcase provides two distinct experiences to demonstrate the importance of asset pipeline optimization:

### 1. Legacy / Non-Optimized (`index.html`)
- **Source:** Fetches raw data directly from the GitHub repository.
- **Performance:** Higher latency and larger file sizes.
- **Use Case:** Historical reference and testing raw asset fidelity.

### 2. Production / Optimized (`opt.html`)
- **Source:** Fetched via the [Production API Endpoint](https://pokemon-3d-api.onrender.com/v1/pokemon).
- **Performance:** Uses Draco-compressed meshes and WebP textures.
- **Use Case:** Recommended for mobile devices and production-grade applications.

---

## 🚀 Key Features
- **Dynamic Filtering:** Search by Name, ID, Generation (1-9), or Form (Mega, Shiny, G-Max, etc.).
- **Animation Support:** Interactive modal allows users to swap between available animations (Idle, Walk, Attack, etc.) dynamically.
- **Responsive Design:** Fully optimized for mobile, tablet, and desktop viewing.
- **AR Ready:** Built-in Augmented Reality support for compatible mobile browsers.

---

## 📦 How to run locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pokemon-3D-api/showcase.git
   ```

2. **▶️ Open with a Live Server**
Since this project uses JavaScript `fetch`, it **must be served through a local web server** to avoid CORS issues.

Recommended option:
- Use the **Live Server** extension in VS Code.

### 📂 Navigate the Showcase

- **Standard version:** `index.html`  
  Displays the legacy / non-optimized asset pipeline.

- **High-performance version:** `opt.html`  
  Uses the optimized production API with compressed assets.

---

## 🤝 Contributing

If you find a bug or have a suggestion for improving the UI or performance:
- Open an issue
- Or submit a pull request

Contributions are welcome!

---

## ⚖️ Legal Notice

This project is an **unofficial, fan-made resource**.

- Pokémon and Pokémon character names are trademarks of **Nintendo**.
- This project is intended **strictly for educational and non-commercial purposes**.
