# 🎨 Color Detection using OpenCV

A simple **real-time color detection** project built with **Python**, **OpenCV**, and **Pillow (PIL)**.  
It detects a specific color from the webcam feed and draws a green bounding box around the detected object.

---

## 📸 Demo

> The program uses your webcam to detect the specified color (default: blue).  
> You can change the target color in the code.

![Color Detection Example](https://github.com/yourusername/Project-Color-Detection/assets/example.gif)

---

## 🧠 How It Works

1. The webcam captures each video frame.  
2. Each frame is converted from **BGR** to **HSV** color space.  
3. Based on the chosen color, a **color range** (lower and upper HSV limits) is calculated.  
4. A **mask** is created to isolate the target color.  
5. The bounding box of the detected area is drawn in real time.  
6. Press **`q`** to quit the application.

---

## 🗂️ Project Structure

