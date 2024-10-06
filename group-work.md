# Small Group Work
## Simple Quiz Using `if-elif-else` Statements

### Directions
> Work with your assigned group
>
> Contribute to the success of your group by doing your fair share of the work
>
> **Actively** participate in class and small group discussions
> 

---

### Today's Assignment

- Write a script for a four-question quiz
- Format each question as shown in the example below
- Use the `elif` statement to give the user some feedback when they don't enter the correct answer
- Reminder: Choose **one-word** answers for each question (because it's easier to check if the user answered the question correctly or not)
- Be prepared to show and discuss your group's code with the rest of the class

```python

  # A simple quiz that checks a user's answer and gives the user some feedback
  # if their answer is not correct

  question1 = "What is the capital of France?"
  correct_answer1 = "Paris"

  user_answer1 = input(question1)

  if user_answer1.lower() == correct_answer1.lower():
    print("Correct!")
  elif user_answer1.lower() == "London":
    print("Close, but the capital of France is actually Paris.")
  else:
    print("Try again.")

```
---




