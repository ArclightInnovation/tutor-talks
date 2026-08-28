# 🎓 Tutor Talks — AI Tutoring Web Platform for University Faculty & Students

**Tutor Talks** is a mobile-first, production-ready AI tutoring platform designed for university professors and students. Faculty members can configure specialized AI tutors for their courses, upload sectioned course modules, synthesize AI lesson plans, establish custom guardrails, and generate unique student access codes. Students log in using their class code and interact with customized AI tutoring modes, including Socratic questioning, practice quizzes, and step-by-step guidance.

---

## 🌟 Key Features

### 🎓 **Instructor Portal**
* **Course & Class Management:** Create and manage university courses with unique class access codes (e.g. `NYU-CS101`).
* **Sectioned Course Modules:** Upload syllabus materials, readings, and lecture notes organized by module.
* **AI Lesson Plan & RAG Synthesizer:** Auto-generate structured learning objectives, core concepts, teaching strategies, and misconception checks embedded directly into module context.
* **Scaffolding & Help Level Controls:**
  * **Minimal Hints (Socratic Questions Only):** Guides students with subtle nudges.
  * **Balanced Guidance:** Offers structured feedback and partial steps.
  * **Full Step-by-Step Explanations:** Complete detailed walk-throughs.
* **Safety Guardrails:**
  * Prevent direct homework/essay answer dumping.
  * Enforce academic honor code rules.
  * Restrict discussion strictly to course domain topics.

### 👨‍🎓 **Student Portal**
* **Class Code Login:** Login using student first name, last initial, and class access code.
* **Module Selection:** Choose specific course modules to study.
* **Interactive AI Chat:** Real-time conversation powered by **Gemini 3.1 Pro** with automatic model fallbacks.
* **Audio Voice Playback:** Native ElevenLabs text-to-speech audio synthesis for tutor replies.
* **Student Notes Pad & PDF Export:** In-session notes editor with 1-tap PDF downloads.
* **Custom `.tutor` Session Packaging:** End session and package all learning context, transcripts, notes, and AI mastery evaluations into a `.tutor` file to resume later.
* **Student Progress Tracking (`.md`):** Live dashboard tracking `STUDENT_PROFILE.md`, `STUDENT_MASTERY.md`, and `STUDENT_ANALYTICS.md`.

---

## 🔒 Security
Faculty authentication uses client-side SHA-256 verification, while students authenticate with class access codes. Authentication secrets are not documented or stored in plaintext.

---

## 🌐 Live Deployment
* **Live Web App:** [https://arclightinnovation.github.io/tutor-talks/](https://arclightinnovation.github.io/tutor-talks/)
