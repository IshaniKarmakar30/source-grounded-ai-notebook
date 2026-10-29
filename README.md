# Source-Grounded AI Study Notebook: CPU Scheduling Algorithms

[![AI Framework](https://img.shields.io/badge/Platform-Google%20NotebookLM-blue.svg)](https://notebooklm.google.com)
[![Topic](https://img.shields.io/badge/Domain-Operating%20Systems-orange.svg)]()
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

## 📌 Project Overview
This project is an interactive, source-grounded study notebook built using **Google NotebookLM** during the **Def-Space Advanced Generative AI & AI Agents Internship (BSERC)**. The system is designed to provide zero-hallucination, verified conceptual explanations and multimedia study materials on **Operating System CPU Scheduling Algorithms**.

---

## 🎯 Key Objectives
- **Zero-Hallucination Retrieval:** Implemented Retrieval-Augmented Generation (RAG) principles to restrict model reasoning strictly to curated academic sources.
- **Source Citation:** Every conceptual output is backed by direct inline source citations (e.g., NPTEL lectures and operating system texts).
- **Multilingual Concept Exploration:** Querying complex algorithm behaviors in native language (Bengali) while preserving technical accuracy.
- **Multimodal Learning Artifacts:** Generating synthetic study tools including Audio Overviews (AI Podcast), interactive Flashcards, Quizzes, Mind Maps, and Slide Decks.

---

## 📚 Curated Knowledge Base (Sources)
1. **NPTEL OS Lecture Materials:** Core theory on Process Scheduling, CPU Scheduling criteria, and context switching.
2. **Textbook References:** Silberschatz, Galvin, and Gagne's *Operating System Concepts*.
3. **Web References & Benchmarks:** Comprehensive guides on Preemptive vs Non-Preemptive scheduling.
4. **Educational Video Lectures:** Detailed Gantt chart simulations and turnaround/waiting time calculations.

---

## 🔬 System Evaluation & Testing

### 1. In-Domain Verification (Algorithm Deep-Dive)
- **Prompt:** `Explain Round Robin CPU Scheduling with an example from my source`
- **Behavior:** Accurately computed Average Waiting Time (AWT) and Average Turnaround Time (ATAT) with inline PDF citations.

### 2. Multilingual Grounding (Bengali Query)
- **Prompt:** `CPU Scheduling-এর মূল অ্যালগরিদমগুলো (FCFS, SJF, Round Robin) সহজ বাংলায় বুঝিয়ে দাও এবং সোর্স সাইটেশন উল্লেখ করো।`
- **Behavior:** Successfully translated domain concepts into clear Bengali while retaining source anchors.

### 3. Out-of-Domain Hallucination Test
- **Prompt:** `Do my uploaded sources mention how to make chicken biryani?`
- **Result:** **Passed.** The model explicitly refused to answer outside domain boundaries: *"No, your uploaded sources do not mention how to make chicken biryani. All sources focus exclusively on operating systems..."*

---

## 🎧 Studio Artifacts Generated
- **Audio Overview (Deep Dive Conversation):** Dual-host conversational podcast breaking down scheduling criteria and Gantt charts.
- **Mind Map & Slide Deck:** Structured visual hierarchy of preemptive vs non-preemptive algorithms.
- **Quiz & Flashcards:** Dynamic recall cards testing Time Quantum impact on CPU utilization.

---

## 🔗 Demo & Resources
- **Interactive AI Notebook:** [Click here to view NotebookLM](https://notebook.google.com/notebook/7022778d-6fda-4e4d-9291-ae82261818e0)
- **Author:** [Ishani Karmakar](https://github.com/IshaniKarmakar30)
