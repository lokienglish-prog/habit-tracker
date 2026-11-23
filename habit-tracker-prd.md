# PRD: Habit Tracking App

**Status:** Draft · **Date:** 2026-11-17 · **Version:** 0.1

## 1. Overview
A simple, motivating mobile app that helps people build good habits and break bad ones through daily check-ins, streaks, reminders and progress insights.

## 2. Problem Statement
Most people abandon new habits within the first few weeks. Existing trackers are either too complex (heavy setup, cluttered dashboards) or too shallow (no insight into why habits fail). Users need a low-friction way to log habits and clear feedback that keeps them going.

## 3. Goals
- Make logging a habit take under 3 seconds.
- Increase 30-day habit retention through streaks, reminders and gentle nudges.
- Give users clear, visual insight into their consistency over time.

### Non-Goals (v1)
- Social feeds or public leaderboards.
- Coaching content or paid programs.
- Wearable / health-platform integrations.

## 4. Target Users
- **The Self-Improver:** wants to build 2–5 daily routines (exercise, reading, meditation).
- **The Quitter:** wants to reduce a bad habit (smoking, doom-scrolling) and track days clean.
- **The Busy Professional:** needs quick logging and smart reminders that fit a packed schedule.

## 5. User Stories
1. As a user, I can create a habit with a name, icon, color and schedule (daily, specific weekdays, or X times per week).
2. As a user, I can mark a habit complete with one tap from the home screen.
3. As a user, I can see my current and longest streak for each habit.
4. As a user, I can set reminders at a chosen time for each habit.
5. As a user, I can view a calendar heatmap of my completion history.
6. As a user, I can track "avoid" habits that count days since the last slip.
7. As a user, I can add a short note when I complete or skip a habit.
8. As a user, I can pause a habit (e.g. while travelling) without losing my streak.

## 6. Functional Requirements
| ID | Requirement | Priority |
|----|-------------|----------|
| F1 | Create, edit, archive and delete habits | P0 |
| F2 | One-tap completion on Today screen | P0 |
| F3 | Flexible schedules (daily, weekdays, X/week) | P0 |
| F4 | Streak calculation (current & best) | P0 |
| F5 | Local push reminders per habit | P0 |
| F6 | Calendar heatmap & weekly/monthly stats | P1 |
| F7 | "Avoid" habits with days-since counter | P1 |
| F8 | Notes on check-ins | P1 |
| F9 | Pause / vacation mode | P2 |
| F10 | Home-screen widget | P2 |
| F11 | Cloud sync & account backup | P2 |

## 7. Non-Functional Requirements
- **Performance:** app opens to Today screen in < 1 second.
- **Offline-first:** all logging works without a connection; sync when online.
- **Privacy:** habit data stays on device by default; no third-party ad tracking.
- **Accessibility:** WCAG 2.2 AA, Dynamic Type, VoiceOver/TalkBack support.
- **Platforms:** iOS 17+ and Android 12+.

## 8. Key Screens
- **Onboarding:** pick 1–3 starter habits from templates.
- **Today:** list of today's habits with one-tap check-off and progress ring.
- **Habit Detail:** streaks, heatmap, completion rate, notes.
- **Add/Edit Habit:** name, icon, color, schedule, reminder.
- **Stats:** overall consistency across all habits.
- **Settings:** notifications, theme, data export, backup.

## 9. Success Metrics
- **Activation:** 70% of new users create at least one habit on day 1.
- **Engagement:** average 5+ check-in days per week among active users.
- **Retention:** 35% D30 retention.
- **Satisfaction:** App Store rating ≥ 4.6.

## 10. Release Plan
- **MVP (Month 1–2):** F1–F5.
- **v1.1 (Month 3):** F6–F8.
- **v1.2 (Month 4+):** F9–F11.

## 11. Risks & Open Questions
- How strict should streaks be? (Grace days vs. hard resets.)
- Monetization: freemium with premium stats/sync, or one-time purchase?
- Notification fatigue: how do we avoid users disabling reminders?
