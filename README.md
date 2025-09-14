
# 📖 Prompting Techniques with FlowS

## 📝 Instructive Prompting

Direct, task-oriented instructions.

### Example 1: Essay Writing

```mermaid
flowchart TD
    A[User: Write a 100-word essay on Climate Change] --> B[AI: Understands instruction]
    B --> C[AI: Organizes into Intro, Body, Conclusion]
    C --> D[AI: Generates essay]
    D --> E[Output: 100-word Climate Change essay]
```

### Example 2: Summarization

```mermaid
flowchart TD
    A[User: Summarize this article in 3 bullet points] --> B[AI: Reads & extracts key ideas]
    B --> C[AI: Compresses into 3 concise points]
    C --> D[Output: 3 bullet summary]
```

### Example 3: Formal Email

```mermaid
flowchart TD
    A[User: Convert this text into a formal business email] --> B[AI: Identifies professional tone]
    B --> C[AI: Structures into Greeting, Body, Closing]
    C --> D[Output: Formal email draft]
```

---

## 📚 Informative Prompting

Seeks knowledge, explanation, or definitions.

### Example 1: Simple Explanation

```mermaid
flowchart TD
    A[User: Explain Blockchain in simple words] --> B[AI: Identifies concept]
    B --> C[AI: Removes technical jargon]
    C --> D[AI: Creates easy analogy]
    D --> E[Output: Simple Blockchain explanation]
```

### Example 2: AI vs ML

```mermaid
flowchart TD
    A[User: What are the differences between AI and ML?] --> B[AI: Collects definitions]
    B --> C[AI: Finds similarities & differences]
    C --> D[AI: Organizes into comparison list]
    D --> E[Output: AI vs ML comparison]
```

### Example 3: Real-World Use Cases

```mermaid
flowchart TD
    A[User: Give real-world applications of Big Data] --> B[AI: Searches domains like Healthcare, Finance, Retail]
    B --> C[AI: Selects top 3-5 examples]
    C --> D[AI: Explains each briefly]
    D --> E[Output: List of Big Data applications]
```

---

## 💬 Conversational Prompting

Engages AI like chatting with a mentor or friend.

### Example 1: Trip Planning

```mermaid
flowchart TD
    A[User: Hey, can you help me plan a weekend trip?] --> B[AI: Asks about preferences & budget]
    B --> C[AI: Suggests travel options & activities]
    C --> D[User: Refines based on interests]
    D --> E[Output: Personalized itinerary]
```

### Example 2: Debugging Help

```mermaid
flowchart TD
    A[User: I am stuck in writing code, what should I do?] --> B[AI: Asks for error details]
    B --> C[AI: Suggests debugging steps & examples]
    C --> D[User: Applies fix & reports back]
    D --> E[Output: Resolved code issue]
```

### Example 3: Mentor Guidance

```mermaid
flowchart TD
    A[User: Imagine you are my mentor, guide me for interviews] --> B[AI: Switches to mentor role]
    B --> C[AI: Provides resume tips, FAQs, and confidence advice]
    C --> D[User: Asks follow-up questions]
    D --> E[Output: Interview preparation roadmap]
```

---

## 🎯 Zero-Shot Prompting

No prior examples, just task.

### Example: Translation

```mermaid
flowchart TD
    A[User: Translate 'Good Morning' into Spanish] --> B[AI: Understands task directly]
    B --> C[AI: Uses knowledge base]
    C --> D[Output: Buenos Días]
```

---

## 🎯 Few-Shot Prompting

User provides examples, AI follows pattern.

### Example: Classification

```mermaid
flowchart TD
    A[User: Examples → Cat=Animal, Rose=Flower] --> B[User: Now classify 'Mango']
    B --> C[AI: Learns pattern of classification]
    C --> D[AI: Applies to Mango]
    D --> E[Output: Fruit]
```

---

## ✅ Best Practices Checklist

### Normal Prompts

* 🎯 Be **specific**
* 🏗️ Define **structure** (list, table, code, essay)
* 🎨 Set **tone/style** (formal, casual, creative)
* ⏳ Add **constraints** (word limit, step-by-step)
* 📚 Provide **context** (background info helps accuracy)

### Claude Prompts

* 👤 Use **role-based prompting** (“You are a career coach…”)
* 🧠 Ask for **step-by-step reasoning** (“Think carefully before answering…”)
* 🏗️ Give **structured instructions** (headings, bullet points)
* 🔒 Be **polite, clear, and safe**

