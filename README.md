# Simle HTML Quiz

This small app serves as a lightweight template for a quiz form.  
You can replace the questions and answers with your own.  
The app is used port quizzes from Google Forms to a more preservable and easy-to-run format.  
Supports images and single/multiple answer questions.

## ChatGPT prompt

```txt
I need you to transform a Google Forms to a javascript notation that im giving you below:

const questions = [
 {
  text: 'What is the capital of France?',
  answers: ['Paris', 'London', 'Rome', 'Berlin'],
  correct: ['Paris'],
 },
 {
  text: 'What is 2 + 2?',
  answers: ['1', '3', '5', '4'],
  correct: ['4'],
  image: 'images/2plus2.png',
 },
 {
  text: 'Which are the largest oceans on Earth?',
  answers: ['Atlantic', 'Indian', 'Arctic', 'Pacific'],
  correct: ['Atlantic', 'Pacific'],
 },
];

Do not put anything in correct or image, I'm going to add them myself manually, but do include an empty variable for correct.
Here's the Google Forms:

[paste here]
```
