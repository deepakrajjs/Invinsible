
### 🪄 Invisible Cloak using Python & OpenCV

This project brings a bit of Harry Potter magic into reality using **Python** and **OpenCV**.  
With the help of Computer Vision, a cloak of a specific color becomes invisible in real-time video.



## 📌 Overview
The idea is simple:
1. Capture the background.
2. Detect a specific cloak color (default: **red**).
3. Replace the detected cloak area with the background.
4. The cloak appears **invisible** on camera. 👻



## 🛠 Tech Stack
- Python 3
- OpenCV
- NumPy


## 🚀 How It Works
- Convert live video frames to **HSV color space**.  
- Create a **mask** for the cloak color.  
- Refine the mask using **morphological operations**.  
- Replace the cloak area with the **saved background**.  
- Display the output in real time.  

---

## 📂 Setup & Installation

1. **Clone the Repository**
   
   git clone https://github.com/your-username/invisible-cloak.git
   cd invisible-cloak


2. **Install Dependencies**

   
   pip install opencv-python numpy
   ```

3. **Run the Script**

   
   python invisible_cloak.py
   ```

---

## 🎨 Customization

By default, this project detects the **red cloak**.
To use another color (like blue or green), update the HSV values in the code.

**Example (Blue Cloak):**


lower_blue = np.array([94, 80, 2])
upper_blue = np.array([126, 255, 255])


---

## 📖 What I Learned

* Basics of **Computer Vision & OpenCV**
* Real-time background replacement
* Color detection, masking, and image manipulation
* How fun projects make learning more engaging 🚀

---

## 📸 Demo




https://github.com/user-attachments/assets/ddab1871-df9c-4651-92d0-00915ac5f04a


---

## ✨ Future Enhancements

* Dynamic cloak color selection
* Multi-color cloak support
* Improved background capture

---

## 📜 License

This project is open-source and available under the **MIT License**.

```

---

Would you like me to also prepare the **`invisible_cloak.py` file** (final polished version of your code) so you can upload both **README.md** + **Python file** directly to GitHub without editing?
```
