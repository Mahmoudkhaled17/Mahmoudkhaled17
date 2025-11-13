<h1 align="center">Hi 👋, I'm Mahmoud Khaled</h1>
<h3 align="center">🌍 GIS & GeoAI Developer | Machine Learning Enthusiast 🚀</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mahmoudkhaled17&label=Profile%20views&color=0e75b6&style=flat" alt="mahmoudkhaled17" />
</p>

---

## 🛰️ GIS & GeoAI — **Primary Focus**
I focus on GIS & Remote Sensing first — combining spatial analysis with AI to build real-world solutions.

**Key GIS skills**
- ArcGIS Pro / ArcGIS Online
- Spatial analysis, Network analysis
- Satellite image preprocessing, NDVI/NDWI, spectral indices
- Raster & vector workflows, Land-use / land-cover classification
- STK mission analysis (space-related simulations)

**Featured GIS projects**
- **Dragsail Simulation** — deployable drag sail for CubeSat deorbiting. 🔗 https://github.com/mahmoudkhaled17/Dragsail-Simulation  
- **Land Cover Classification** — CNN-based satellite classification with spatial post-processing.  
- **Interactive Web Map** — ArcGIS Online dashboard & story map.

---

## 🧠 Machine Learning & AI — (Complementary to GIS)
I use ML/AI to enhance GIS outputs and build predictive systems.

**Key ML/AI skills**
- TensorFlow, PyTorch, Scikit-learn
- Convolutional Neural Networks (satellite imagery)
- GANs for data augmentation
- NLP (DEPI projects) — text analytics & sentiment classification
- MLOps: MLflow, model serving, Azure AI, reproducible pipelines

**Featured ML projects**
- MLflow pipelines & model serving for spatial models  
- Custom CNNs for remote sensing classification  
- GANs to increase labeled data for spatial tasks

---

## 🚀 Experience
- **Machine Learning Intern** — Digital Egypt Pioneers Initiative (DEPI) — ML/DL/NLP & MLOps.  
- **AI Intern** — Elaraby Group — Smart manufacturing.  
- **AI Intern** — NRIAG — Satellite & seismic data analysis.

---

## 🛰️ Final Year Project
**Deployable Drag Sail for Satellite Deorbiting** — simulated a 1.7 m² drag sail for a 3U CubeSat using STK for orbital perturbation analysis.  
🔗 https://github.com/mahmoudkhaled17/Dragsail-Simulation

---

## 🧩 Full Example: HTML / CSS / JS (Demo page for your profile)
> *Note:* GitHub README renders HTML but for full website behaviour (CSS + JS) use **GitHub Pages** (instructions below).  
> The code below is a single-file demo you can paste into `index.html` and publish.

```html
<!-- index.html (demo) -->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Mahmoud Khaled — GIS & GeoAI</title>
  <style>
    :root{--bg:#071021;--card:#0b1220;--accent:#0e75b6;--muted:#94a3b8}
    body{margin:0;font-family:Inter,system-ui,Arial;background:linear-gradient(#071021,#081427);color:#e6eef8}
    .wrap{max-width:1000px;margin:36px auto;padding:20px}
    header{display:flex;gap:16px;align-items:center}
    .avatar{width:90px;height:90px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#4fa6e6);display:flex;align-items:center;justify-content:center;font-weight:700}
    h1{margin:0;font-size:22px} h2{margin:4px 0 0;color:var(--muted)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:20px}
    .card{background:rgba(255,255,255,0.02);padding:16px;border-radius:10px}
    .tabs{display:flex;gap:8px;margin-top:10px}
    .tab{padding:8px 10px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);cursor:pointer}
    .tab.active{border-color:var(--accent);color:var(--accent)}
    @media(max-width:900px){.grid{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar">MK</div>
      <div>
        <h1>Mahmoud Khaled</h1>
        <h2>GIS & GeoAI Developer | Machine Learning Enthusiast</h2>
      </div>
    </header>

    <div class="grid">
      <main>
        <section class="card" id="gis">
          <h3>🌍 GIS (Featured)</h3>
          <p>ArcGIS Pro, Remote Sensing, STK, Network Analysis — primary focus.</p>
          <div class="tabs" role="tablist">
            <button class="tab active" data-target="gis-projects">Projects</button>
            <button class="tab" data-target="gis-tools">Tools</button>
          </div>

          <div id="gis-projects" class="panel" style="margin-top:12px">
            <ul>
              <li><strong>Dragsail Simulation</strong> — CubeSat deorbiting (STK). <a href="https://github.com/mahmoudkhaled17/Dragsail-Simulation" target="_blank">Repo</a></li>
              <li><strong>Land Cover Classification</strong> — CNN + spatial post-processing.</li>
            </ul>
          </div>
        </section>

        <section class="card" id="ml" style="margin-top:14px">
          <h3>🤖 Machine Learning & AI</h3>
          <p>TensorFlow, MLflow, GANs, CNNs for satellite imagery and MLOps pipelines.</p>
        </section>
      </main>

      <aside>
        <div class="card">
          <h4>Contact</h4>
          <p><a href="https://linkedin.com/in/mahmoud-khaled1" target="_blank">LinkedIn</a> • <a href="mailto:mahmoudkhaedl1772001@gmail.com">Email</a></p>
        </div>
      </aside>
    </div>
  </div>

  <script>
    document.querySelectorAll('.tab').forEach(btn=>{
      btn.addEventListener('click', ()=>{
        document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
        btn.classList.add('active');
        // panels (simple) - hide others if needed
        // (demo only)
      });
    });
  </script>
</body>
</html>