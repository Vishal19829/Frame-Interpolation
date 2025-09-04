# AI Frame Interpolation  

A browser-based **frame interpolation tool** that doubles a video's framerate for buttery-smooth motion. Built entirely with **HTML, Tailwind CSS, and JavaScript**, this project runs 100% client-side — no server required.  

## ✨ Features  
- Upload or drag-and-drop videos (MP4, MOV, WEBM, etc.)  
- Automatic frame extraction and blending  
- Doubles the framerate using pixel averaging interpolation  
- Real-time progress bar and smooth UI (TailwindCSS + custom animations)  
- Secure — all processing happens in your browser, no uploads  

## 🚀 How It Works  
1. **Frame Extraction** – Extracts frames from your uploaded video.  
2. **Blending** – Creates new intermediate frames by averaging pixel values of consecutive frames.  
3. **Reassembly** – Reconstructs a new video with double the framerate.  
4. **Download** – Interpolated video is available instantly in WebM format.  

## 🛠️ Usage  
1. Clone the repository or download `frame_interpolation_ccp.html`.  
2. Open the file directly in your browser (no server needed).  
3. Upload a video and click **Interpolate Video**.  
4. Preview results and download the interpolated video.  

## 📂 File Structure  
repo-name/
│── frame_interpolation_ccp.html # Main project file (HTML, CSS, JS)
│── README.md # Documentation


## 📸 Example  
| Original (30 FPS) | Interpolated (60 FPS) |  
|-------------------|------------------------|  
| ![original](examples/original.gif) | ![interpolated](examples/interpolated.gif) |  

## 📜 License  
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.  
