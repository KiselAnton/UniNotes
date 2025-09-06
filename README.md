
# What is this project?
This is an open-source web application designed for university students and educators. It combines the flexibility of personal note-taking (similar to Obsidian) with the power of collaboration and AI support.

- 📚 Subjects & Lectures — Academics create subjects, add lectures, and attach resources.
- ✍️ Personal Notes — Every student receives a private space to write notes during lectures.
- 🤝 Combined Notes — The system aggregates and synthesises shared notes into a collaborative lecture document, reviewed by academics or moderators.
- 🧠 AI-assisted learning — Automatically generates flashcards, quizzes, and tests to help students revise.
- 🔍 Search & organisation — Full-text search across lectures and notes.
- 🌐 Web-only, open source — Runs in the browser, no paid licences required; universities can self-host.


# Vision statement

The aim is to make higher education knowledge more accessible, collaborative, and student-driven. Instead of fragmented personal notes, students are provided with a shared “knowledge commons” for each subject. The application empowers communities to study more effectively together, without relying on costly commercial tools.


# Audience

- Students — Write and organise your own notes, practise with flashcards, and benefit from collaborative giga-notes.
- Academics/Admins — Set up subjects, provide official resources, and curate AI-generated material.
- Contributors — Join the project! Help build features, improve AI pipelines, or translate the application for your university.


# Why open source?

- Universities should not have to pay subscription fees for essential study tools.
- Open code ensures transparency (especially important when AI is involved).
- Community contributions can improve the tool for everyone.


# Project structure

```
/backend         # FastAPI backend application
/frontend        # React + Tiptap frontend application
/infrastructure  # Docker Compose, deployment, CI/CD
```

- **backend/** — FastAPI backend, REST API, business logic, database models
- **frontend/** — React application, Tiptap editor, user interface
- **infrastructure/** — Docker Compose, deployment scripts, CI/CD pipelines
