## Description: 
**This is a prompt for creating multiple-choice questions (MCQs) using GPT-4, which includes the option to select the Bloom's taxonomy level of the MCQ. If you have access to ChatGPT plugins you can get a link reader plugin and paste a link at the end of the prompt. Otherwise you can just copy and paste a text at the end.**

**Not every question, response alternative, or feedback will be a winner. Be the human-in-the-loop by selecting, re-running and curating the output.**

### Prompt:
I want you to act as an expert tutor. I will provide a text, and it will be your job to create a number of multiple-choice questions (MCQs) for university students to use as practice questions to learn about the content of the text. The multiple-choice questions should have three response alternatives, of which 1 is correct, and 2 are lures. You should also provide corrective feedback to each alternative.

When creating the MCQs follow these rules:

Rules for the questions:
<br>(1) The question should not be about really specific details such as exact numbers.
<br>(2) Do not refer to the text, the question should be about the concepts in the text, not about the text itself.

Rules for response alternatives:
<br>(1) The correct response alternative must be hard to guess for an individual who does not know the answer to the question.
<br>(2) The correct response alternative must be easy to detect for an individual who knows the answer to the question.
<br>(3) When possible, the lure alternatives should target common misconceptions about the concept that the question is about.
<br>(4) Avoid words like "always" and "never" in the alternatives.

Rules for the feedback:
<br>(1) Do not refer to the text, the feedback should be about the concepts in the text, not about the text itself.

General rules:
<br>(1) The question, alternatives and feedback should be set to reflect a level on Bloom's revised taxonomy of educational learning objectives. I will set the level when asking you to create the question. I will do it by writing for example [Bloom = Analysis].

The output should follow this format and each output heading should be bolded:

Question:
<br>Alternative A (correct):
<br>Feedback A (correct):
<br>
<br>Alternative B (lure):
<br>Feedback B (lure):
<br>
<br>Alternative C (lure):
<br>Feedback C (lure):

Now, create 1 MCQs [Bloom = Analysis], based on the following text:
<br>**[Insert your text here]**
