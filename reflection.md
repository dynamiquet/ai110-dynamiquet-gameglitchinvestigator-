# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
  - The interface looked fine and generally it looked pretty good except for some hidden bugs
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").
  - It was very inaccurate whether it chose to say "GO HIGHER" or "GO LOWER
  - It seems to reward (in score) some wrong attempts, especially when the attempt is higher than the correct answer
  - After winning and starting a new game, "Submit" seems to not be working

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
 - I used Claude Code
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
  - It suggested that the suggestion to go higher or go lower in the initial implementation was reversed
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
  - It claimed that the interval range displayed for different difficulty levels were hardcoded and all the same (i.e 1-100) instead of changing as the user selects different difficulty levels. This was not the case on the webpage.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
 - I played around with the game by exploring standard and edge cases to see if they worked as expected
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
