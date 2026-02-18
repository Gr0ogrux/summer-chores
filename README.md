# Callback Assignment: Summer Chores
## Description
This project simulates a series of summer chores that must be completed in a specific order. Using Asynchronous JavaScript (Callbacks), the program handles tasks that take different amounts of time to complete.

To make it more realistic, the script includes logic to simulate the person getting tired. As the day progresses, there is a random chance the person might fall asleep before finishing their tasks.

## The Chore List
The chores are performed in the following strict routine:

1. Mow the Yard (2000ms) - Never fails
2. Weed Eat (1500ms)
3. Trim Hedges (1000ms)
4. Collect Wood (2500ms)
5. Water Garden (500ms)

## Technical Implementation
This version of the project demonstrates "Callback Hell," where functions are nested within one another to ensure they execute in the correct chronological order.

- Uses setTimeout to simulate the time taken for each chore.

- Uses Math.random() to determine if a chore is successfully completed or if the person falls asleep.

## How to Run
1. Ensure you have Node.js installed.

2. Clone this repository:

```bash
git clone https://github.com/Gr0ogrux/summer-chores.git
```

3. Navigate to the project folder:

```Bash
cd summer-chores
```

4. Run the script:

```Bash
node callbackVersion.js
```

## Lessons Learned
What made this assignment particulary difficult was figuring out the "order of operations" and how all of the functions fit together.  It took some time to get all of the functions working together.

## Author
Andy Fields - Student at Code:You