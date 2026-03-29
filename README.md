# 🌍 Probashe Bangladesh - AI-Powered Overseas Employment & Visa Platform

> 🔒 **Confidentiality Notice:** The source code is private to protect proprietary business logic. This repository serves as a technical showcase for the AI-driven architecture and agency management system I engineered for the overseas employment sector.

## 🚀 System Overview
Probashe Bangladesh is an enterprise-grade solution designed for visa agencies. It bridges the gap between AI automation and human consultancy, featuring a personalized AI assistant, a dynamic job portal, and a robust tracking system for applicants (Work, Student, and Tourist visas).

### 🛠️ Tech Stack & Infrastructure

<p align="left">
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/resend-000000?style=for-the-badge&logo=resend&logoColor=white" alt="Resend" />
  <img src="https://img.shields.io/badge/Meta_CAPI-0668E1?style=for-the-badge&logo=meta&logoColor=white" alt="Meta CAPI" />
  <img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
</p>

---

## 🧠 Core Engineering Highlights

### 1. "Probashi Shohayota AI" - Hybrid Chatbot
* **AI Lead Generation:** Automatically captures user names and phone numbers to initiate a lead session in the admin panel.
* **Full Context Persistence:** Every message from the user and AI is logged in real-time for admin review.
* **Human Takeover Mode:** When a user requests a human representative, a real-time email alert is sent via **Resend API**. Admins can toggle off the AI to chat manually and hand back control to the AI anytime.
* **Knowledge Base Management:** Admins can train the AI by adding specific keywords and business logic directly from the dashboard.

### 2. Dynamic Visa Tracking & Workflow
* **Auto-Generated Tracking:** Every application gets a unique tracking code. Users can track their real-time status (Visa processing, embassy slots, etc.) without logging in.
* **Authenticated Tagging:** Registered users can "tag" their tracking codes to their profiles for one-click access.
* **Per-Country Dynamic Status:** Admins can add/edit custom application statuses based on specific requirements of different countries (e.g., KSA vs. UK).

### 3. Enterprise Admin & Audit System
* **Audit Logs:** Every action taken by admins or moderators is recorded, ensuring 100% accountability within the organization.
* **Granular RBAC:** Permissions can be set for specific pages (e.g., a moderator might only manage Job Posts but not access Email Settings).
* **Website CMS:** Fully dynamic control over country flags, requirements, dynamic FAQs, and multi-media reviews (YouTube links/Images).

### 4. Dynamic Email Engine
* **Template Customization:** Admins can edit HTML/Text email templates for various triggers (Welcome, Status Updates, Lead Alerts) using variables and real-time previews.

### 5. Technical SEO & Growth Tracking
* **Bilingual Support:** Full implementation of Bangla and English across the platform.
* **Hybrid Tracking:** Meta CAPI (Server-side) and GA4 integration with event deduplication for precise conversion tracking.
* **Robots & Sitemaps:** Optimized `robots.txt` and dynamic `sitemap.xml` for real-time indexing of new job circulars.

---

## 🤝 Let's Connect
I build complex, mission-critical systems that drive business revenue.
* 🌐 **Portfolio:** [shahnabil.com](https://shahnabil.com)
* ✉️ **Email:** hello@shahnabil.com
