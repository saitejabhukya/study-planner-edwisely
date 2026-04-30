# Personalized Weekly Study Planner
### Problem ID: 6 | Edwisely Hackathon

## Problem
Students plan studies randomly, ignoring weak areas and upcoming exams.
This leads to poor conceptual understanding and last-minute cramming.

## My Solution
An AI-powered study planner that creates a personalized weekly schedule.

## How It Works
1. Student enters subjects, exam dates, confidence level, difficulty
2. AI calculates Priority Score for each subject
3. System generates day-by-day study plan for the full week
4. LLM provides study tips and explains scheduling decisions

## Priority Score Formula
Priority Score = (Weakness x 3) + (Difficulty x 2) + (Exam Urgency x 5)

Example:
- Maths: Weak(9) + Hard(6) + Urgent(15) = Score 30 → Most hours
- English: Strong(3) + Easy(2) + Far(5) = Score 10 → Least hours

## Key Features
- Smart prioritization of weak subjects
- Balanced daily schedule (no burnout)
- Color coded weekly calendar (Red=Weak, Orange=Medium, Green=Strong)
- 2-day pre-exam revision mode automatically triggered
- AI generated study tips per subject
- Suspicious behavior detection system

## Screens Designed
1. Welcome Screen
2. Student Input Form
3. AI Processing Screen (shows Priority Score calculating)
4. Weekly Plan View (color coded calendar)
5. AI Explanation and Study Tips

## LLM Validation
Tested with ChatGPT using real student data:
- Maths (Weak, Hard, exam May 8) → assigned 2.5 hrs/day
- Chemistry (Weak, Hard, exam May 10) → assigned 1.5 hrs/day  
- English (Strong, Easy, exam May 15) → assigned least time
Result confirmed my Priority Score formula works correctly.

## Suspicious Behavior Detection
- Tracks time spent per topic
- Flags if all topics marked complete too quickly
- Random concept check questions after each session
- Compares patterns with peer average
- Session timestamps logged to detect impossible completion times

## Tech Stack
- Frontend: JavaScript / ReactJS
- Backend: Python
- LLM: ChatGPT API
- Design: Figma

## Wireframe

<img width="915" height="654" alt="ed1" src="https://github.com/user-attachments/assets/12ec1e40-ec2a-4649-8df1-c4664721ee10" />

<img width="907" height="575" alt="ed2" src="https://github.com/user-attachments/assets/3778507c-62d6-49ac-8e42-9f6f313f1462" />

<img width="917" height="434" alt="ed3" src="https://github.com/user-attachments/assets/053ba0b7-f094-4bb3-a683-8e2419a8eb25" />

<img width="982" height="723" alt="image" src="https://github.com/user-attachments/assets/ecafa0c7-6c4f-45df-a685-2078057dacd9" />


## Video Walkthrough
[Add your Loom link here]
