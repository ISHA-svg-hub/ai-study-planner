# 📚 AI Study Planner — Powered by Google Gemini 2.5 via OpenRouter

A smart, browser-based web app that generates a **personalized study schedule** for students preparing for exams. Built using prompt engineering and Google Gemini 2.5 through OpenRouter, this app helps students plan effectively based on time, subjects, and priorities.

![image](https://github.com/user-attachments/assets/377c7263-0bb1-4f44-95c5-58dcc7478c3d)



---

## 🧠 Key Features

✅ One-page HTML file — No backend required  
✅ Gemini 2.5 API via OpenRouter integration  
✅ Prompt dynamically adjusts to your input  
✅ Aesthetic, minimal design to impress teachers  
✅ Clean schedule output based on your priorities  

---

## 💡 How It Works

1. You enter your:
   - Subjects to study
   - Hours per day you can dedicate
   - Days left before exams
   - A subject you'd like to prioritize

2. The app dynamically builds a **prompt** and sends it to **Google Gemini 2.5** via **OpenRouter API**.

3. The LLM responds with a **day-by-day study schedule**, shown in a beautifully formatted layout.

---

## ✨ Example Prompt Sent to Gemini

```text
You are an expert academic planner. I have 10 days until exams and can study 5 hours per day. My subjects are: Physics, Chemistry, Math. Please create a detailed and realistic day-by-day study schedule, prioritizing Physics. Format clearly with days and subjects.
