# StoryBuddy MVP – Peblo Mobile App Developer Challenge

## Candidate

Pattan Tasneem

## Overview

StoryBuddy is a child-friendly mobile application that combines story narration with an interactive quiz experience. The application is designed to provide a joyful learning journey for children using an AI Buddy character named Pip.

## Framework

Expo React Native

## Features

### AI Buddy

* Friendly robot mascot (Pip)
* Animated idle and success states

### Story Narration

* Text-to-Speech narration
* Loading state
* Playback state
* Error handling with retry support

### Data-Driven Quiz

Quiz content is served through backend APIs and rendered dynamically. The application supports varying numbers of answer choices without requiring UI code changes.

### Feedback System

Wrong Answer:

* Shake animation
* Haptic feedback
* Retry support

Correct Answer:

* Confetti animation
* Success haptic feedback
* Smiling buddy state

## Backend APIs

* GET /api/story
* GET /api/quiz

## State Flow

Idle → Loading → Narrating → Quiz → Success/Error

## Performance Optimizations

* Lightweight assets
* Optimized animations
* Efficient state updates
* Suitable for mid-range Android devices

## Future Improvements

* Multiple stories and quizzes
* User progress tracking
* Reward and streak system
* Enhanced animated mascot

## AI Usage & Judgment

AI-assisted development tools were used to accelerate prototyping and UI generation. Suggestions were reviewed and adapted to meet the assignment requirements and child-friendly design goals.
