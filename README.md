# CS-360-16014-M01-Mobile-Architect-Programming-2025

## About
This repository is part of my ongoing CS portfolio. It showcases my work in mobile architecture, Android development, and user-centered design. Included are project artifacts and reflections demonstrating my ability to design a simple, functional app, iterate on UI flows, and prepare a lightweight launch plan.

## Repository Contents

### Inventori Mobile App

**Summary:**
This project focused on building a fast, minimal inventory tracker for small spaces. Users can add items, adjust quantities with plus/minus, and set a low-stock threshold to get a heads-up before running out. The main problem solved is reducing friction in everyday tracking so users don’t miss restocks.

I kept the flow “fast first.” The app opens right to the list for quick taps, fields are simple, and the plus/minus pattern makes updates feel instant. Separation between UI and the basic data operations made the code easier to reason about.

Adding more boundary tests for input validation and edge behaviors (empty names, very large quantities) would harden the app. Persisting data with a structured local store and adding basic instrumentation tests would improve reliability.

Designing the low-stock alert flow without cluttering the UI was tricky. Iterating in small steps, testing interactions as I built them, and trimming extra screens kept the experience focused.

**Tools and resources added to my network:** 
- Android Studio and Android Developer documentation
- Material Design guidelines
- Emulator/device testing notes for UI polish

**Skills transferable to other projects:** 
- Mobile UI flow design for speed and clarity
- Input validation and simple state management
- Planning small, testable increments of work

**How I made this project maintainable, readable, and adaptable:**
Consistent naming, small functions with single purposes, clear comments where logic isn’t obvious, and a simple project structure that keeps UI concerns separate from core logic.

---

### UI Design and App Launch Plan

**Summary:**
This work captured the UI baseline used for the final app and outlined how I’d present the app for release. The goal was to translate user needs into clear screens with minimal steps, then document how the app would be positioned, described, and supported.

I kept screens lean (list-first, quick add/edit) and tied each UI element to a real user action. The store listing copy focuses on the core value: quick updates and low-stock reminders.

More visual artifacts (annotated screen flows or short demos) would speed up reviews and future iterations. A short FAQ and support page would reduce friction after launch.

Balancing “fewer taps” with “enough validation” required tradeoffs. Building from the most common actions and trimming extras helped keep the flow smooth.

**Tools and resources added to my network:**
Android Studio Layout tools
Material 3 components and guidance
Play listing best-practice references for copy and visuals

**Skills transferable to other projects:**  
- Writing concise product copy for listings
- Documenting UI intent and success criteria
- Aligning UX choices with implementation constraints

**How I made this maintainable, readable, and adaptable:**  
Clear sections, short justifications tied to the app screens, and versioned artifacts that match the final build.

---

## Additional Reflections

### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
Inventori helps users keep small inventories under control with quick add/edit, rapid quantity adjustments, and a low-stock alert so they don’t forget to restock.

### What screens and features were necessary to support user needs and produce a user-centered UI? How did your UI designs keep users in mind, and why were they successful?
A list-first home screen, a simple add/edit screen, plus/minus controls, and low-stock thresholds. The design prioritizes speed, clarity, and minimal taps, which makes it successful for everyday use.

### How did you approach the process of coding your app? What techniques or strategies did you use, and how could they be applied in the future?
I worked in small increments, validated behavior as I went, and kept UI logic separate from the basic data operations. The same approach applies to any mobile feature: isolate concerns, ship small, and verify early.

### How did you test to ensure your code was functional? Why is this important, and what did it reveal?
Manual walkthroughs covered item creation, edits, and threshold alerts. This surfaced edge cases around empty inputs and confirmed that core flows remained fast and predictable.

### Considering the full process from initial planning to finalization, where did you have to innovate to overcome a challenge?
I trimmed the UI to the essentials and shaped the alert flow to avoid extra screens. This kept the experience focused while still covering the core need.

### In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The list-first interaction with instant plus/minus updates shows good product judgment: it keeps the most frequent action front and center without extra steps.

---

## Collaborators
For this assignment, I have added my instructor **jdimarzioprof** as a collaborator so they can review my portfolio work.

## Acknowledgments
Thanks to my instructor and classmates for their support and detailed feedback throughout the CS-360 course.

## Contact
For any questions or suggestions, please feel free to open an issue or contact me.
