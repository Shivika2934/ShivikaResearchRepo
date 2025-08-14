# First Question

[https://64e91fbd-c3b3-4588-b4a8-ca41bcf0a39f-00-1kh99z2geglia.spock.replit.dev/admin/view_questions/6](https://64e91fbd-c3b3-4588-b4a8-ca41bcf0a39f-00-1kh99z2geglia.spock.replit.dev/login)
flow diagram:
<img width="800" height="450" alt="question1" src="https://github.com/user-attachments/assets/92868b09-9f05-42fe-a5fb-e6c5f95d59f9" />

login page: 
<img width="1166" height="634" alt="image" src="https://github.com/user-attachments/assets/b68fce7f-9a50-46c8-b1b5-23978372802f" />
admin portal for creating questions
<img width="1092" height="633" alt="image" src="https://github.com/user-attachments/assets/1faf76e9-5bb0-4508-aedb-160dda9b8e91" />
student portal for viewing assigned question
<img width="1081" height="627" alt="image" src="https://github.com/user-attachments/assets/ccd956a3-f3fe-4325-8e4a-1a9517843477" />
## 🎯 Objectives
- Eliminate paper usage for question papers and evaluations.
- Maintain **exam integrity** with secure authentication.
- Provide **role-based access** (Admin, Student).
- Enable **multi-device compatibility** (desktop, mobile, tablet).
- Automate **question generation and evaluation** using AI.

---

## 🏗 System Architecture
The system is designed with two main roles:

1. **Admin**
   - Securely log in.
   - Use AI to auto-generate question papers from syllabus/topics.
   - Schedule and publish exams digitally.
   - View and evaluate student submissions.
   - Access analytics and performance reports.

2. **Student**
   - Log in securely.
   - Attempt digital question papers within the exam window.
   - Submit answers digitally.
   - View results and feedback.

---

## 🔍 Role of AI
- **Question Paper Generation**:  
  AI generates unique, difficulty-balanced question papers from a syllabus or topic bank to prevent cheating.
  
- **Plagiarism Detection**:  
  AI checks for answer originality in real-time to ensure academic honesty.
  
- **Automated Evaluation**:  
  AI evaluates objective questions instantly and assists in grading subjective answers.

- **Proctoring**:  
  AI-based remote proctoring detects unusual behavior via webcam and microphone.
  
# Second Question
https://cdad7ef9-7626-4c49-a658-e9416bb6b830-00-1uq08hnlem0q7.picard.replit.dev/
<img width="1377" height="534" alt="question2" src="https://github.com/user-attachments/assets/1b4593aa-0990-451c-973d-9790fc262958" />

<img width="1199" height="639" alt="image" src="https://github.com/user-attachments/assets/66efc807-7468-444d-91a1-4a5e7c0c09e8" />
student dashboard:
<img width="1194" height="623" alt="image" src="https://github.com/user-attachments/assets/db236e14-68d7-4bd6-906b-8016e234938a" />
<img width="1152" height="490" alt="image" src="https://github.com/user-attachments/assets/ced565e2-75e4-43f9-86d1-030db6fd145f" />

admin dashboard:
<img width="1156" height="541" alt="image" src="https://github.com/user-attachments/assets/5d925ff4-2751-4001-91cf-ccfca5a91443" />
<img width="1144" height="283" alt="image" src="https://github.com/user-attachments/assets/ab8eae4b-b1e5-40ac-bedd-4189c718c84e" />

## AI-Powered Digital Examination System

A comprehensive digital examination platform built with Flask that leverages AI for question generation, automated evaluation, and intelligent exam management.

### 🌟 Features

#### Core Functionality
- **Role-based Authentication**: Separate interfaces for administrators and students using Replit OAuth
- **AI Question Generation**: Automatically generate unique questions using OpenAI's GPT-4o model
- **Exam Management**: Create, publish, and manage exams with flexible settings
- **Timed Examinations**: Built-in countdown timer with automatic submission
- **Anti-Cheat Measures**: Tab switching detection, question randomization, and session monitoring
- **Automated Evaluation**: Instant grading for multiple-choice questions
- **Comprehensive Analytics**: Detailed performance statistics and reporting

#### Admin Features
- Create exams with AI-generated questions
- Subject and difficulty level management
- Question approval and review workflow
- Real-time exam monitoring
- Performance analytics and reporting
- Student result management

#### Student Features
- Responsive exam interface
- Real-time timer with visual warnings
- Progress tracking and navigation
- Auto-save functionality
- Detailed result viewing
- Mobile-friendly design

#### AI Integration
- **Question Generation**: Create contextually relevant questions based on subject and difficulty
- **Question Variations**: Generate multiple versions to prevent cheating
- **Content Adaptation**: Adjust difficulty and complexity automatically
- **Future Enhancement**: Subjective answer evaluation (framework ready)

