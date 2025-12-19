---
layout: project
type: project
image: img/vacay/vacay-square.png
title: "Study Buddy"
date: 2025-12-18
published: true
labels:
  - Web Development
  - React
  - Next.js
  - TypeScript
  - PostgreSQL
  - Software Engineering
summary: "A collaborative web application for UH Manoa ICS students to organize in-person study sessions in ICSpace."
---

<img class="img-fluid" src="../img/image.jpg">

## Overview

Study Buddy is a web application developed for ICS 314 (Software Engineering) that helps University of Hawaii at Manoa ICS students self-organize in-person study sessions in ICSpace. The platform addresses a critical problem: ICS students often spend more time than necessary on homework and fail to learn as effectively as they could because they study alone and don't leverage the power of face-to-face peer study groups.

The application connects students seeking help with those willing to provide assistance, promoting collaborative learning in a structured, safe environment. Students can create two types of sessions: planned group study sessions scheduled for later, or immediate "Right Now!" sessions for spontaneous collaboration when they're already in ICSpace.

## My Contributions

As one of three team members (alongside Brandon Nguyen and Caleb Zerbe), I contributed to several key aspects of the project:

**Frontend Development:** I designed and implemented user interface components using React and Next.js, focusing on creating a clean and intuitive user experience. This included developing reusable components like course selection dropdowns, session creation forms, and the study session browsing interface that we used consistently across multiple pages.

**Design and User Experience:** I took a leading role in establishing visual design patterns for the application using Bootstrap. By maintaining consistent design patterns throughout the site—such as standardized button styles, form layouts, and color schemes—I ensured users would have a familiar and comfortable experience across all pages.

**Database Integration:** I worked with PostgreSQL and Prisma ORM to connect frontend components to our backend data collections, ensuring that study sessions, user profiles, and course information were properly stored and retrieved. This involved designing database schemas and implementing efficient queries.

**Team Collaboration:** Working through Issue Driven Project Management (IDPM), I managed GitHub issues, created feature branches, conducted code reviews, and collaborated through pull requests. We organized our development into three milestones, tracking all work transparently on project boards.

## What I Learned

This project was an invaluable learning experience that taught me lessons extending far beyond web development:

**Modern Web Technologies:** This was my first experience with Next.js, TypeScript, and PostgreSQL in a real application. Learning how Next.js handles routing, server-side rendering, and API routes gave me a deeper understanding of modern web architecture. TypeScript's type safety caught numerous bugs during development that would have been runtime errors in plain JavaScript.

**Agile Project Management:** Working with Issue Driven Project Management (IDPM) taught me how to break down complex features into manageable tasks, track progress transparently, and adapt to changing requirements. Each task was implemented on a branch named issue-XX, reviewed by teammates, then merged to main. This systematic approach prevented the chaos of everyone working directly on main.

**Database Design and ORM:** Using Prisma with PostgreSQL taught me about relational database design, migrations, and how ORMs abstract database operations while maintaining type safety. Designing schemas for Profiles, Courses, Sessions, and Points collections required thinking about relationships, constraints, and data integrity.

**Team Collaboration:** Working as a three-person team using GitHub taught me about branching strategies, pull requests, code reviews, and merge conflict resolution. I learned that good communication prevents problems and that reviewing teammates' code helps everyone write better code.

**User-Centered Design:** Gathering community feedback from fellow UHM ICS students taught me the importance of real user testing. Their feedback about navigation issues and UI clarity directly shaped our improvements in Milestone 3. Building for real users—not just for a grade—changed how I thought about every feature.

**Authentication and Security:** Implementing Google OAuth for UH-affiliated login taught me about secure authentication flows, protecting user data, and why features like requiring ICSpace meetings help create a safe environment.

## Technical Stack

- **Framework:** Next.js (React framework with server-side rendering)
- **Language:** TypeScript for both frontend and backend
- **Database:** PostgreSQL with Prisma ORM
- **Styling:** Bootstrap 5 for responsive design
- **Authentication:** Google OAuth (UH email required)
- **Integrations:** Google Calendar API, Slack notifications
- **Deployment:** Vercel
- **Code Quality:** ESLint and Prettier for standardization
- **Testing:** Playwright for end-to-end testing
- **Version Control:** Git and GitHub with IDPM workflow

## Key Features

**For Students:**
- Profile management with "sensei" (can help) and "grasshopper" (need help) course designations
- Create planned study sessions or immediate "Right Now!" sessions
- Browse and RSVP to all available sessions
- Calendar view of upcoming sessions
- Gamification with points, levels, and leaderboards to motivate participation

**For Administrators:**
- Create sessions on behalf of users
- Manage and delete any session
- Monitor behavior and handle inappropriate use reports
- Distribute rewards to top-performing students

**Security and Privacy:**
- UH-affiliated login required (Google OAuth with @hawaii.edu)
- All meetings must occur in ICSpace for safety
- No guest browsing of user data

## Links

- **Live Application:** [https://study-buddy-flax-ten.vercel.app/](https://study-buddy-flax-ten.vercel.app/)
- **GitHub Repository:** [https://github.com/Study-Buddy-G2S6/study-buddy](https://github.com/Study-Buddy-G2S6/study-buddy)
- **Project Documentation:** [https://study-buddy-g2s6.github.io](https://study-buddy-g2s6.github.io)
- **GitHub Organization:** [Study-Buddy-G2S6](https://github.com/Study-Buddy-G2S6)

The project repository includes comprehensive documentation, setup instructions, developer guide, and our complete development history organized across three milestones showing how we built this application from concept to deployment.
