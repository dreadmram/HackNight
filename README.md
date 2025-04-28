# HackNight
Submission for Hack@Night
# 🥑 MealFit: My AI Nutrition Chatbot Project

## Inspiration

I wanted to create a simple, fun, and interactive way for people to quickly find out the nutritional information about what they're eating. The idea came to me because I noticed that while there are many apps out there, most feel too heavy or complicated. I thought: what if tracking your meals felt as easy as chatting with a friend?

## What I Built

I built **MealFit**, an AI-powered chatbot that:
- Asks what you are eating.
- Responds with calories, protein, carbs, and fat data.
- Visually shows your macronutrient breakdown using a doughnut chart.
- Speaks back the nutrition information using Text-to-Speech.
- Provides interesting food facts when you ask about the food's history.
- Sends recipe links if you ask for recipes!

The design uses clean and modern aesthetics powered by Tailwind CSS, while Chart.js makes the nutrition breakdown easy to understand at a glance.

## How I Built It

I used:
- **HTML**, **CSS** (Tailwind), and **JavaScript**.
- **Nutritionix API** to fetch live nutrition data.
- **Web Speech API** for human-like voice reading.
- **Chart.js** to build dynamic, colorful nutrition charts.

Everything is frontend-only — no backend server required (but I plan to add one for security later).

## What I Learned

- How to work with third-party APIs like Nutritionix.
- How to integrate charts dynamically with Chart.js.
- How to make web apps talk using the Web Speech API.
- Better UI/UX practices using Tailwind CSS.
- How to parse and clean HTML into readable text for speech output.

## Challenges I Faced

- Finding a free nutrition API that worked reliably without expensive plans.
- Handling unexpected foods or misspellings in user input.
- Balancing design aesthetics with functionality.
- Managing multiple features (speech, charts, facts, recipes) without cluttering the UI.

## What's Next

- Add user authentication to save meal history.
- Create a "favorite meals" feature.
- Integrate a calorie goal tracker and achievement badges.
- Polish the voice even further by letting users customize tone/speed.

---

> **MealFit** isn't just another meal tracker — it's your smart, friendly assistant for better eating! 🥗🤖
