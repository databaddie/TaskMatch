# 📦 TaskBuddy – Product Backlog & Sprint Plan

A mobile/web platform that connects college students with local people who need help with everyday tasks like mowing the lawn, grocery runs, or returns.

---

## 🔖 Labels (Windsurf/GitHub)

- `epic/onboarding`
- `epic/task-posting`
- `epic/chat`
- `epic/payments`
- `epic/ratings`
- `epic/admin`
- `feature/frontend`
- `feature/backend`
- `feature/api`
- `chore/devops`
- `chore/qa`
- `auth`
- `stripe`
- `map`
- `edu-verification`
- `priority/high`
- `priority/medium`
- `priority/low`

---

## 🧱 Backlog by Epic

---

### 🧑‍💼 Epic: Onboarding & Profiles (`epic/onboarding`)

#### User Stories
- **[3 pts]** `Signup`: As a user, I want to sign up with email and password.
- **[5 pts]** `Email Verification`: As a student, I want to verify my .edu email address.
- **[2 pts]** `Login Session`: As a user, I want to stay logged in using persistent sessions.
- **[4 pts]** `Profile Setup`: As a user, I want to create a basic profile with photo and task preferences.

#### Chores
- **[2 pts]** `Email Templates`: Setup email templates for verification and welcome emails.

---

### 📝 Epic: Task Posting & Matching (`epic/task-posting`)

#### User Stories
- **[5 pts]** `Post a Task`: As a poster, I want to describe and publish tasks with payment, time, and location.
- **[5 pts]** `Browse Tasks`: As a tasker, I want to see local tasks filtered by time, location, and category.
- **[4 pts]** `Accept Task`: As a tasker, I want to accept tasks and notify posters.
- **[6 pts]** `Auto-Match`: As a poster, I want taskers automatically recommended based on proximity and rating.

---

### 💬 Epic: Chat & Notifications (`epic/chat`)

#### User Stories
- **[8 pts]** `In-App Chat`: As a user, I want to message matched users within the app.
- **[5 pts]** `Push Notifications`: As a user, I want to get notified of new messages and task updates.

---

### 💳 Epic: Payments (`epic/payments`)

#### User Stories
- **[6 pts]** `Stripe Connect`: As a user, I want to connect my account to Stripe for payments and payouts.
- **[5 pts]** `Pre-Payment`: As a poster, I want to pay in advance for the task.
- **[5 pts]** `Payout to Tasker`: As a tasker, I want to receive payment after task completion.

---

### ⭐ Epic: Ratings & Reviews (`epic/ratings`)

#### User Stories
- **[3 pts]** `Rate Tasker`: As a poster, I want to rate a tasker after task completion.
- **[3 pts]** `Rate Poster`: As a tasker, I want to rate the poster.
- **[2 pts]** `Display Ratings`: As a user, I want to see average ratings on user profiles.

---

### 🛠️ Epic: Admin & QA (`epic/admin`)

#### Features
- **[5 pts]** `Admin Dashboard`: As an admin, I want to view and manage users, tasks, and flagged content.
- **[3 pts]** `Moderate Reports`: As an admin, I want to delete or block inappropriate content.

#### Chores
- **[4 pts]** `QA Test Plan`: Manual test plan for key flows like signup, task posting, and payment.
- **[3 pts]** `Analytics Integration`: Add Mixpanel or Amplitude for tracking engagement.
- **[3 pts]** `CI/CD Setup`: Configure CI/CD for dev, staging, and production.

---

## 🗓️ Sprint Plan

### ✅ Sprint 0 – Setup & Planning (Week 0)
- Setup repos, CI/CD
- Define architecture and routes
- UX wireframes for onboarding and task flow

---

### 🚀 Sprint 1 – Onboarding (Week 1–2)
- Signup
- Login session
- Email verification
- Profile setup
- Email templates

---

### 🚀 Sprint 2 – Tasks (Week 3–4)
- Task posting
- Task browsing
- Accept task
- Filter by location & category

---

### 🚀 Sprint 3 – Matching & Messaging (Week 5–6)
- Auto-matching logic
- In-app chat
- Push notifications

---

### 🚀 Sprint 4 – Payments (Week 7–8)
- Stripe connect
- Pre-payment handling
- Tasker payout
- Basic transaction logs

---

### 🚀 Sprint 5 – Ratings & Admin (Week 9–10)
- Post-task ratings
- User profile ratings display
- Admin dashboard and report moderation

---

### 🚀 Sprint 6 – Launch Prep (Week 11–12)
- QA testing and bug fixes
- Analytics and basic dashboards
- Final security audit
- Launch to closed beta

---

## ✅ Optional Enhancements (Post-MVP)
- Task cancellation / refund flows
- Referral / invite system
- Repeat task scheduling
- Student badge verification
- iOS/Android native wrapper

