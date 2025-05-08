# Face Recognition Attendance System 🎯

A real-time attendance system built using **Flask**, **OpenCV**, and **KNN classifier** that captures faces from a webcam, recognizes them, and marks attendance automatically.

---

## 📌 Features

- 🎥 Real-time face detection using OpenCV
- 🧠 Face recognition using K-Nearest Neighbors (KNN) classifier
- 📁 Save and manage user faces in organized folders
- 🧾 Mark attendance with name, roll number, and timestamp
- 📊 Export daily attendance as CSV files
- 🧹 User management (add/delete users)
- 🌐 Web-based interface using Flask

---

## 🔧 Tech Stack

- Python 3.x
- Flask
- OpenCV
- NumPy
- Pandas
- scikit-learn
- Joblib

---

## 📁 Project Structure

```

├── static/
│   ├── faces/               # Stored user face images
│   └── face\_recognition\_model.pkl  # Trained KNN model
├── Attendance/              # Daily attendance CSVs
├── templates/
│   ├── home.html            # Main attendance page
│   └── listusers.html       # Registered users listing
├── haarcascade\_frontalface\_default.xml  # Haar Cascade model
├── app.py                   # Main Flask application
└── README.md

````

---

## 🚀 Getting Started

### 1. Clone the Repository


### 2. Install Required Libraries

Make sure you have Python installed. Then install the dependencies:

```bash
pip install -r requirements.txt
```

**Sample `requirements.txt`**:

```
Flask
opencv-python
numpy
pandas
scikit-learn
joblib
```

### 3. Run the App

```bash
python app.py
```

Visit `http://127.0.0.1:5000/` in your browser.

---

## 🧑‍💻 How to Use

1. **Add User**
   Enter a new user name and roll number, capture 10 face images.

2. **Train Model**
   Automatically triggered after a new user is added.

3. **Take Attendance**
   Click “Take Attendance” to recognize faces and mark attendance.

4. **View Attendance**
   See the table of names, roll numbers, and timestamps on the homepage.

5. **Delete User**
   Go to "List Users" → Delete.

---

## 📌 Notes

* Attendance is saved in `Attendance/Attendance-<MM_DD_YY>.csv`
* At least one user must be registered before taking attendance.
* Press `Esc` to stop capturing from webcam.

---

## 📸 Screenshots

> Add screenshots here of your interface for `home.html` and `listusers.html`.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Syed Saaduddin Azhaan**
📧 [saaduddinsyed10@gmail.com](mailto:saaduddinsyed10@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/syed-saaduddin-b7682726b/)
💻 [GitHub](https://github.com/Saaduddin47)

---

