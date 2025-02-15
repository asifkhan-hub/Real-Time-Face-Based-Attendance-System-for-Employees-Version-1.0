# 🚀 Real-Time Face Based Attendance System for Employees | Version 1.0

Automate employee attendance with our cutting-edge face recognition system. Using **MTCNN** and **InceptionResnetV1**, it provides **real-time check-in/check-out**, accurate face detection, and seamless attendance tracking. The system supports **multiple cameras**, generates detailed reports, and ensures secure and efficient attendance management. Ideal for businesses looking to **streamline their attendance process** with enhanced security and accuracy.

---

## 🔑 Key Features

✅ **Real-Time Face Recognition**: Utilizes the powerful **MTCNN** (Multi-task Cascaded Convolutional Networks) and **InceptionResnetV1** models to detect and recognize faces in real-time with high accuracy.

📝 **Easy Employee Registration**: Employees can be quickly registered by uploading their profile picture and essential details such as **name, employee ID, phone number, email, and department**.

🔄 **Automatic Check-In and Check-Out**: Records employee check-ins and check-outs automatically using facial recognition, eliminating manual attendance entry.

📊 **Efficient Attendance Management**: Tracks daily attendance, including **check-in and check-out times**, with detailed records of **stay duration**. Attendance records are organized by date and employee for easy management.

📷 **Multiple Camera Support**: Supports multiple cameras simultaneously, whether using **local webcams or IP cameras**.

🔒 **Security and Authorization**: Employees are identified and authorized based on face recognition data, ensuring **secure and accurate** attendance recording.

⚙️ **Customizable Threshold Settings**: Allows the admin to set a threshold for **face recognition accuracy**, ensuring high-quality detection tailored to your environment.

🔊 **Sound Notifications**: Plays customizable **success sounds** upon successful check-in/check-out using **Pygame**.

📑 **Comprehensive Reporting**: Generates **CSV and Excel reports** with check-in/check-out times and stay duration for detailed analysis.

👨‍💼 **Admin Control**: Admins can **manage employees**, authorize or deactivate accounts, and securely access the system with role-based login.

---

## 🎯 Benefits

📈 **Increased Accuracy and Efficiency**: Automated tracking ensures **error-free** attendance records.

💰 **Cost-Effective**: Reduces administrative overhead by automating attendance management, **saving time and resources**.

🔐 **Enhanced Security**: Eliminates the need for physical ID cards, making the system **tamper-proof**.

🖥️ **User-Friendly Interface**: Simple UI for easy navigation by employees and admins.

⚙️ **Customizable for Your Needs**: Scalable for **small offices or large organizations**.

---

## 🛠️ Technology Stack

- 🎭 **Face Detection & Recognition**: MTCNN and InceptionResnetV1
- 🏗️ **Backend Framework**: Django
- 🎨 **Frontend Technologies**: HTML, CSS, JavaScript
- 🗄️ **Database**: SQLite or PostgreSQL
- ⚡ **Real-time Processing**: Multi-threading for simultaneous camera handling
- 🔊 **Sound Notifications**: Integrated with Pygame

---

## 📥 Installation Requirements

Ensure you have Python installed on your system. Then, install dependencies using `requirements.txt`.

### 📌 Prerequisites

- 🐍 **Python 3.12.1**
- 🏗️ **Django**
- 🎥 **OpenCV**
- 🔥 **Torch & torchvision**
- 🧠 **Face recognition libraries (MTCNN, InceptionResnetV1)**
- 🔊 **Pygame (for alert sounds)**

### 📥 Installation Steps

1️⃣ **Clone the Repository**
```sh
git clone https://github.com/asifkhan-hub/Real-Time-Face-Based-Attendance-System-for-Employees-Version-1.0/
```

2️⃣ **Create a Virtual Environment (Recommended)**
```sh
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3️⃣ **Install Dependencies**
```sh
pip install -r requirements.txt
```

4️⃣ **Apply Migrations**
```sh
python manage.py migrate
```

5️⃣ **Run the Server**
```sh
python manage.py runserver
```

6️⃣ **Access the Application**
🌐 Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser and log in.

---

## 📜 License

This project is open-source and available under the **[MIT License](LICENSE)**.

---

## 📧 Contact

For inquiries or contributions, feel free to reach out:

📩 **Email**: [asifkhanhdn75@gmail.com](mailto:asifkhanhdn75@gmail.com)

🌍 **Website**: [apycoder.com](https://apycoder.com)

💡 **Follow & Contribute**: *Revolutionize attendance management today!* 🚀
