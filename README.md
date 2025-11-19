<h1 align="center">🛳️ Oil Spill & Vessel Anomaly Detection in Marine Environment (AIS)</h1>

<p align="center">
  <b>AI + AIS + Satellite Data • YOLOv8 • HTML • JavaScript</b><br>
  Complete Maritime Monitoring & Detection Web App
</p>

<hr>

<h2>🌐 Live Demo</h2>

<p>
  👉 <a href="https://ganeshkumarseepana.github.io/OilSpill_Detection/" target="_blank">
      <b>Click Here to View Live Project</b>
  </a>
</p>

<hr>

<h2>🚀 Built With</h2>
<ul>
  <li><b>HTML5 / CSS3</b> – Frontend UI</li>
  <li><b>JavaScript</b> – Dynamic Image Loading</li>
  <li><b>YOLOv8</b> – Oil Spill Detection</li>
  <li><b>AIS Dataset</b> – Vessel Anomaly Analysis</li>
  <li><b>GitHub Pages</b> – Deployment</li>
</ul>

<hr>

<h2>✨ Features</h2>

<h3>🛑 Vessel Anomaly Detection</h3>
<ul>
  <li>Displays MMSI, Coordinates, COG, SOG, Vessel Type, Draft</li>
  <li>Static HTML table with anomaly records</li>
  <li>No backend required</li>
</ul>

<h3>🛢 Oil Spill Detection (Satellite Images)</h3>
<ul>
  <li>Auto-loaded images from <code>images/</code> folder</li>
  <li>Hover zoom effect (CSS)</li>
  <li>Supports 1.png, 2.png, 3.png…</li>
</ul>

<h3>🤖 YOLOv8 Oil Spill Detection</h3>
<ul>
  <li>Loads up to 50 images dynamically</li>
  <li>Supports .png / .jpg / .jpeg</li>
  <li>Only displays existing images</li>
</ul>

<h3>📊 Navigation Dashboard</h3>
<ul>
  <li>Clickable Boxes</li>
  <li>Detected Anomalies</li>
  <li>Oil Spills</li>
  <li>YOLOv8 Results</li>
</ul>

<hr>

<h2>🗂 Project Structure</h2>

<pre>
📦 OilSpill_Detection
│
├── index.html                 # Main Dashboard
├── anomalies.html             # AIS anomaly table
├── oil_spills.html            # Oil spill gallery
├── oilspills_yolov8.html      # YOLOv8 image gallery
│
├── images/                    # Oil spill images
├── imagesyolov8/              # YOLOv8 images
│
└── README.md
</pre>

<hr>

<h2>🧠 How It Works</h2>

<h3>1️⃣ Vessel Anomaly Detection</h3>
<p>
AIS data is preprocessed → anomaly rows exported → displayed as a table in <code>anomalies.html</code>.
</p>

<h3>2️⃣ Oil Spill Detection (Satellite)</h3>
<p>
Model processes images → prediction outputs saved → JavaScript loads them dynamically.
</p>

<h3>3️⃣ YOLOv8 Oil Spill Detection</h3>
<p>
Inference output images saved in <code>imagesyolov8/</code> → script auto-loads them into the gallery.
</p>

<hr>

<h2>📥 Local Setup</h2>

<p>No installation required. Just open:</p>

<pre>index.html</pre>

Everything loads offline.

<hr>

<h2>📌 Deployment</h2>

<ol>
  <li>Go to <b>Settings → Pages</b></li>
  <li>Choose <b>Deploy from Branch</b></li>
  <li>Select <b>main</b> and <b>/(root)</b></li>
  <li>Save & wait for deployment</li>
</ol>

<p>Your site will appear at:</p>

<pre>https://ganeshkumarseepana.github.io/OilSpill_Detection/</pre>

<hr>

<h2>🙌 Author</h2>

<p>
<b>Ganesh Kumar S</b><br>
AI & ML Engineer
</p>
