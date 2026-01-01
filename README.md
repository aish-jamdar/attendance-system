# attendance-system
# Face Recognition Attendance System 

This project is a real-time **Face Recognition Based Attendance System** developed using **Python, OpenCV, and Machine Learning (KNN)**.  
It captures facial data, recognizes registered users, and automatically marks attendance with date and time.

---

## 🔹 Features

- Real-time face detection using Haar Cascade
- Face recognition using K-Nearest Neighbors (KNN)
- Attendance stored in CSV format
- Background UI integration
- Duplicate attendance prevention
- Manual control for next student
- Easy dataset reset and retraining

---

## 🔹 Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- CSV
- Pickle

---

## 🔹 Project Structure
attendance-system/<br/>
│
├── attendance.py<br/>
├── dataset.py<br/>
├── haarcascade_frontalface_default.xml<br/>
├── bg.png<br/>
├── data/<br/>
├── Attendance/<br/>
├── requirements.txt<br/>
├── README.md<br/>
└── .gitignore<br/>


---

## 🔹 How It Works

1. **Face Registration**
   - Capture face images using webcam
   - Store face features and labels

2. **Training**
   - Train KNN model using stored face data

3. **Attendance**
   - Detect and recognize face in real time
   - Press `o` to mark attendance
   - Press `n` to allow next student
   - Attendance saved with timestamp

---

## 🔹 Controls

| Key |       Action       |
|-----|--------------------|
| `o` |   Mark attendance  |
| `n` | Allow next student |
| `q` |  Quit application  |

---

## 🔹 Installation & Setup

1. Clone the repository:
git clone https://github.com/aish-jamdar/attendance-system.git

2. Install dependencies:
pip install -r requirements.txt

3. Run face registration:
python dataset.py

4. Run attendance system:
python attendance.py

---

## 🔹 Notes

- Do not open CSV files while the program is running
- Ensure proper lighting for accurate recognition
- Face data and attendance files are ignored for privacy

---

## 🔹 Future Improvements

- Automatic attendance without key press
- Face recognition confidence threshold
- Database integration
- Web-based interface

---

## 🔹 Author

**Aishwarya Jamdar**  
