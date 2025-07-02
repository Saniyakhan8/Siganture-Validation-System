# 🖋️ Signature Validation System

A Flask-based web application that verifies a signature by comparing it with a reference signature using the Structural Similarity Index (SSIM). This tool helps in validating whether a given signature matches the reference signature or not, by analyzing image similarity.

## 🔍 Features

- 🔐 Secure login authentication  
- 📤 Upload reference signature and multiple signatures for validation  
- 🧠 Signature comparison using SSIM (Structural Similarity Index)  
- 🖼️ Displays best match signature and result  
- 💻 Responsive and user-friendly interface  

## 📂 Project Structure

signature-validation/
│
├── app.py # Main Flask app
├── static/
│ ├── style.css # Custom CSS styling
│ └── uploaded_images/ # Stores uploaded images
├── templates/
│ ├── login.html # Login page
│ ├── index.html # Upload & verify page
│ └── result.html # Result page
└── README.md # Project documentation

## ⚙️ Technologies Used

- Python 🐍  
- Flask 🌐  
- OpenCV 🎥  
- scikit-image 🧠  
- HTML/CSS 🖌️  

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/signature-validation.git
cd signature-validation
2. Install Required Libraries
bash
Copy
Edit
pip install flask opencv-python scikit-image
3. Run the Application
bash
Copy
Edit
python app.py
Visit http://127.0.0.1:5000/ in your browser.

🔐 Login Credentials
Default credentials (set in app.py):
Username: shalzz
Password: 17dk
You can change these in the USER_CREDENTIALS dictionary inside app.py.

🧠 How It Works
User logs in via secure login page.
Upload a reference signature and one or more signatures to verify.
The app compares each uploaded signature to the reference using SSIM.
Displays whether the signature is verified or not verified and shows the best match image.

🛠️ Future Improvements
User registration and multi-user support
History tracking for verification
Advanced ML/DL-based signature verification
Signature preprocessing (noise removal, alignment)

📬 Contact
Developed by Saniya Khan
📎 LinkedIn

📜 License
This project is for educational purposes and is open to modifications or enhancements.
