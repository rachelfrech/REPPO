# REPPO
REPPO is an AI-powered strength training app that turns workout history into personalized recommendations. Track sets, reps, weight, and difficulty, then use AI to understand your progress, adjust workouts, and decide what to do next all within an extremely simple, non cluttered UI.

# Why I'm Building REPPO

I'm a product manager exploring how AI-assisted software development can change the way products are conceived, built, and iterated.
I'm building REPPO to develop a deeper understanding of software development by taking a product from **idea → requirements → technical decisions → development → testing → iteration → launch**. Rather than using AI to simply generate an application, my goal is to use AI development tools as collaborators while learning the concepts behind the product I'm building. Through REPPO, I want to become more technically fluent as a product manager and better understand the decisions, tradeoffs, and challenges involved in turning a product idea into working software.

## The Problem

Strength training apps are great at recording workouts, but they often leave the user responsible for what to do next and when. they are often cluttered and cumbersome. I'm setting out to build Reppo for my own personal needs.

After a workout, users still have to answer questions like:

* Should I increase the weight next time?
* Should I add more reps or stay where I am?
* Am I actually getting stronger?
* Is this exercise still challenging enough?
* Should my next workout change based on how the last one felt?
* How should I adjust my workout if I only have 30 minutes today?
* What should I substitute if a machine or piece of equipment isn't available?

For people who don't have a personal trainer, making these decisions consistently can take up a lot of mental load.

## The Target User

REPPO is initially designed for recreational strength trainers who want structured, progressive workouts without hiring a personal trainer.

The target user:
* Strength trains regularly
* Wants to become stronger or improve body composition
* Tracks weights, reps, and sets over tiem
* Understands basic exercises but isn't an expert in programming workouts
* Wants guidance on when and how to progress
* May have changing time, equipment, or workout constraints
* Wants to understand their progress without manually analyzing workout history
* Wants an extremely straightforward, simple interface


## The Product Vision

REPPO acts as a training companion that learns from each workout.
A user logs:
**What they did**
> Shoulder Press
> 3 sets × 10 reps × 50 lbs
**How it felt**
> Moderate difficulty

REPPO remembers that performance and uses it when the exercise appears again. Over time, REPPO could identify patterns such as:
> You've completed 3 × 10 at 50 lbs twice and rated both sessions as moderate. Try 55 lbs during your next session.
The goal is to move fitness tracking from:
**"Here's what you did."**
to:
**"Here's what you should do next, and why."**

## MVP
The first version of REPPO will focus on proving one core experience:

### 1. Create a Workout
Users can create or select a workout containing multiple exercises from a library. Users can generate a workout via AI based on composition goals, equipment availability, workout duration, and workout frequency.
### 2. Log a Workout
For each exercise, users can record:
* Exercise
* Sets
* Reps
* Weight
* Difficulty / perceived effort
* Optional notes
### 3. View Workout History
Users can see previous workouts and exercise performance over time.
### 4. Receive an AI Recommendation
REPPO uses previous workout performance and user feedback to recommend what the user should do the next time they perform an exercise.
For example:
> **Last workout**
> Squat: 3 × 8 @ 90 lbs
> Difficulty: Challenging

> **REPPO recommends**
> Stay at 90 lbs and aim for 3 × 9 before increasing weight.

### 5. Modify a Workout
Users can tell REPPO about a constraint such as:
> "I only have 30 minutes today." or  "The cable machine is taken."
REPPO can recommend how to adjust the planned workout while preserving its overall training goal.

## Not in the MVP
REPPO could eventually become a much larger fitness platform, but the first version will intentionally not attempt to solve everything.

Initial exclusions include:

* Nutrition tracking
* Calorie tracking
* Social feeds
* Trainer marketplaces
* Wearable integrations
* Apple Health integration
* Strava integration
* Advanced recovery tracking
* Sleep tracking
* Video-based form analysis

These may be explored after validating the core workout tracking and recommendation experience.

## Future Opportunities
Potential future REPPO capabilities include:

### Adaptive Programming
Automatically adjust upcoming workouts based on previous performance.
### Progress Insights
Identify trends such as strength improvements, plateaus, training consistency, and exercise volume.
### Conversational Fitness History
Allow users to ask questions such as:
> "How much stronger have my legs gotten in the last three months?"
> "What exercises haven't I progressed on recently?"
> "What weight did I use the last time I did Bulgarian split squats?"
### Wearable & Health Integrations
Potentially incorporate recovery, sleep, heart rate, activity, and other signals from platforms such as Apple Health or fitness wearables.

## Product Principles

### Personalized, Not Generic
Recommendations should be grounded in the user's actual workout history whenever possible.
### Explain the Why
REPPO shouldn't just tell users what to do. It should explain why it is making a recommendation.
### Keep Logging Fast
AI should make workout tracking easier, not create additional work.
### Progress Over Perfection
The product should help users make small, sustainable improvements over time.
### AI as a Coach, Not Just a Chatbot
AI should be integrated into the product experience rather than existing as a generic chat window disconnected from workout data.
## Success Criteria for the MVP
The MVP will be considered successful if a user can:

1. Create a workout
2. Complete and log that workout
3. Return later and view their previous performance
4. Receive a recommendation based on that performance for future workout
5. Use that recommendation to inform their next workout
6. Conversational AI to swap exercises, modify workouts
7. Calendar for dragging populated workouts


## Current Status 🚧 **In development**

### Current Phase

**Phase 1: Product definition and technical planning**

Next steps:

* [ ] Define the core MVP user journey
* [ ] Create initial wireframes
* [ ] Determine technical architecture
* [ ] Set up the development environment
* [ ] Build the first working version
* [ ] Test with real workout data
* [ ] Iterate based on usage and feedback
* [ ] Deploy REPPO
