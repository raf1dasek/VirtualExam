# VirtualExam

**VirtualExam** is a comprehensive web-based platform designed to facilitate multiple-choice online examinations for educational institutions. It offers an efficient, secure, and user-friendly experience for both students and administrators.

##  Features

### Admin
- Login/logout and dashboard
- Add/view courses and exams
- Add/view students
- View results by course
- View feedback and manage student requests
- Post announcements
- Control access and exam availability

### Student
- Login and password reset
- Request to join
- View enrolled courses
- Take exams and receive instant feedback
- View results
- Submit feedback

---

##  Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** PHP
- **Database:** MySQL
- **Version Control:** Git
- **IDE:** Visual Studio Code
- **Web Server:** Apache (XAMPP/LAMP recommended)

---

##  System Design

- **Flow Diagram**
  ![Screenshot (69)](https://github.com/user-attachments/assets/c3fcce54-c341-4152-bd91-ed4dde302e72)

- **Use Case Diagram**
  ![Screenshot (70)](https://github.com/user-attachments/assets/9d26476a-3067-4912-9001-ae5187b4619c)

- **Entity-Relationship Diagram**
![Screenshot (71)](https://github.com/user-attachments/assets/e51f5953-ffca-4def-8d4f-abe73e8b6dbb)

These diagrams represent the structural and functional logic of the VirtualExam system.

---

##  How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/raf1dasek/VirtualExam.git


## Limitations

- The system is dependent on a stable internet connection for all users.
- Security is limited to basic front-end restrictions; it does not support live proctoring or advanced cheating prevention.
- Currently lacks advanced analytics or performance tracking features for students and administrators.
- The platform is optimized for desktop use only; no dedicated mobile application is available.
- Feedback and result insights are limited to simple views without in-depth reporting.

---

## Future Enhancements

- **Live Proctoring:** Integrate webcam and ID verification to ensure exam integrity.
- **Mobile Application:** Develop a mobile app version for Android and iOS with push notification support.
- **Advanced Analytics:** Include dashboards for performance trends, comparison, and graphical analysis.
- **Coding Contest Module:** Introduce a section for coding challenges with a real-time compiler and leaderboard, similar to platforms like HackerRank.
- **Paid Quiz System:** Enable paid quizzes using secure payment gateways for monetization or certifications.
- **Homepage with Open Quizzes:** Allow guest users to access public quizzes by category (e.g., General Knowledge, Aptitude).
- **Offline Exam Mode:** Implement limited offline capabilities with automatic syncing when the internet is available.

