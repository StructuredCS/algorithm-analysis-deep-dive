# Algorithm Analysis Deep Dive

<p align="center">
    <img src="course-overview.png" alt="Course Cover" width="600">
</p>

## Table of Contents

- [Course Overview](#-course-overview)
- [Who This Course Is For](#-who-this-course-is-for)
- [What You'll Learn](#-what-youll-learn)
- [Why It Still Matters to Learn Algorithm Analysis](#-why-it-still-matters-to-learn-algorithm-analysis)
- [Weekly Content & Interactive Assignments](#-weekly-content--interactive-assignments)
- [Join the Discussion](#-join-the-discussion)
- [Stay Connected & Support the Course](#-stay-connected--support-the-course)

## 📘 Course Overview

Algorithm Analysis Deep Dive began as a part of a flipped classroom experience designed for university students ([more about me](https://qhao.info)). As the lectures went online, I realized they were helping a much wider audience — especially self-taught programmers and bootcamp graduates who never had the chance to study algorithm analysis rigorously. That's why I've decided to open access the course, and share the full learning experience.

This is not just a coding tutorial — it's a full university-level learning experience in algorithm and data structure analysis, a topic often glossed over in bootcamps and self-study resources, and one that AI tools like ChatGPT frequently struggle to explain accurately. The course emphasizes understanding why algorithms work, not just how to implement them, with a strong focus on deriving and reasoning about time complexity.

The course is organized into weekly modules of eight weeks. Each week includes curated lecture videos, quizzes, and hands-on coding labs with automated feedback. You can:

* [Binge watch the full playlist](https://www.youtube.com/playlist?list=PL3fg3zQpW0k4TYTBwPFrGkXDJ1Xh4IHyv)
* Or follow along with [the course structure below](#-weekly-content--interactive-assignments)
* Or jump into topics that interest you most using [the content table below](#-weekly-content--interactive-assignments)

If you find this course helpful, consider giving this repo a star ⭐️, sharing it with your network, and subscribing to [**@StructuredCS on YouTube**](https://www.youtube.com/@structuredcs). Your support helps more learners discover quality, accessible resources. 

## 🧠 Who This Course Is For

This course is designed for anyone who wants to deepen their understanding of algorithm analysis and time complexity. It's particularly useful for:

* Self-taught programmers looking to fill gaps in algorithm analysis
* Bootcamp graduates who want to go beyond surface-level DSA
* Students preparing for coding interviews who struggle with complexity analysis
* Students who've taken an algorithms course before but found the math abstract, non-intuitive, or disconnected from the actual code
* Anyone who's tried to memorize time complexity by brute force — and now wants to truly understand it

The prerequisites are minimal:

* a basic understanding of programming concepts
* a basic understanding of linear data structures, such as arrays and linked lists
* a basic understanding of recursion and iteration
* a basic understanding of at least one programming language (Java, Python, C++, etc.)

## 🎯 What You'll Learn

By the end of this course, you will have a solid understanding of:

* Core mathematical tools: asymptotic notation, recurrence tree method, substitution method, and the master theorem
* Complexity analysis techniques: worst-case, average-case, probabilistic, and amortized analysis
* Sorting algorithms: insertion sort, quicksort, mergesort, heapsort
* Data structures: heaps, hashtables, and binary search trees
* The divide-and-conquer paradigm and how to analyze its time complexity
* How to analyze the time complexity of algorithms using mathematical reasoning
* How to analyze the time complexity of data structures

## 🧩 Why It Still Matters to Learn Algorithm Analysis

As AI tools like ChatGPT become more prevalent, you may wonder if you can rely on AI to handle algorithm analysis for you. While AI tools can be a helpful tool, these tools often struggle with the nuances of time complexity, and give incorrect or incomplete answers & explanations. Here is an example where Google AI Overview fails to parse a correct statement about the time complexity of heap operations:

> A statement that's true: In the average case, a heap allows insertion in O(1) time and deletion of the highest-priority element (e.g., the min value in a min heap) in O(log⁡n) time.

<p align="center">
    <img src="ai-overview-snapshopt.png" alt="AI overview sample snapshot" width="750">
</p>

## 🧪 Weekly Content & Interactive Assignments

This course is more than just lectures — it's a full learning experience designed to help you apply what you've learned and get feedback automatically, just like a structured university course. The course is structured to be language-agnostic. Each week comes with:

* A set of lecture videos (YouTube playlist)
* One or more conceptual assignments or quizzes
* Hands-on coding labs where you'll write and test algorithms

Labs use GitHub, Github Actions and GitHub Classroom, where you'll:

* Submit your code via version control
* **Receive immediate automated feedback via GitHub Actions**
* Learn through test-driven development
* You don't need to be enrolled anywhere — just a GitHub account is enough to participate.

The current lab setup is designed for **Java**. The setups for other languages are in the works, and they will be added when ready.

| Week | Topic | Videos | Assignments |
|------|-------|--------|-------------|
| Week 1 | Introduction to algorithms | [Best & Worst Case Analysis Explained](https://youtu.be/Ye6puk0LhwU)| [Quiz 1](https://docs.google.com/document/d/1PClb1o2UcZQSQG5B3Ptg959xZCAyYuciqmhKX5535Io/edit?usp=sharing) |
| | | [Step-by-Step Analysis of Insertion Sort](https://youtu.be/9LN-tteG0l0)| [Problem 1](https://docs.google.com/document/d/15-nIma2gogszhGfsyvyfc7kIr6LAJd6VYPfaqLz1S0I/edit?usp=sharing) |
| | | | [**Lab 1**](https://docs.google.com/document/d/1m427yvKV19ESz8GZIrMKYjJkzWRFk2UojCoTCCe4gbs/edit?usp=sharing) |
| Week 2 | Asymptotics | [Asymptotic Analysis Explained](https://youtu.be/TdPFZLPkPNE) | [Quiz 2](https://docs.google.com/document/d/1FU-Kr4A2BaMsaRyJKzZ2fbiUR04nqJcuEEkmIM9fOkU/edit?usp=sharing) |
| | | | [Assignment 1](https://docs.google.com/document/d/1i0FRQT-tFdPttXnp5b-foclHR3lJslYozPLhFIo3eMc/edit?usp=sharing) |
| Week 3 | Divide and conquer | [Recurrence Relations & <br>Recurrence Tree Method](https://youtu.be/jqXjzWIZiyA) | [Quiz 3](https://docs.google.com/document/d/1-me6Ale3Z3sZWuMyGhZlG7v8vZfOwYj4ucEsoJwbmq8/edit?usp=sharing) |
| | | [Master Theorem Explained with Examples](https://youtu.be/aS8ce5B64yU)| [Problem 2](https://docs.google.com/document/d/16-Kx34G5W1rkZHESQsOg3oO_cx78GVA-UbjHF5Qfct0/edit?usp=sharing) |
| Week 4 | Quick sort and <br>probability analysis | [Understanding Quicksort](https://youtu.be/XhGOEuQdAAs) | [Quiz 4](https://docs.google.com/document/d/1JHpZxrnRD7RKn0P-22Xv3pO_ECiBzep5L0VmUsk_3Io/edit?usp=sharing) |
| | | [Average-Case Complexity, Expected <br>Value & Randomized Quicksort](https://youtu.be/M0O-s2y0O9I) | [Problem 3-5](https://docs.google.com/document/d/1QbHFdegvk0j3fbPysIwiU9yI6Y3lrjVDMypWJr7K1Bc/edit?usp=sharing) |
| | | | [**Lab 2**](https://docs.google.com/document/d/11xeCwWmB2DcXtvO5Rfhh0RIFbmm3sOjf5sHmz3P7Hp0/edit?usp=sharing) |
| | | | [Assignment 2](https://docs.google.com/document/d/1AyGOX4SYYp25lpnus1-VwxmtB9vXaHw7hc2l9UZXXeM/edit?usp=sharing) |
| Week 5  | Heaps | [Understanding Heap Properties](https://youtu.be/IGbHcofDbFs) | [Quiz 5](https://docs.google.com/document/d/1bdhzd8xujyFB6TyhDft2fD3UYasClTsPYJ0SVMeNwGA/edit?usp=sharing) | 
| | | [Insert & Peek Methods Explained](https://youtu.be/QSmCO-9HCcQ) | [Quiz 6](https://docs.google.com/document/d/1_X_jlrd3_Be5C5CfRSLkjiCT-BCR5u0are1jEOE49xQ/edit?usp=sharing) |
| | | [Delete Method Explained](https://youtu.be/e_yaojRRnyI) | [Problem 6](https://docs.google.com/document/d/1C-r7XTbeJ5QpVD4yVvtHbbiMyV9FbciKiZ_ha95450M/edit?usp=sharing) |
| | | [Building a Heap & Mastering Heap Sort](https://youtu.be/7TnTsK2HjUk) | [**Lab 3**](https://docs.google.com/document/d/1lwlJkkjzq5QpSqcw96Uvzdf4WsHA2te9UYuZ3bhYK70/edit?usp=sharing) |
| Week 6 | Hashtables | [How Hash Functions Work](https://youtu.be/Z43QoUzU5uE) | [Quiz 7](https://docs.google.com/document/d/1iA98z82cX85ra1_uA34v5s168ONLP-lKeK5FDI3TioY/edit?usp=sharing) |
| | | [Understanding Open Addressing](https://youtu.be/haLcAKMqPec) | [Problem 7](https://docs.google.com/document/d/1afHJyWHN0YPt-eI8_Q3oZka56eni9N-k93FVCXPcD30/edit?usp=sharing) |
| | | [Understanding Chaining](https://youtu.be/3BKp1l8WYhc) | [**Lab 4**](https://docs.google.com/document/d/1pwQVB2D7f0EE8gzNNSw-AnsnAiG3PdR0RUq1k9JlMPA/edit?usp=sharing) |
| Week 7 | Binary search trees | [Search Operation & <br>Time Complexity Explained](https://youtu.be/NN8xJflPbaU) | [Quiz 8](https://docs.google.com/document/d/1RRiLsf3OSIY8AaR9h4DjYydPUx8BbPgOc0ung7JU55s/edit?usp=sharing) |
| | | [The Insert Method Explained](https://youtu.be/adz2MYaZ4qY) | [Problem 8](https://docs.google.com/document/d/158JDkjWOb-fQTGoqDyy8I1szZduoJkGiRyPPeQsEKm4/edit?usp=sharing) |
| | | [The Delete Method Explained](https://youtu.be/Pgb_GpMWPXo) | [Assignment 3](https://docs.google.com/document/d/1MRTNm4OkC8Tk-BbGRO6nj6DV_PirCDAnU2HBe2wUjZw/edit?usp=sharing) |
| | | [Traversal](https://youtu.be/ZxxnhfjS-wY) | [**Lab 5**](https://docs.google.com/document/d/102Gx7wsJhDzBJtTUNGyJTe8ROrWdu98W-kzOr26w7O4/edit?usp=sharing) |
| Week 8 | Amortized analysis | [Aggregate Method Explained with Examples](https://youtu.be/sCaPH2ogogg) | [Quiz 9](https://docs.google.com/document/d/1WRmLXa4f72bSCfSaSoo60rPJqM6OMDZgGTq9NXo3g9A/edit?usp=sharing) |
| | | [Accounting Method Explained with Examples](https://youtu.be/EI5fST7z27o) | |
| | | [Potential Method Explained with Examples](https://youtu.be/zUxWjC9WSJM) | |

The answers and sample solutions for the quizzes and writing assignments are provided in the [answers.md](answers.md) file for your reference. Please try to solve each question on your own before looking at the answers.

## 💬 Join the Discussion

If you're working through the labs or lectures and want to discuss challenges, ideas, or solutions with others:

* [Start a GitHub Discussion in this repo](https://github.com/Neo-Hao/algorithm-analysis-deep-dive/discussions)
* [Leave a comment on the relevant YouTube video](https://www.youtube.com/@structuredcs)
* [Or tag me on LinkedIn if you're sharing your progress](https://www.linkedin.com/in/qiang-hao-4984023b/)

## 🙌 Stay Connected & Support the Course

If you find this course helpful, consider giving this repo a star ⭐️, sharing it with your network, and subscribing to [**@StructuredCS on YouTube**](https://www.youtube.com/@structuredcs). Your support helps more learners discover quality, accessible resources. A like, a share, or a comment goes a long way. If you know someone who might benefit from this course — a fellow learner, colleague, or friend preparing for interviews — feel free to share [the playlist](https://www.youtube.com/playlist?list=PL3fg3zQpW0k4TYTBwPFrGkXDJ1Xh4IHyv) or this GitHub repo with them.

## 📜 License & Attribution

This course is licensed under the [MIT License](LICENSE). Feel free to use, modify, and share the content as long as you provide appropriate credit. The course materials come from various sources, including my own lectures and resources from other educators. I have made every effort to credit the original authors and sources of the materials used in this course. If you notice any omissions or errors, please let me know so I can correct them. The materials are provided for educational purposes only, and I encourage you to adapt them for your own learning or teaching purposes.