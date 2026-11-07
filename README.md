# NBA Basketball Quiz App 🏀

A mobile quiz application built with **React Native** and **Expo** that tests your knowledge of NBA players, records, and team logos.

---

## Features

* **Interactive Quiz Questions:** Answer multiple-choice questions using custom dropdown pickers (`@react-native-picker/picker`).
* **Visual Aids:** Each question is paired with a consistent image showcase for players and team logos.
* **Instant Feedback & Scoring:** Submitting the quiz evaluates your answers against an answer key and provides a personalized scorecard using React Native's `Alert` API.
* **Scrollable Layout:** Built within a `ScrollView` for seamless navigation across all 6 questions.

---

## Tech Stack

* **Framework:** React Native / Expo
* **UI Components:** View, Text, Button, ScrollView, Image
* **Third-Party Package:** `@react-native-picker/picker`

---

## Project Structure

```text
├── assets/
│   ├── curry.png
│   ├── jaylen.png
│   ├── kawhi.png
│   ├── lebron.png
│   ├── paul george.png
│   └── philly.png
├── App.js
├── app.json
├── package.json
└── README.md