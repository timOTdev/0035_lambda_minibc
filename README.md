# 0035_lambda_minibc

## Lambda School Mini Bootcamp

## Start 5/7/2018

## [Syllabus](https://learn.lambdaschool.com/fsw-pre/sprint/recw0xx1timtjaq3d)

## [Lambda Challenge](https://github.com/lambdaschool/lambda-challenge)

# Day 1 Intro to Web Development Fundamentals

- [Link](https://www.youtube.com/watch?v=NNOwFxEggeU)
- [First Day Attendance](https://airtable.com/shrmVa1GAG9UB5d2A)
- [D1 Homework](https://codepen.io/timh1203/pen/QrOXyJ?editors=1010)

## What is computer programming?

- Any task we communicate with computer via code
- There are many computer languages including low level languages and high languages
- Syntax is how all the code is similar
- Other terms:
- Language - the type of syntax we use
- Framework - a type of overarching scaffold we can use on top of a programming language

## What is web development?

- Building online web with HTML, CSS, Javascript
- That's the front end but there is also a backend
- A codebase is a collection of code to make a web app work
- We will be using codepen for most of our coding, we don't need an IDE

## Basic Code

- div, p, spans, h1, h2
- spans are inline
- you should not use headers as size oriented

## Questions

```plain
1. What platform will classes be conducted in like zoom, etc.? Ability to ask questions live?

the full course is supplemented using Zoom, for now we're going to just use text because it's a little bit easier and not everyone should have the software installed at the moment
```

```plain
2. What is the general process of applying to lambda school? I saw one would have to complete the lambda challenge for an interview or something like this?

when I was a student, you'd apply via an online form and set up a interview with the CEO Austen. now that it's gotten a bit bigger, it's a different process. you can complete the lambda challenge for an interview and you'll be tested on web dev / coding fundamentals (that you should pretty much be prepared for after this course if you put the work in!) and other personal factors

i'm not 100% because I haven't applied as a student in a while, but I believe that's the general gist of it, it should always involve an interview and some sort of testing of your knowledge because lambda is not a "0-100" school, but more like a "20-120" school, if that makes sense? the full course isn't designed for complete beginners.
```

```plain
3. Can you break down a typical day as a student by hour? Like 8-10am class, 10-12pm group work, etc.

all times in PST:
8AM - 8:45 AM - algorithm coding challenge
8:45 - 9 - code challenge solution
9 - 11 - lecture / guided demo with an instructor
11 - 12 - lunch
12 - 1 - pair programming with a group
1 - 4 - either work solo on the days assignment or continue in your groups
4:15 - EOD - team standup meeting with your assigned project manager

that's the schedule that I maintain in the group that I manage currently
(i'm a manager in the fulltime program as well as this one)

that's kind of a rough schedule, there's usually some 5-10 minute breaks here and there but that's generally when you'll be expected to be available during the day

yeah the algorithms are awesome!
want to see an example?

Given a positive (or 0) number, return a string of 1's and 0's representing it's binary value:
toBinaryString(6) should return "110" (no leading 0).
Use of the native method number.toString(2);  is disallowed.
function toBinaryString(number) {
  let r = "";
  while(number > 0) {
    r = number % 2 + r;
    number >>= 1;
  }
  return r || "0";
}

if you want to practice algorithms on your own i recommend hackerrank personally, but codewars and leetcode and freecodecamp all have great algorithm resources too

there's also a free princeton course on programming and algorithms which is cool too
```

```plain
4. In general, can we expect to have our nights open during the full course or do a lot of students study then?

it's definitely not the easiest thing but as long as you put in a solid effort you'll go far!

okay so when I was a student I was putting in like 100hrs/wk to keep myself caught up and staying afloat BUT it's not as intense as that anymore
with the new project manager system it's a LOT easier to maintain yourself

on the hardest weeks of the course (redux and data structures in my opinion) it's not unreasonable for students to spend extra time studying since it's very difficult material

i'd say it's closer to 9 for most of the program

you're DEFINITELY encouraged to maintain a social life and communicate with friends/family/etc as much as you can while in the program, it's VERY easy to burn out, but yeah there's a lot of times it's necessary to study
```

```plain
5. I don't plan to start until July or August, is there any prep you would recommend in the in between time that might make the 6 month intensive more manageable?

I don't have the exact numbers on how many students have to fall behind, but there's a lot of options. recently we've enabled a "night school" program to help students after hours so that's an option, and then students can also defer back a cohort if that's necessary (i.e. if they fall ill or miss a week of lecture)
there's a lot of options, but I think of my students that I manage none of them have had to resort to anything like that
(and I think something like half of my students have almost no programming experience before lambda)

yeah it's hard to slot out 6 months of your life, but there's always the part time program! it's a solid alternative and it beats self-learning imo

write a lot of code. read You Don't Know JavaScript. get a mentor. talk to people who are better and more experienced and have them help you. you've got a lot of time and so getting a headstart on javascript fundamentals can be huge
there's also great udemy courses and things like that too

this is awesome! i like hearing about your guys' individual paths

i hope lambdaschool can serve to further each of you as much as possible
personally, I dropped out of college to go pro in a videogame (if you've heard of it, it's called Overwatch) and then I used my inroads there to get involved with software engineering. I was overwhelmed with my first job as a front end web developer and I eventually discovered Lambda School, so I quit my job to join lambda and i've been here since then (like 8 months now?) both as a student and a Project Manager
one of my favourite things about software engineering is the fact that there's so many unique ways to get where you want to go
```

```plain
6. Do we have access to past recent lectures to watch if we are accepted into the program? Definitely helps with learning as you guys suggest in the syllabus too.

You do! All of the lectures are recorded and the link is shared shortly after they end.
```

# Day 2 HTML and CSS Fundamentals

- [Link](https://www.youtube.com/watch?v=dxKczspmHOk)
- [D2 Homework 1](https://codepen.io/timh1203/pen/QraeLX?sort_col=item_updated_at&)
- [D2 Homework 2](https://codepen.io/timh1203/pen/PeEMNX?sort_col=item_updated_at&)
- [D2 Homework 3](https://codepen.io/timh1203/pen/WJdVdb?sort_col=item_updated_at&)

# Day 3 Introduction to Javascript

- [Link](https://www.youtube.com/watch?v=L9dVHm8GYqQ)
- [D3 Homework 1](https://repl.it/student/submissions/2961292)
- [D3 Homework 2](https://repl.it/student/submissions/2961496)

# Day 4 Control Flow

- [Link](https://www.youtube.com/watch?v=q4F5csfO-Bc)
- [D4 Homework 1](https://repl.it/student/submissions/2969643)
- [D4 Homework 2](https://repl.it/student/submissions/2969694)

# Day 5 Functions

- [Link](https://www.youtube.com/watch?v=P6X7QjKqz4A)
- [D5 Homework](https://repl.it/student/submissions/2989864)

# Day 6 Arrays & Objects

- [Link](https://www.youtube.com/watch?v=O3Sb1pDPVBg)
- [D6 Homework](https://repl.it/student/submissions/2997952)

# Day 7 Classes

- [Link](https://www.youtube.com/watch?v=6voX-LQPjsY)
- [D7 Homework](https://repl.it/student/submissions/3006329)

# Day 8 Classes

- [Link](https://www.youtube.com/watch?v=GWCOthwdzaU)
- [D8 Homework 1](https://repl.it/student/submissions/3014884)
- [D8 Homework 2](https://repl.it/student/submissions/3015005)

## Lambda Challenge

```plain
Lambda Challenge
Welcome to the Lambda Challenge! All students must pass this challenge in order to be considered for enrollment at Lambda School.

There are 4 problems covering the basics of what we have learned in the Mini Bootcamp. You goal is to make all of the tests pass. Follow the instructions for each problem and write the function correctly. Spelling and case DO matter, so make sure your spelling and cases are correct.
```