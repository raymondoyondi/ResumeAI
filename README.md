# ResumeAI 🚀
**The Intelligent Path to Your Next Career Move.**

ResumeAI is an intelligent, full-stack web application designed to help job seekers bypass the "ATS black hole." By leveraging AI-powered content generation, the platform transforms raw career data into professional, high-impact, and ATS-friendly resumes in minutes.

---

## ✨ Key Features

* **AI-Powered Content Generation:** Automatically craft compelling bullet points and professional summaries based on your job title and experience.
* **ATS Optimization:** Built-in keyword analysis to ensure your resume passes through Applicant Tracking Systems.
* **Real-Time Live Preview:** See your changes instantly as you type with a side-by-side editing interface.
* **Secure Authentication:** User accounts and data protection powered by modern auth providers.
* **Customizable Templates:** Choose from various professional layouts designed to be readable by both humans and machines.
* **PDF Export:** High-quality, formatted PDF generation ready for job applications.

---

## 🛠️ Tech Stack

* **Frontend:** React, Next.js, Tailwind CSS, Lucide Icons
* **Backend:** Node.js, Express
* **AI Integration:** Google Gemini API / OpenAI API
* **Database:** PostgreSQL / MongoDB
* **Authentication:** Clerk / NextAuth

---

## 🚀 Getting Started

### Prerequisites
* Node.js (v18.x or higher)
* NPM or Yarn
* AI API Key (Gemini or OpenAI)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/raymondoyondi/ResumeAI.git](https://github.com/raymondoyondi/ResumeAI.git)
    cd ResumeAI
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up Environment Variables:**
    Create a `.env` file in the root directory and add your credentials:
    ```env
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=

    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

    MONGODB_URL=

    GEMINI_API_KEY=
 
    BASE_URL=localhost:3000
    ```

4.  **Run the development server:**
    ```bash
    npm run dev
    ```

---

## 🗺️ Roadmap
- [ ] Multi-language support for international job markets.
- [ ] AI Cover Letter generator based on specific job descriptions.
- [ ] LinkedIn profile optimization suggestions.
- [ ] Browser extension for one-click data importing.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  **Fork** the Project.
2.  **Create** your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  **Commit** your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  **Push** to the Branch (`git push origin feature/AmazingFeature`).
5.  **Open** a Pull Request.

Please ensure your code follows the existing style and includes comments for complex logic.

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.