---



# 📖 Prompting Techniques

## ✅ Normal Prompts Best Practices

* 🎯 **Be specific** → Avoid vague instructions.
* 🏗️ **Define structure** → Output format (list, table, essay, code).
* 🎨 **Set tone/style** → Formal, casual, technical, creative.
* ⏳ **Add constraints** → Word limit, step-by-step, exact format.
* 📚 **Provide context** → Background info improves accuracy.

---

## 🤖 Claude Prompts Best Practices

* 👤 **Use role-based prompting** → (“You are a career coach…”)
* 🧠 **Ask for step-by-step reasoning** → (“Think carefully before answering…”)
* 🏗️ **Give structured instructions** → Use headings, bullet points, sections.
* 🔒 **Be polite, clear, and safe** → Direct, respectful instructions.

---

## 📌 Mandatory Elements in Prompts

1. **Context** → Provide background (so AI knows scope).
2. **Role** → Assign AI a persona (teacher, mentor, coder).
3. **Task** → Clearly state what needs to be done.
4. **Examples** → (Optional, but powerful) give few-shot references.

---

## 📝 Sample Prompts (Using All Four Elements)

### 🔹 Example 1: Normal Prompt (Learning Content)

```
Context: I am a beginner learning Python.  
Role: You are a coding tutor.  
Task: Explain how loops work in Python with real-life examples.  
Examples: Show me 2 code snippets (for loop and while loop).  
```

✅ Output → Clear explanation + 2 code snippets.

---

### 🔹 Example 2: Claude Prompt (Interview Preparation)

```
Context: I am preparing for a Data Analyst job.  
Role: You are an interview coach.  
Task: Guide me step by step with:
   - Resume tips
   - 3 common interview questions (with sample answers)
   - 2 practical projects I can showcase  
Examples: Format output with headings and bullet points.  
```

✅ Output → Structured career guide.

---

### 🔹 Example 3: Creative Prompt (Story Writing)

```
Context: I want to write a bedtime story for kids aged 7-10.  
Role: You are a children’s storyteller.  
Task: Write a short story about a curious rabbit who discovers teamwork.  
Examples: Keep it under 200 words, use simple language, and add a moral at the end.  
```

✅ Output → Fun, age-appropriate story with moral.

---

## 🔄 Additional Examples

### 🔹 Example 4: Normal Prompt (Technical Explanation)

```
Context: I am studying networking for an exam.  
Role: You are a computer science teacher.  
Task: Explain the difference between TCP and UDP in simple terms.  
Examples: Provide the explanation in a comparison table with at least 3 points.  
```

✅ Output → Side-by-side TCP vs UDP comparison table.

---

### 🔹 Example 5: Claude Prompt (Project Guidance)

```
Context: I want to build a simple website for my college project.  
Role: You are a web development mentor.  
Task: Suggest a step-by-step plan with:
   - Tech stack to use
   - Basic project features
   - Free hosting options  
Examples: Present it in 3 sections with bullet points.  
```

✅ Output → Roadmap for project development.

---

### 🔹 Example 6: Normal Prompt (Email Drafting)

```
Context: I need to inform my professor about missing a class due to illness.  
Role: You are a professional email assistant.  
Task: Draft a short, polite email.  
Examples: Keep it under 100 words, include subject line, and use formal tone.  
```

✅ Output → Professional, concise email draft.

---

### 🔹 Example 7: Claude Prompt (Learning Roadmap)

```
Context: I want to become a Machine Learning Engineer.  
Role: You are a career advisor.  
Task: Create a 6-month structured learning roadmap with:
   - Key topics
   - Resources (free/paid)
   - Mini-project suggestions  
Examples: Output in a month-wise timeline with bullet points.  
```

✅ Output → Month-wise ML learning plan.

---

## 🎯 Flowchart – How a Strong Prompt Works

```mermaid
flowchart TD
    A[Context: Background Info] --> B[Role: Assign AI Persona]
    B --> C[Task: Clear Instruction]
    C --> D[Examples: Provide references/patterns]
    D --> E[AI: Generates accurate, structured response]
```

---

✨ **Takeaway:**

* Normal prompts = direct + structured.
* Claude prompts = role-based + step-by-step + structured.
* Always include **Context + Role + Task + Examples** for best results.

---

👉 Do you want me to now **add a side-by-side comparison table (Normal vs Claude prompts with examples)** so your students can instantly see the difference?
