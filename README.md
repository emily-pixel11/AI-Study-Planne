# AI Study Planner

Building AI course project

---

## Summary

AI Study Planner is an AI-powered tool that helps students create personalized study plans.  
Based on available study time, exam dates, and subject difficulty, the AI generates optimized schedules.

The goal is to reduce stress and improve learning organization.

---

## Background

Many students struggle with:

* Time management
* Motivation
* Exam stress
* Prioritizing tasks

People often study inefficiently or start preparing too late.

My motivation for this project is to make studying more structured and easier. AI can help students organize their learning process automatically and save time.

---

## How is it used?

Users enter information such as:

* Subjects
* Exam dates
* Available study hours
* Difficulty level of each subject

The AI then creates a personalized learning schedule.

This solution can be used by:

* High school students
* University students
* Online learners

Example workflow:

1. User enters study information
2. AI analyzes priorities
3. AI generates a weekly study plan
4. User follows and updates the plan

![Study Planning](https://images.unsplash.com/photo-1522202176988-66273c2fd55f)

---

## Data sources and AI methods

The project could use:

* User-entered study schedules
* Calendar data
* Subject difficulty ratings
* Exam deadlines

Possible AI methods:

* Recommendation systems
* Machine learning for schedule optimization
* Predictive analysis for workload balancing

Example Python code:

```python
subjects = ["Math", "Biology", "History"]
hours = [4, 2, 3]

total_hours = sum(hours)

for i in range(len(subjects)):
    percentage = (hours[i] / total_hours) * 100
    print(subjects[i], "-", round(percentage, 1), "% of study time")
```

---

## Challenges

This project does not solve every learning problem.

Possible limitations:

* Users may not follow the schedule
* Study effectiveness is difficult to measure
* Personal motivation cannot fully be predicted
* AI recommendations may not fit every learning style

Ethical considerations:

* Protecting personal data
* Avoiding bias in recommendations
* Preventing over-dependence on AI tools

---

## What next?

Future improvements could include:

* Mobile app integration
* Voice assistant support
* Smart reminders
* Real-time progress tracking
* Integration with Google Calendar
* Adaptive learning recommendations

The project could grow into a complete AI learning assistant.

---

## Acknowledgments

Inspired by:

* The Building AI course
* GitHub open-source projects
* AI productivity applications

Image source:

* Unsplash free images

Created as a final project for the Building AI course.
