# Fundamentals II Introduction to Class-based Program Design

Course page: https://course.ccs.neu.edu/cs2510sp22/

## Syllabus


| Week #  | Task          | Book       |
|---------|---------------|------------|
| Week 1  | Lecture 1     | Ch. 1 - 13 |
|         | Lecture 2     |            |
| Week 2  | Lecture 3     | Ch. 1 - 13 |
|         | Lab 1         |            |
|         | Lecture 4     |            |
|         | Lecture 5     |            |
|         | Assignment 1  |            |
| Week 3  | Lecture 6     |            |
|         | Lab 2         |            |
|         | Lecture 7     |            |
|         | Assignment 2  |            |
|         | Lecture 8     |            |
| Week 4  | Lecture 9     |            |
|         | Lab 3         |            |
|         | Lecture 10    |            |
|         | Assignment 3  |            |
|         | Lecture 11    | Chapter 19 |
| Week 5  | Lecture 12    |            |
|         | Lab 4         |            |
|         | Lecture 13    |            |
|         | Assignment 4  |            |
|         | Lecture 14    |            |
| Week 6  | Lab 5         |            |
|         | Exam 1        |            |
|         | Lecture 15    |            |
|         | Assignment 5  |            |
| Week 7  | Lecture 16    |            |
|         | Lab 6         |            |
|         | Lecture 17    |            |
|         | Assignment 6  |            |
|         | Lecture 18    |            |
| Week 8  | Lecture 19    |            |
|         | Lab 7         |            |
|         | Lecture 20    |            |
|         | Assignment 7  |            |
|         | Lecture 21    |            |
| Week 9  | Lecture 22    |            |
|         | Lab 8         |            |
|         | Lecture 23    |            |
|         | Assignment 8  |            |
|         | Lecture 24    |            |
| Week 10 | Lecture 25    |            |
|         | Lab 9         |            |
|         | Lecture 26    |            |
|         | Assignment 9  |            |
|         | Lecture 27    |            |
| Week 11 | Lecture 30    |            |
|         | Lab 10        |            |
|         | Exam 2        |            |
|         | Lecture 28    |            |
| Week 12 | Lecture 29    |            |
|         | Assignment 9  |            |
|         | Lab 11        |            |
|         | Lecture 31    |            |
|         | Lecture 32    |            |
| Week 13 | Lab 12        |            |
|         | Assignment 10 |            |
|         | Lecture 34    |            |
|         | Lecture 35    |            |
| Week 14 | Lecture 35    |            |
|         | Optional Lab  |            |
|         | Assignment 10 |            |
|         | Intro to OOD  |            |


## FAQ

### What IDE should I use?

**Eclipse**, as shown in the Lab 1.

### Can I use other IDE/no IDE at all?

**Yes**, and some did, you can check out the course chat's pinned messages on Discord.

### Should I watch course videos?

**Yes**, unless you're in a hurry. Considering that this course is
less structured than SPD, the videos give more context about the topic
of the lecture.

### Should I read a book "How to Design Programs (Second Edition)"

**Probably, No.** The course lists the book as a recommended reading,
so it's not mandatory reading.

Also the book is not up to date with the course:
- it uses teaching Java-like language and discontinued ProfessorJ IDE
- see note below about the book by Dr. Felleisen

Still, the book adds more context to the topics in this course, so
it's probably good idea to skim through it at least,

## On this course and the book, by Matthias Felleisen

Here's response by Dr. Felleisen regarding this course and the book:

```
Thanks for letting me know that OSSU uses some of my ideas and even
refers to the underlying materials.

1. The book is _not_ about teaching Java but about teaching a
systematic design approach to programming.  (The usual approach goes
through the syntax of a language and has students copy-and-modify …
and that’s called learning.)

2. I abandoned the book because a person on the Java team at the time
confirmed that there would always be a conflict between the Java
language and the design principles that people in the OO community had
developed over the past four decades.  (Technical issue, which I can
explain if you have taken a PL course.)

WARNING: With this said, the book lacks the ideas about connecting the design
principles to the actual language and some basic libraries (nothing fancy).

NOTE: C#’s core language satisfies the OO principles people have
discovered over time. But it is an even more complex beast than Java (due to its C/C++ inheritance.)


3. Our Fundamentals 2 and the book _assume_ that you have taken
Fundamentals 1, a basic introduction to programming teaching more or
less the same principles but use teaching languages instead. F 1
assumes a student has understood very very basic ideas from what the
US calls “middle school” algebra or sometimes pre-algebra.  I would
take you from this knowledge to the construction of a distributed
system (using algebra ideas) within six weeks and spend the 13 weeks
of the semester on bringing across what systematic design is and why
it matters to grown-ups.


WARNING: My institution has just abandoned this curriculum. They wish to
teach a conventional Python! course sequence now for a number of reasons.

4. If your goal is to focus on Java, I recommend Josh Bloch’s
“Effective Java”.  I strongly recommend the first edition, because it
is concise and even the chapter titles confirm how I described F 1 and F 2.
Tthe first edition is a good (probably inexpensive) book to
read anyways, because it focuses on class-based OO programming rather
than Java.


5. I would _not_ just focus on just Java. Languages come and go, and a
developer must know how to move from PL to PL.  I would recommend

(a) learn JavaScript/TypeScript.  “JS: The Good Parts” might be a good
starting point.
(b) take a look at my PL course from the fall:

Programming Language Pragmatics
https://felleisen.org/matthias/4400-f25/index.html

All of this is particularly true when you look at the new AI landscape
where managers religiously believe that everyone can build complex
systems with Claude Opus 4.5.
```
