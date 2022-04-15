We have some JSON file, e.g.:

{
 "data": [
  {question: "How old are you?", id: 1},
  {question: "What is your name?", id: 2},
  {question: "Where do you live?", id: 3},
  {question: "What is your favorite color?", id: 4},
  {question: "Do you have a pet?", id: 5},
  {question: "What is yor favorite music?", id: 6},
 ]
}

The task is to make a page with questions. Each question must have the input so user could answer them. At the bottom of the page make a submit button, by tapping on which all the answers will be saved as an object (the format question:answer) in localStorage. Questions and input forms should generate automatically based on JSON file.