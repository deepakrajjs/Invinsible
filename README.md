
### 🪄 Invisible Cloak using Python & OpenCV

Bring a little Hogwarts magic to life with Python!  
This project creates an **Invisible Cloak effect** inspired by Harry Potter, using **Computer Vision techniques**.

---

## 📌 Project Overview
The idea is simple but powerful:
- Capture the background
- Detect a specific cloak color (default: red)
- Replace the cloak area with the background
- The cloak appears invisible in **real-time video** 👻

---

## 🛠️ Tech Stack
- **Python 3**
- **OpenCV** (Image Processing & Masking)
- **NumPy**

---

## 🚀 How It Works
1. Capture background frame
2. Convert live frames from BGR to HSV color space
3. Create masks to detect cloak color
4. Replace detected region with background
5. Display the processed video stream

---

## 📂 Installation & Setup

### 1. Clone this repository
```bash
git clone https://github.com/your-username/invisible-cloak.git
cd invisible-cloak
````

### 2. Install dependencies

```bash
pip install opencv-python numpy
```

### 3. Run the project

```bash
python invisible_cloak.py
```

---

## 🎨 Change Cloak Color

By default, this project detects **red color**.
You can update the HSV ranges in the code for other colors like **blue** or **green**.

Example (blue cloak):

```python
lower_blue = np.array([94, 80, 2])
upper_blue = np.array([126, 255, 255])
```

---

## 📸 Demo

Here’s how the effect looks in action:

![demo](demo.gif)

---

## 📖 Learning Outcomes

* Basics of **Computer Vision**
* Real-time background replacement
* Color detection & masking
* How fun projects can make learning more exciting

---

## ✨ Future Improvements

* Add option to select cloak color dynamically
* Support multiple cloak colors
* Improve background capture for more realistic effects

---

## 🤝 Contribution

Pull requests are welcome!
If you’d like to suggest improvements, feel free to fork the repo and open a PR.

---

## 📜 License

This project is open-source and available under the **MIT License**.

```



👉 Do you want me to also **write the `invisible_cloak.py` code file** neatly formatted so you can upload both together to GitHub?
```
