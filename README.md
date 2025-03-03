# Video Motion Analysis using Optical Flow  

## 📌 Overview  
This Flask-based web application analyzes object motion in a video using **OpenCV's optical flow** technique. It computes **velocity, acceleration, force, and direction** in real-time while displaying the video feed with overlays.  

## 🚀 Features  
- 📂 **Upload Video** – Supports `.mp4`, `.avi`, and `.mov` formats.  
- 🎥 **Real-time Motion Tracking** – Detects movement using **Lucas-Kanade Optical Flow**.  
- 📊 **Physics Calculations** – Computes **velocity (cm/s)**, **acceleration (cm/s²)**, **force (N)**, and **direction**.  
- 📡 **Live Data Streaming** – Uses **Server-Sent Events (SSE)** to provide real-time updates.  
- 🖥 **Web Interface** – Interactive UI built with **Flask & OpenCV**.  

## 🔧 Installation  
### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/video-motion-analysis.git
cd video-motion-analysis
```
### 2️⃣ Install Dependencies  
Make sure you have Python installed (>=3.7). Then, install the required packages:  
```bash
pip install -r requirements.txt
```


### 3️⃣ Run the Application  
```bash
python app.py
```

Open your browser and go to **http://127.0.0.1:5000/**  

## 📂 Project Structure  
video-motion-analysis/
│── static/             # Folder to store uploaded videos
│── templates/          # HTML templates for Flask
│   ├── index.html      # Main UI for video upload and streaming
│── app.py              # Main Flask application
│── requirements.txt    # Python dependencies
│── README.md           # Project documentation


## 🛠 How It Works  
1️⃣ **Upload a video** via the UI.  
2️⃣ The system extracts frames and initializes **optical flow tracking**.  
3️⃣ It continuously calculates **velocity, acceleration, force, and direction** based on object movement.  
4️⃣ The processed video is streamed back to the user with overlays.  
5️⃣ Data is also sent via **real-time API** using SSE (`/data_feed`).  


🔗 **GitHub Repo:** (https://github.com/Pradesha2005/opencv-)  
📧  Contact:pradesha3112@gmail.com 
