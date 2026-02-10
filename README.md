# 📐 SUSAN Corner Analysis

A classical **computer vision** project that detects **corners, edges, and homogeneous regions** using the **SUSAN corner detector** combined with **automatic thresholding via the Convex Hull algorithm**.

No deep learning. Just algorithms doing real work 🧠

---

## ✨ What I built
- Implemented **SUSAN Corner Detection** from scratch
- Generated **corner response images** and histograms
- Applied **Convex Hull–based automatic threshold detection**
- Extracted **two thresholds** to separate image regions
- Split the image into:
  - 🟢 Homogeneous regions  
  - 🟡 Edges  
  - 🔴 Corners  

---

## 🧠 How it works (quickly)
1. Apply **SUSAN** to compute corner likelihood scores  
2. Build a **histogram** of the SUSAN response  
3. Use the **Convex Hull algorithm** to automatically find thresholds  
4. Segment the image into **three regions** based on these thresholds  

---

## 🛠️ Tech used
- Python  
- NumPy  
- Matplotlib  
- Pillow / OpenCV  

---

## 🎯 Output
- SUSAN response image  
- Histogram of scores  
- Three output images:
  - corners only  
  - edges only  
  - homogeneous regions  

---

Classic feature detection. Smart thresholding. Clean results. 🚀
