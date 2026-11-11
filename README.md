# LiftLog

A workout tracking app that helps weightlifers log sessions, find exercises, track progress. 

## Overview

Many beginner lifters track progress using mental notes or unoptimized note apps/paper. This method can make tracking improvements over time difficult and confusing. LiftLog gives lifters of all levels a fast, structured, and easy way to log workouts and discover new exercises. 

## Features

- Create and save custom workouts
- Log sets, repetitions, and weight during a session
- Browse a database of exercises with the ability to filter based on muscle group
- Add exercises to a workout in just a few taps
- Find exercises with an interactive muscle group finder

## Tech Stack

- Language: Dart - Native language for the Flutter framework, compiles native code for fast performance on different operating systems (iOS and Android)
- Framework: Flutter - for cross-platform compatability across iPhone, Android, macOS, Windows, etc
- Storage: SQLite - Local storage for user created workouts to allow offline use

## Getting Started

1. Clone the repository: `git clone https://github.com/ewhitehead1/LiftLog.git`.
2. Open the project in [VS Code].
3. Ensure Flutter is installed.
4. Download project dependencies `flutter pub get`.
5. Run using Flutter `flutter run`.

## My Contributions

Started as a collaborative project with a team of four other students. Since December 5, 2025 I have been the sole developer of this project, my work includes: 

- Designed and created SQLite Database
- Built a database helper layer that handles all SQLite queries to enable UI screens to call simple methods
- Implemented workout list screen
- Implemented single workout screen

See the commit history (https://github.com/ewhitehead1/LiftLog/commits?author=ewhitehead1)

## Future Roadmap

- Integration with Apple Health
- Exercise photo/video demontrations
- Improved UI