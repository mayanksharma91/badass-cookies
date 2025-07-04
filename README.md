# Tiny Wins - A Micro-Journaling App

> **Status:** [Archived] This project was a side project from 2022 and is no longer actively maintained. The original Supabase instance has been deactivated, so the code in this repository is not currently functional.

The best way to understand the project's vision is through the product demo video on the original landing page:

* **➡️ Live Landing Page:** [https://thetinywins.carrd.co/](https://thetinywins.carrd.co/)

---

### The Product Vision (The "Why")

The goal of Tiny Wins was to create a simple, frictionless micro-journaling experience. In a world of complex productivity apps, I wanted to build a tool focused on one thing: helping users celebrate their small, daily achievements to build positive momentum and combat burnout.

The core hypothesis was that by making the act of recording a "win" take less than 10 seconds, users could log small wins that we don't give ourselves credit for. The bot then surfaces these wins to remind you that you are awesome!

### Key Features

* **Frictionless Entry:** A simple text field and a single button to log a "tiny win."
* **Reminder of Wins:** Whenever you need a quick reminder of why you're awesome, the bot can surface an old win, and you can tweak how frequently you want it shown.
* **Minimalist UI:** Intentionally designed to avoid the feature bloat and distractions common in other journaling apps.

### Original Technology Stack

This project was built as an experiment using the following technologies:

* **Environment:** Node.js (v16.14.0), npm (8.5.2)
* **Frontend:** Telegram
* **Backend & Database:** [Supabase](https://supabase.com/) (for user authentication and data storage)
* **Integrations:** [Telegraf.js](https://telegraf.js.org/) (for connecting to a Telegram bot)

### Original Project Roadmap & Backlog

Below are the original, unedited notes for the project's MVP roadmap and future backlog. They are preserved here as an artifact.

**Product Backlog (Unprioritized)**

* **Custom Quests:** Allow users to create their own recurring journaling prompts.
* **Refactor 'Weight' Variable:** Change confusing variable names in the code (e.g., `weight` to `frequency`) to improve clarity for future development.
* **Improve Algorithm:** Show more important "wins" less frequently to retain their potency and impact.
* **Log user replies:** Create a `user_action_log` table in Supabase to track user messages and bot replies for analysis.

---
