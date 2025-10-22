# Fundamental Prompting Techniques in Prompt & Context Engineering


In this section, we’ll explore **fundamental prompting techniques**, the building blocks of how you communicate with AI models like ChatGPT, Claude, or Gemini.  

Each technique changes **how the AI understands your request**, and learning them will help you get more accurate, creative, and useful results.  

Let’s dive in 👇

---

## **🟢 Zero-Shot Prompting**

**What it means:**  
You give the AI **no examples**: just the question or task itself.  
The model uses its **trained knowledge** to generate the answer.

**Example:**  
> Prompt: “Translate the sentence ‘Good morning’ into French.”

🧠 The AI replies: “Bonjour.”

❓ **When to use:**  
When the task is simple or well-known, like translation, definitions, or summaries.

---

## **🟡 One-Shot Prompting**

**What it means:**  
You give the AI **one example** before the actual task.  
This helps it understand the **format or pattern** you expect.

**Example:**  
> Prompt:  
> Example -  
> Input: “The sky is blue.”  
> Output: “Weather description.”  
>  
> Now, Input: “It’s raining outside.”  
> Output:

🧠 The AI replies: “Weather description.”

❓ **When to use:**  
When you want to teach the AI a simple pattern or task format using just one sample.

---

## **🟠 Few-Shot Prompting**

**What it means:**  
You give the AI **a few examples** (3–5 usually) so it can learn the **style or logic** you want before performing the real task.

**Example:**  
> Prompt:  
> Example 1 -  
> Input: “The pizza tastes amazing.”  
> Output: “Positive”  
>  
> Example 2 -  
> Input: “This laptop is too slow.”  
> Output: “Negative”  
>  
> Now, Input: “The movie was okay.”  
> Output:

🧠 The AI replies: “Neutral.”

❓ **When to use:**  
When the task is slightly complex and the AI needs examples to catch your pattern or tone (like sentiment analysis, labeling, or formatting).

---

## **🔵 System Prompting**

**What it means:**  
You tell the AI **how it should behave or respond** before the conversation starts.  
It’s like setting the **AI’s personality or rulebook.**

**Example:**  
> System Prompt: “You are a polite and helpful customer support assistant.”  
>  
> User: “My package hasn’t arrived yet.”  

🧠 The AI replies politely and professionally:  
> “I’m sorry to hear that! Could you please share your order ID so I can help you track it?”

❓ **When to use:**  
When building chatbots, assistants, or educational tools where the AI must follow a specific tone, role, or goal.

---

## **🟣 Contextual Prompting**

**What it means:**  
You give the AI **extra background or context** to help it respond better.  
The more context you give, the more accurate the answer becomes.

**Example:**  
> Context: “You are analyzing a conversation between a teacher and a student about photosynthesis.”  
>  
> Prompt: “Summarize the student’s understanding in two lines.”

🧠 The AI replies with a clear and context-aware summary.

❓ **When to use:**  
When your prompt depends on prior details, like documents, chat history, or previous instructions.

---

## **🟤 Role Prompting**

**What it means:**  
You assign a **specific role** to the AI so it answers like an expert or character.  
It helps the model respond with **the right tone and expertise**.

**Example:**  
> Prompt: “You are a fitness coach. Suggest a simple 10-minute morning workout for beginners.”

🧠 The AI replies like a real trainer:
> “Start with 2 minutes of stretching, then 5 minutes of light cardio like jumping jacks, and end with 3 minutes of deep breathing.”

❓ **When to use:**  
When you want responses from a particular perspective: like a teacher, developer, doctor, or friend.

---

## 🧠 Summary

| Technique | Description | Best Used For |
|------------|--------------|---------------|
| **Zero-Shot** | No examples , AI uses its general knowledge | Simple or known tasks |
| **One-Shot** | One example given | Simple pattern recognition |
| **Few-Shot** | A few examples given | Slightly complex patterns |
| **System Prompting** | Define AI’s behavior upfront | Chatbots, structured roles |
| **Contextual Prompting** | Add background info for clarity | Document-based or multi-turn prompts |
| **Role Prompting** | Assign a specific role or identity | Expert or character-style responses |

---

💡 **Real-World Example:**
Imagine you’re building an **AI resume reviewer**:
- Use **system prompting** to set the AI’s role: “You are an HR recruiter.”  
- Use **contextual prompting** by adding the user’s resume and job description.  
- Use **few-shot prompting** to show examples of good and bad feedback.  

Together, these techniques make the AI’s feedback more **relevant, clear, and realistic**.

---

### 💡 Key Takeaway
Prompting isn’t just about asking questions,  
it’s about **guiding the AI** to think and respond the way you want.

---
