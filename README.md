# Attendance Management System using Face Recognition 📸✅

---

## Project Overview  
The *Attendance Management System using Face Recognition* utilizes advanced facial recognition technology to streamline attendance management. By capturing and comparing facial data with a secure database, this system automates attendance tracking, reducing manual effort and ensuring accuracy. It is designed to benefit educational institutions and corporate environments alike.

### Key Features:  
- 🏢 **Real-time Facial Recognition**: Accurately identifies individuals to mark attendance.  
- 📂 **Secure Database Integration**: Safeguards attendance data and ensures reliability.  
- 🔄 **Robust Error Handling**: Detects and resolves operational issues seamlessly.  
- 📊 **Comprehensive Reporting**: Generates detailed attendance reports.

---

## Steps for Setup ⚙📂  
### 1. Download Project Files  
Download the project repository as a ZIP file from the GitHub link.  

### 2. Extract Files  
Unzip the downloaded file to a designated folder on your system.  

### 3. Install Required Libraries  
Navigate to the project directory using the terminal and install all dependencies:
```bash
pip install -r requirements.txt
```

### 4. Database Setup  
- Configure the database credentials in the project settings.  
- Ensure the database schema matches the requirements provided in the documentation.  

---
## Directory Structure
```plaintext
Attendance Management System using Face Recognition/
│
├── TrainingImage/               # Directory to store training images
├── TrainingImageLabel/          # Directory to save trained model
├── StudentDetails/              # Directory to save student details CSV
├── Attendance/                  # Directory to save attendance records
├── haarcascade_frontalface_default.xml  # Haarcascade file for face detection
├── requirements.txt             # Required Python packages
├── main_Run.py                  # Main application file
├── training.py                  # Script for training the face recognition model
├── testing.py                   # Script for testing face recognition
├── mini_app.py                  # Simple GUI application for capturing images
├── app.py                       # Streamlit app for attendance visualization
└── README.md                    # Project documentation
---
## Error Handling ⚠️  
### Built-in Features to Address Common Issues:
1. **Database Connection Issues**: Verifies and alerts on connectivity problems.
2. **Camera Access Errors**: Notifies users if the camera is unavailable or not functioning.
3. **Unrecognized Faces**: Logs such instances for manual review.
4. **Missing Dependencies**: Guides users to install any missing Python modules.  

---

## Technical Requirements 📦  
To run this project, install the following libraries:  
1. **excel**: For database operations.  
2. **opencv-python**: To enable camera access and facial recognition.  
3. **numpy**: For efficient data handling and calculations.  
4. **face-recognition**: Core library for facial identification.  
5. **pandas**: To structure and manage attendance data.  
6. **datetime**: To log attendance timestamps.  

---

## Installation

### Clone the Repository  
1. Open a terminal or command prompt.  
2. Navigate to the directory where you want to save the project:
   ```bash
   cd /path/to/your/folder
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/vaibhell/attendance.git
   ```

### Install Dependencies  
1. Navigate into the project directory:
   ```bash
   cd Attendance_Management_System_Using_Face_Recognition
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Create Necessary Folders  
Ensure the following directories are created to store image data:
- **Attendance**: For capturing real-time images.  
- **TrainingImage**: For training facial recognition models.  

---

## Usage
1. Run the main script to start the application:
   ```bash
   python main.py
   ```
2. Follow the on-screen instructions to capture faces, train the system, and mark attendance.  

---

## Contribution Guidelines 🛠️  
We welcome contributions to improve this project! Here’s how you can contribute:
- Fork the repository on GitHub.
- Make changes to the code or documentation.
- Submit a pull request for review.

For suggestions or feature requests, feel free to open an issue on the GitHub page.

---

## Acknowledgements  
I extend my deepest gratitude to my mentor, **Aditya Prashant Ardak**, for his exceptional guidance and support throughout this project. Your insights have been invaluable.  

Special thanks to the entire team for this opportunity to work on such an impactful project, enhancing both my technical skills and understanding of real-world applications.

---

Feel free to connect and collaborate to make this project even better! 🚀

