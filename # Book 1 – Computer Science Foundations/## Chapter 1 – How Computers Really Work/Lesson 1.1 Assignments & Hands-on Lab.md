# 📘 Backend Engineering Mastery Program

# Book 1 – Computer Science Foundations

## Chapter 1 – How Computers Really Work

# Lesson 1.1 – Part 9

# Assignments & Hands-on Lab

> **Purpose**
>
> These assignments are designed to help you think like an engineer rather than simply memorizing definitions.

---

# Assignment 1 – Explain the Computer

## Objective

Explain the computer in your own words.

Do NOT copy from the lesson.

Imagine you're teaching a school student.

Answer:

- What is a computer?
- Why was it invented?
- What problems does it solve?

Maximum:
300 words

---

# Assignment 2 – Real Backend Mapping

Suppose you have this API:

```
POST /register
```

Request

```json
{
    "name":"Fazal",
    "email":"fazal@gmail.com",
    "password":"123456"
}
```

Identify:

### Input

What enters the system?

---

### Processing

What validations happen?

What business logic executes?

---

### Storage

What gets stored?

Where?

---

### Output

What does the API return?

---

# Assignment 3 – Observe Your Own Computer

Open:

Windows

Task Manager

or

Linux

System Monitor

Observe:

- CPU Usage
- Memory Usage
- Disk Usage

Answer:

1. Which application is using the most CPU?
2. Which application uses the most RAM?
3. Why do you think that application needs so much memory?

---

# Assignment 4 – Think Like an Engineer

Imagine your API suddenly becomes slow.

Write down at least TEN possible reasons.

Example:

- Database
- CPU
- Memory

Don't stop there.

Think deeper.

---

# Assignment 5 – Draw the Architecture

Draw this in your notebook.

```
             Computer

                 │

      ┌──────────┼──────────┐

      │          │          │

     CPU        RAM      Storage

      │

 Input Devices

      │

 Output Devices
```

Now explain the responsibility of every component in one sentence.

---

# Assignment 6 – Draw the Java Journey

Without looking at notes,

draw

```
Java Source

↓

Compiler

↓

Bytecode

↓

JVM

↓

Machine Code

↓

CPU

↓

Output
```

If you cannot draw it,

read Part 4 again.

---

# Assignment 7 – Research

Spend no more than 20 minutes.

Find answers for:

1. Why is Java called platform independent?

2. Why can't CPUs execute Java directly?

3. Why is RAM called volatile memory?

Write your answers in your own words.

---

# Hands-on Lab 1

## Objective

Observe the Java Compilation Process

Create:

Main.java

```java
public class Main {

    public static void main(String[] args) {

        System.out.println("Backend Engineering Mastery");
    }
}
```

Compile manually.

```
javac Main.java
```

Observe:

A new file appears.

```
Main.class
```

Question

Where did this file come from?

---

Now run

```
java Main
```

Observe

The JVM starts.

Question

Which command compiled the program?

Which command executed it?

---

# Hands-on Lab 2

Use

```
javap -c Main
```

Don't worry if everything looks confusing.

Just observe.

Question:

Do you see Java code?

Or something different?

We'll understand this output later.

Today,

just become familiar with it.

---

# Reflection Questions

These are the most important questions.

Write answers in your notebook.

Question 1

What surprised you most today?

---

Question 2

Which concept was hardest?

---

Question 3

Could you explain this lesson to someone else?

---

Question 4

If not,

which topic needs revision?

---

Question 5

Where do you think this lesson will help you in backend engineering?

---

# Bonus Challenge

Imagine you are explaining Java execution to your younger brother.

Explain

```
Main.java

↓

Main.class

↓

JVM

↓

CPU
```

without using technical jargon.

If you can do that,

you truly understand the concept.

---

# GitHub Tasks

Commit today's work.

Suggested commit message

```
Book 1 Chapter 1 Lesson 1.1 Assignments and Hands-on Lab
```

---

# Lesson Completion Checklist

- [ ] I understand what a computer is.
- [ ] I understand why computers exist.
- [ ] I understand Input → Processing → Storage → Output.
- [ ] I understand the major computer components.
- [ ] I understand Java execution.
- [ ] I manually compiled a Java program.
- [ ] I completed all assignments.
- [ ] I committed everything to GitHub.
