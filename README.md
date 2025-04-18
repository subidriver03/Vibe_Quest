# Vibe Quest  
**Level Up Your Life: The Gamified Personal Growth Tracker**  
**Author:** Vibe Rantz  
**Version:** Draft 1.0  
**Date:** April 18, 2025  

---

## 🎯 Introduction

### 1.1 Purpose  
This document outlines the functional and non-functional requirements of the *Vibe Quest* application. Special focus is given to areas that are conceptually challenging, such as gamification logic, translating personal growth into digital progress, and creating a motivational user experience.

### 1.2 Scope  
*Vibe Quest* is a web-based application designed to transform personal development into an RPG-like experience. It targets users who struggle with motivation and are seeking a more engaging, creative way to track progress and build better habits.

---

## 🧠 Conceptually Difficult Areas

### 2.1 Gamification of Personal Tasks  
One of the hardest aspects to implement is giving real-life actions meaningful game mechanics.
- Users manually input custom tasks (e.g., “Go for a walk,” “Sketch for 30 min”).
- Tasks grant XP and are tied to skill categories: Mind, Body, Creativity, and Focus.
- Completing tasks awards XP and levels up the user.

**Challenge:** Making the system feel like real progress, NOT just checkbox ticking. XP values and level-up pacing must feel natural and rewarding.

---

### 2.2 Skill Trees & Progress Mapping  
- Skill Trees will visually show growth across categories like Creativity, Focus, Health, and Mental Resilience.
- XP from tasks gets distributed into these areas.

**Challenge:** Users must be able to easily see the connection between their actions and their growth. Cause and effect must be clear in the UI.

---

### 2.3 Leveling System  
- Users level up based on total XP earned.
- XP thresholds grow with each level.
- Rewards may be visual, cosmetic, or motivational.

**Challenge:** Creating a balanced XP curve that keeps users motivated without making progress feel too easy or impossible.

---

### 2.4 Journal Reflections & Mental Growth  
- Users can write daily or weekly reflections.
- Journals are tied to growth, not just storage.
- Completing reflections may grant XP or “Mental Clarity” bonuses.

**Challenge:** Emotional growth is hard to quantify. We need to show this value clearly without making it feel like we're trivializing mental health.

---

### 2.5 Why This Isn’t Just a To-Do List  
- The core loop: input quests → complete → earn XP → level up → grow skills.  
- Encourages deeper self-reflection and habit consistency.

**Challenge:** Users may assume it’s just another productivity app. We must emphasize the RPG experience, gamified motivation, and visual progress.

---

## 🛠️ Tools & Technology

- **Frontend:** Blazor WebAssembly  
- **Backend:** ASP.NET Core  
- **Auth:** ASP.NET Identity  
- **Database:** SQLite *(tentative; still under research)*  
- **Styling:** Bootstrap 5 or TailwindCSS  
- **Version Control:** GitHub  
- **Hosting (Dev):** localhost → GitHub Pages *(for front-end)*

---

## 🚀 Future Expansion Areas

- Boss Battles: Multi-day milestone quests  
- Achievements: Visual rewards for consistency  
- Companion mobile app  
- Patreon integration: Exclusive quests and digital unlockables  

---

> “Grind XP. Grow IRL.” – *Vibe Rantz*
