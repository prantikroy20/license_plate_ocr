🔍💥 YOLOv8 License Plate Detector 🔥📸
Ever seen a shady car and thought, “Yo what’s that plate say?” — well, now you can find out yourself 😎

This bad boy project uses YOLOv8 + EasyOCR to detect & read license plates from images 📷. Whether it's for fun, security, or just flexing your AI skills, this project gotchu 💯

⚙️ What It Does
🧠 Trained a YOLOv8 model using Roboflow dataset

🔎 Detects number plates from real-world car images

🔤 Reads text from plates using EasyOCR

🧪 Tested on juicy real-life news images (like cars outside Taj Hotel 🚗🔥)

🧰 Tech Stack
🔧 Tool	💬 What It Do
YOLOv8	Detects the plate like a sniper 🎯
EasyOCR	Reads the text on the plate 👁️🔤
Roboflow	Source of our dope dataset 🔥
Python	The real MVP here 🐍
Pillow	Image handling & flexin’ 📸

🚀 How To Run It
bash
Copy
Edit
# Step 1: Install dependencies
pip install roboflow ultralytics easyocr pillow requests

# Step 2: Get the dataset from Roboflow
# Use your API key to fetch & download

# Step 3: Train the model
# inside the notebook:
model.train(
    data="License-Plate-Detection-dataset-1/data.yaml",
    imgsz=640,
    batch=4,
    epochs=100,
    patience=5,
    name="license_plate_detector"
)

# Step 4: Detect & OCR
# Load model and run predictions on any image URL
📸 Sample Output
🔲 YOLO detects this → 🅱️
🔡 EasyOCR reads this → WB 20 AK 6969

That's a full AI pipeline doing 🔥 magic.

💡 Why This Slaps
✅ Real-time use cases: Parking 🅿️, Toll booths, Security, and Spy stuff 🕵️

✅ Clean YOLOv8 + EasyOCR integration

✅ Based on real news image samples 📰

✅ Super customizable

🧠 Made By
Built with 🚀 and ☕ by Prantik Roy

🛠️ Coming Soon (maybe 😉)
🎥 Video input support

🧠 Smart post-processing

🌐 Flask or Streamlit web app

💬 Real-time alert system (imagine this on CCTV 👀)

Clone it. Run it. Detect it. Flex it.
✌️ Peace out, coder gang 💻🔥
