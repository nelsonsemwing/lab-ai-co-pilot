![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | The AI Assistant Trials, who’s the Best Co-Pilot?

> :test_tube: Focus: Critical AI comparison, Prompt Engineering, Output Review

## :brain: Scenario

Your dev team is considering integrating an AI assistant into your daily workflow, but which one fits best?

You’ve been tasked with leading **“The AI Assistant Trials”**, a side-by-side comparison between:

-  **ChatGPT (Free)**  
-  **Claude (Free)**  
-  **Your pick** (if you use another AI tool like Gemini or so)

You’ll evaluate each AI by giving them the same set of coding challenges and analysing their responses.

<br />

## :dart: Learning Goals

By completing this lab, you will:

:white_check_mark: Compare AI assistants on real-world tasks   <br>
:white_check_mark: Practice prompt clarity and iteration   <br>
:white_check_mark: Learn how to critically evaluate AI suggestions   <br>
:white_check_mark: Choose the best assistant for your own dev flow

<br />

<br>

## Requirements

- Fork this repo.
- Clone this repo.

<br>

## Submission

- Upon completion, run the following commands:

```bash
git add .
git commit -m "Solved lab"
git push origin master
```

- Create a Pull Request so that your work can be checked.

<br>

## :test_tube: Tasks

Perform **3 challenges** with each AI. You must use the **same prompt** for all three.

### :white_check_mark: Task 1: Explain a Function

**Prompt:**  
> “Explain this JavaScript function in detail. Add comments as needed.”

```js
function mysteryOp(arr) {
  return arr.reduce((acc, val) => acc ^ val, 0);
}
```

<br />

### :white_check_mark: Task 2: DOM Manipulation

**Prompt:**  
> “Write a function that changes the text of an HTML element with id `status` when a button is clicked. Use vanilla JavaScript and follow accessibility best practices.”

<br />

### :white_check_mark: Task 3: Refactor Obfuscated Code

**Prompt:**  
> “Refactor this function to make it readable and efficient. Add meaningful variable names and comments.”

```js
function r(a){let b=0;for(let i=0;i<a.length;i++){if(a[i]%2===0){b+=a[i]}}return b}
```

<br />

## :bar_chart: AI Evaluation Table

| AI Tool   | Task | Clarity (1–5) | Accuracy (1–5) | Speed (1–5) | Tone (1–5) | Notes |
|------------|------|----------------|----------------|--------------|-------------|-------|
| ChatGPT    | 1    | 5              | 5              | 5            | 5           | Very clear explanation |
| ChatGPT    | 2    | 5              | 5              | 5            | 5           | Clean DOM solution |
| ChatGPT    | 3    | 5              | 5              | 5            | 5           | Good refactor |
| Claude     | 1    | ...            | ...            | ...          | ...         | ... |
| Claude     | 2    | ...            | ...            | ...          | ...         | ... |
| Claude     | 3    | ...            | ...            | ...          | ...         | ... |

> 💡 Don’t just give scores write down what stood out.  
> Was one clearer, but verbose? Another too short but correct?

<br />

# AI Assistant Trials – Final Report

## 🏆 My Pick:
ChatGPT

---

## ✅ Pros & Cons

### ChatGPT
- ✅ Clear, simple, and beginner-friendly explanations  
- ✅ Fast and practical solutions  
- ❌ Sometimes less detailed for advanced explanations  

### Claude
- ✅ Very detailed and structured answers  
- ❌ Can be too long and less direct  

### My Pick (ChatGPT)
- ✅ Best balance of clarity and speed  
- ❌ Slightly less deep explanations compared to Claude  

---

## 📌 Task-by-Task Highlights

- Task 1: ChatGPT explained the function clearly and simply, Claude was more detailed but harder to read quickly.
- Task 2: ChatGPT gave a clean and accessible DOM solution, very easy to understand.
- Task 3: Both ChatGPT and Claude worked correctly, but ChatGPT was more readable and beginner-friendly.

---

## 🔍 Surprises & Bugs

- Claude sometimes gave overly long explanations that were correct but not efficient.
- ChatGPT was more concise and easier to apply in real coding tasks.
- No major hallucinations or incorrect code from either AI.

---

## 🧠 Final Thoughts

I would trust ChatGPT in a real project because it gives clear, fast, and practical answers that are easy to implement. Claude is better for deep explanation, but ChatGPT fits better for day-to-day coding and learning.

---

## 🧠 Reflection Prompts

- ChatGPT helped me learn better because it was simple and easy to follow.
- Claude gave more detailed explanations but sometimes too complex.
- ChatGPT matched my learning style better because I prefer clear and direct answers.
- I would use different AIs depending on the task: ChatGPT for coding, Claude for deep explanations.

---

## 🔬 Bonus Round

I asked all AI tools:

> “What are 3 common mistakes junior developers make in DOM manipulation, and how can they be avoided?”

- ChatGPT: Clear, simple, and practical advice.
- Claude: Very detailed but slightly long.
- My Pick: ChatGPT because it was easiest to understand and apply quickly.

---

## 🎯 Conclusion

ChatGPT is my preferred AI assistant for coding support because it is fast, clear, and practical for real-world development tasks.
