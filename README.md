# Notion iOS Reverse Engineering

This project is a reverse-engineering analysis of the Notion mobile app (iOS version). It was done as part of a design system recovery and documentation task for my team project .


## About the Project

The goal was to study a real app similar to the one I’m planning to build, and break it down into its features, UI structure, and logic. I picked Notion because of its flexible layout system, nested pages, and block-based content — all things that relate closely to what I want to make.
(58301)

## Technologies I Would Use to Rebuild It

| Layer        | Tech Stack                            |
|--------------|----------------------------------------|
| Frontend     | Flutter (or React Native if needed)    |
| Backend      | Firebase (Firestore, Auth, Storage)    |
| Realtime     | Firestore Realtime updates             |
| State Mgmt   | Riverpod (or Redux Toolkit in RN)      |
| Storage      | Firebase Storage for uploads           |

These choices are based on speed, cross-platform support, and tools I already know.

## What’s Inside

This repo includes all parts of the assignment:

- `docs/report.pdf` – full written report (structure, screens, effort estimates, prompts)
- `diagrams/navigation-map.svg` – flow diagram of the app
- `prompts/ai-prompts.md` – AI prompts for Copilot or Cursor
- `screenshots/` – screen references from the Notion app
- `README.md` – this file

## How This Helps

Doing this helped me learn how to break apps into systems, plan out MVPs, and write better prompts for AI tools. It also made me more aware of what’s realistic to build in a short time and where complexity can sneak in.

## License

This is a study project, not affiliated with Notion Labs. All screenshots are used for educational purposes.
