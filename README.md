# Patient Queue and Doctor Appointment System

A multilingual web application for managing patient queues, doctor appointments, blood donations, feedback analysis, emergency SOS alerts, payments, and notifications. The system supports Admin, Doctor, and Patient roles, providing tailored dashboards and workflows for each.

## Features

- **Role-based Dashboards:** Separate dashboards for Admin, Doctor, and Patient.
- **User Authentication:** Registration and login with approval workflow for doctors.
- **Appointment Management:** Patients can book appointments; doctors can accept/reject and notify patients.
- **Patient Queue:** Each appointment is a position in the doctor's queue for a specific time slot.
- **Blood Donation:** Schedule donations, view/search donation history by region.
- **Feedback Analysis:** NLP-based feedback clustering and summary using scikit-learn and NLTK.
- **Emergency SOS:** Patients can send location-based SOS alerts; visible to doctors and admins.
- **Profile Management:** Update profile info and upload profile images.
- **Payments:** Submit payment details and view transaction history.
- **Notifications:** System notifications for appointments and emergencies.
- **Multilingual Support:** English and Kannada UI.
- **Find Nearby Hospitals:** Interactive map for hospital locations.

## Technologies Used

- **Backend:** Python, Flask
- **Database:** MongoDB (PyMongo, Flask-PyMongo)
- **Machine Learning/NLP:** scikit-learn, NLTK
- **Email:** Flask-Mail
- **Frontend:** HTML (Jinja2 templates)
- **File Uploads:** werkzeug
- **Session Management:** Flask sessions
- **Logging:** Python logging

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Gurukiran10/Patient-Queue-and-Doctor-Appointment-System.git
   cd Patient-Queue-and-Doctor-Appointment-System
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure MongoDB:**
   - Ensure MongoDB is running locally (`mongodb://localhost:27017/`).
   - Update MongoDB URI in `app.py` if needed.

4. **Configure Email:**
   - Set your email and password in `app.py` for Flask-Mail.

5. **Run the application:**
   ```bash
   python app.py
   ```

6. **Access the app:**
   - Open [http://localhost:5000](http://localhost:5000) in your browser.

## Folder Structure

```
Patient-Queue-and-Doctor-Appointment-System/
├── mini/
│   ├── app.py
│   ├── templates/
│   ├── static/
│   └── feedback.json
├── requirements.txt
└── README.md
```



## Screenshots

### Admin Dashboard
![Admin Dashboard](static/uploads/dashboard.png)

## License

MIT License

---

**For any questions or issues, please open an issue on GitHub.**
