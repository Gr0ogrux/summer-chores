# Assignment: Summer Chores
## Description
This project simulates a series of summer chores that must be completed in a specific order. Using Asynchronous JavaScript, the program handles tasks that take different amounts of time to complete.

To make it more realistic, the script includes logic to simulate the person getting tired. As the day progresses, there is a random chance the person might fall asleep before finishing their tasks.

## The Chore List
The chores are performed in the following strict routine:

1. Mow the Yard (2000ms) - Never fails
2. Weed Eat (1500ms)
3. Trim Hedges (1000ms)
4. Collect Wood (2500ms)
5. Water Garden (500ms)

## Technical Implementation
This project demonstrates two different ways to handle asynchronous operations in JavaScript:

**callbackVersion.js**: Uses nested functions (Callback Hell) to ensure chores execute in the correct order.

**promiseVersion.js**: Uses ES6 Promises and .then() chaining for a cleaner, more readable "flat" structure.

- Simulated Time: Uses setTimeout to represent chore duration.

- Failure Logic: Uses Math.random() to determine if a chore resolves (success) or rejects (falling asleep).

## How to Run
This project is best viewed in a web browser using Live Server to see the full output in the Developer Tools.

1. Open the project in VS Code.

2. Right-click promises.html (for the Promise version) or callback.html (for the Callback version).

3. Select "Open with Live Server".

4. Once the browser opens, press F12 or right-click and select Inspect.

5. Click the Console tab to watch the chores progress in real-time.

## Version History
### 02/17/2026
The original part of this project, including callbackVersion.js and README.md were created.  This project was created to simulate "Callback Hell."

### 02/20/2026
Added promiseVersion.js.  This version of the project was created to replace Callbacks with Promises.  Also added callback.html and promises.html to give users the ability to run the JS files in their web browsers to get more lines of information that running Node.js in the terminal wasn't capable of showing.  Converting to Promises helped solve the "order of operations" issue by allowing a linear chain of events. It made the code much easier to debug because errors can be caught in one place using .catch() rather than checking every single nested function.

## Lessons Learned
What made this assignment particulary difficult was figuring out the "order of operations" and how all of the functions fit together.  It took some time to get all of the functions working together.

## Author
Andy Fields - Student at Code:You