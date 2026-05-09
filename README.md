# 🏥 Medical Healthcare Platform (Multi-App System)

## 📌 Overview

This project is a **multi-application healthcare platform** designed to connect doctors, assistants (secretaries), and patients in a unified digital ecosystem.

It focuses on simplifying the medical appointment process, managing complex schedules, and enabling dynamic pre-visit form creation for doctors.

این پروژه یک سیستم جامع پزشکی چنداپلیکیشنی است که ارتباط بین پزشک، منشی و بیمار را در یک اکوسیستم یکپارچه فراهم می‌کند. هدف آن ساده‌سازی فرآیند نوبت‌دهی، مدیریت زمان‌بندی‌های پیچیده و ساخت فرم‌های پیش‌ویزیت داینامیک برای پزشکان است.

---

## 🧩 System Structure

The platform consists of **three separate applications**:

### 👨‍⚕️ Doctor App
- Manage working shifts (morning / evening)
- Define available time slots dynamically
- View and manage patient appointments
- Create custom pre-visit forms (Form Builder)
- Calendar-based scheduling system

### 🧑‍💼 Assistant App
- Manage doctor availability and schedules
- Handle appointment confirmations and coordination
- Support clinic workflow operations

### 🧑‍🦱 Patient App
- Search and view doctors
- Book appointments step-by-step
- Select date → shift → time → minute slots
- Fill pre-visit medical forms
- View appointment history

---

## ⚙️ Core Features

- 🗓 Dynamic calendar system based on doctor availability  
- ⏱ Multi-step appointment booking flow (date → shift → time → minute slots)  
- 🧠 Custom form builder for pre-visit medical data  
- 📊 Role-based system (Doctor / Assistant / Patient)  
- 🔁 Reusable component-based architecture  
- 📦 Centralized state management with Zustand  
- 📱 Fully mobile-first UI/UX design  

---

## 🧠 Technical Highlights

- Multi-step booking logic with conditional UI rendering  
- Shift-based scheduling system (morning / evening separation)  
- Dynamic slot generation in 5-minute intervals  
- Modular and scalable folder architecture  
- Separation of concerns between apps  
- Mock data layer prepared for backend integration  
- Clean and reusable UI components  

---

## 🏗 Architecture

- Built with **React Native (Expo)**
- State management: **Zustand**
- Navigation: React Navigation
- API-ready structure for backend integration
- Component-driven architecture
- Shared logic across multiple apps

---

## 🛠 Tech Stack

- React Native (Expo)
- TypeScript
- Zustand
- React Navigation
- REST API (planned)
- Custom UI Components
- Modular Design System

---
## 🎥 Demo

Two screen recordings are included in this repository to demonstrate the main flows of the application.

You can find them:
- `Create custom pre-visit forms.mp4`
- `Manage doctor availability and schedules.mp4`

These videos show the full user experience from login to core features.

## 🖼️ Screenshots

A set of screenshots is included in this repository to showcase the main features and UI of the application.

You can find them in the project:

- `clinic_broadcast_notification.jpg`
- `Receptionist Appointment Booking.jpg`

These screenshots provide a quick overview of the user interface and key functionalities across the app.

## 🚧 Project Status

This project is currently under active development.

The core system (appointment flow, calendar, and form builder) is implemented, while backend integration and real-time features are planned for the next phase.

Source code is partially private due to ongoing development and future production plans.

---

## 🧭 Roadmap

- Doctor scheduling system  
- Multi-step appointment booking flow  
- Custom form builder  
- Role-based architecture  
- Backend integration  
- Real-time notifications  
- WebRTC video consultation  
- Production deployment  
- Performance optimization  

---

## 💡 Key Idea

The goal of this project is to reduce friction in medical appointment management by:

- Making scheduling fully dynamic  
- Eliminating manual coordination  
- Allowing doctors to customize patient intake forms  
- Improving patient experience through step-by-step booking  

---

## 📬 Contact

If you'd like to learn more about this project or collaborate, feel free to reach out.
