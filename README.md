# 🎙️ BOLISEVA – Voice-First Loan Lifecycle Assistant

> **Winner – TVS Credit EPIC 7.0 IT Challenge**

BOLISEVA is an AI-powered, multilingual, voice-first loan lifecycle assistant designed to make financial services accessible for rural and semi-urban users. The platform enables users to interact using natural voice conversations, simplifying loan applications, document management, EMI tracking, and customer support while reducing dependence on digital literacy.

---

# 📖 Project Overview

Accessing financial services can be challenging for users who are unfamiliar with English interfaces or complex digital forms. 
Boliseva addresses this problem by providing an intuitive voice-driven experience that guides users throughout the entire loan lifecycle.

The platform combines speech recognition, multilingual support, AI-powered conversational assistance, secure authentication, and cloud-based data management to create an inclusive and accessible digital lending experience.

The application follows a modular architecture with separate frontend, backend, AI, and database layers, making it scalable and easy to maintain.

---

# ✨ Features

### 🎤 Voice-First User Experience
- Speech-based interaction
- Voice navigation across loan services
- Hands-free application process

### 🌐 Multilingual Support
- Regional language support
- Language selection for better accessibility

### 🤖 AI Loan Assistant
- AI-powered conversational guidance
- Loan eligibility assistance
- Customer query resolution
- Smart conversational workflow

### 📄 Loan Lifecycle Management
- Loan application
- Loan status tracking
- EMI information
- Loan closure assistance

### 🔐 Secure Authentication
- Mobile number authentication
- OTP verification
- Secure user login

### ☁️ Cloud Database
- Cloud-hosted PostgreSQL using Supabase
- Secure storage
- Scalable architecture

### 📶 Offline-Friendly Design
- Handles intermittent internet connectivity
- Synchronizes data when connection is restored

### 📊 User Dashboard
- Personal profile
- Loan history
- Application status
- EMI details

---

# 🛠 Tech Stack

## Frontend
- React
- TypeScript
- Vite
- Tailwind CSS

## Backend Services
- Supabase
- PostgreSQL

## AI
- Google Gemini API

## Authentication
- Twilio OTP Authentication

## Database
- Supabase PostgreSQL

## Other Technologies
- Speech Recognition API
- Web Speech Synthesis
- REST APIs

---

# 📁 Folder Structure

```text
BOLISEVA
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── hooks/
│   ├── contexts/
│   ├── lib/
│   ├── utils/
│   ├── types/
│   └── assets/
│
├── public/
│
├── supabase/
│   ├── migrations/
│   └── functions/
│
├── package.json
├── vite.config.ts
└── README.md
```

---

# 🚀 Installation

## 1. Clone Repository

```bash
git clone https://github.com/Bhavyaa110/boliseva.git
```

## 2. Navigate to Project

```bash
cd boliseva
```

## 3. Install Dependencies

```bash
npm install
```

## 4. Configure Environment Variables

Create a `.env` file.

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_key
VITE_GEMINI_API_KEY=your_gemini_api_key
VITE_TWILIO_ACCOUNT_SID=your_account_sid
VITE_TWILIO_AUTH_TOKEN=your_auth_token
VITE_TWILIO_PHONE_NUMBER=your_twilio_phone
```

---

## 5. Start Development Server

```bash
npm run dev
```

The application will be available at:

```
http://localhost:5173
```

---

# 💻 Usage

1. Register using your mobile number.
2. Verify your account with OTP.
3. Choose your preferred language.
4. Interact with the AI assistant using voice or text.
5. Apply for loans or manage existing loan information.
6. Track loan status and EMI details.
7. Receive AI-assisted guidance throughout the loan lifecycle.

---

# 🚀 Future Improvements

- Backend-based OTP authentication
- Voice biometrics for authentication
- AI-powered financial recommendations
- Loan eligibility prediction using ML
- Document OCR and verification
- Push notifications
- WhatsApp integration
- Multi-bank integration
- Admin analytics dashboard
- Offline speech recognition
- Regional language expansion
- End-to-end encryption for sensitive user data

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature/new-feature
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push to your branch.

```bash
git push origin feature/new-feature
```

5. Open a Pull Request.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Bhavya Agarwal** & **Atharva Pandey**

- GitHub: https://github.com/Bhavyaa110
- LinkedIn: https://linkedin.com/in/bhavya-ag65

---

⭐ If you found this project useful, consider giving it a **star** on GitHub.
