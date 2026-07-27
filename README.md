# CLAUDE.md

# Developer Profile

## About Me

I am a Software Engineer (Flutter) working at the Bangladesh Army Headquarters (AITSO).

My primary responsibility is developing and maintaining production Flutter applications used in real-world environments.

I focus on:

- Flutter (Dart)
- Clean UI Development
- REST API Integration
- Responsive Design
- Performance Optimization
- Bug Fixing
- Code Refactoring
- Production Ready Code

---

# Tech Stack

## Mobile

- Flutter (Latest Stable)
- Dart

## State Management

Use whichever already exists in the project.

Commonly used:

- Provider
- GetX
- Bloc
- Riverpod

Never introduce a different state management solution unless requested.

---

# Architecture

Projects may use:

- Clean Architecture
- MVVM
- MVC

Always follow the existing architecture.

Never rewrite the architecture.

---

# Code Style

Always write code that is:

- Clean
- Readable
- Reusable
- Modular
- Maintainable

Prefer:

- StatelessWidget whenever possible
- const constructors
- final variables
- composition over duplication

---

# UI Guidelines

I mostly work on UI.

Whenever generating UI:

- Pixel-perfect implementation
- Responsive
- Follow Figma exactly
- Consistent spacing
- Consistent typography
- Proper color usage
- Reusable widgets

Avoid hardcoded values when project constants already exist.

---

# Colors

Use existing project colors.

Prefer:

- AppColors
- Theme
- Color constants

Do not hardcode colors unless requested.

---

# Typography

Use existing typography system.

Prefer:

- AppTextStyles
- Google Fonts
- Theme TextStyles

Avoid inline TextStyle duplication.

---

# Naming

Use meaningful names.

Examples:

AppointmentCard

AppointmentScheduleCard

TimeSlotGrid

DoctorInfoCard

PatientProfileCard

Avoid names like:

Widget1

TestWidget

MyCard2

---

# Folder Structure

Respect existing project structure.

Never move files unless requested.

Never rename folders unless requested.

---

# Performance Rules

Prefer:

const widgets

ListView.builder

GridView.builder

cached widgets

lazy loading

minimal rebuilds

Avoid unnecessary rebuilds.

---

# API Rules

Do not change API contracts.

Do not rename JSON keys.

Do not modify DTOs unless requested.

Preserve API compatibility.

---

# Git Commit Style

Use Conventional Commits.

Examples:

feat(ui): improve appointment schedule card

fix(ui): resolve overflow issue

refactor(widget): simplify appointment card

style(ui): adjust spacing and typography

chore: remove unused imports

---

# Code Quality Rules

Always ensure:

No print()

No debugPrint()

No commented code

No dead code

No duplicated widgets

No unused imports

No unnecessary rebuilds

No magic numbers if constants exist

No force unwrap unless safe

---

# Before Writing Code

Always inspect existing code first.

Follow existing:

- Naming
- Architecture
- Folder structure
- Patterns

Blend into the existing codebase.

---

# Refactoring Rules

When refactoring:

Do not change behavior.

Improve:

- readability
- reusability
- maintainability

Keep logic identical.

---

# UI Review Checklist

Before finishing:

✔ Responsive

✔ Pixel Perfect

✔ Null Safe

✔ Analyzer Clean

✔ No Overflow

✔ No Lint Issues

✔ No Dead Code

✔ Existing Theme Followed

---

# Communication Style

When helping me:

Explain briefly.

Show only the necessary code.

Avoid unnecessary theory.

If there are multiple solutions:

Recommend the most production-ready approach.

---

# Default Assumptions

Unless I explicitly say otherwise:

- Flutter Stable
- Dart Stable
- Production Application
- Clean Code Required
- Enterprise Level Quality
- Maintain Existing Architecture
- Follow Existing Project Conventions

---

# When Reviewing My Code

Check for:

Architecture issues

Performance issues

Widget rebuilds

Code duplication

Naming consistency

Memory leaks

UI consistency

Responsiveness

Accessibility

Null safety

Lint warnings

Unused code

Provide practical improvements rather than theoretical discussions.

---

# Goal

Every code suggestion should be production-ready, scalable, maintainable, and suitable for enterprise Flutter applications used in government and healthcare environments.
