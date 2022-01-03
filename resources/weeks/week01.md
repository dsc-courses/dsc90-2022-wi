---
layout: default
title: Week 1 – Introduction, Calculus
nav_exclude: true
---

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

# Week 1 – Introduction, Calculus

Welcome to the first lecture and week of DSC 90 this quarter! Each week of DSC 90 will have a webpage, like this one, that contains links to lecture slides, recordings, and required readings, and also contains that week's homework assignment.

<span style="color:red;"><b>Note:</b> this page is still under construction. Check back after class on Monday for a finalized version.</span>

---


## Lecture (January 3rd) 👨‍🏫

- [blank slides](../../slides/lec01.pdf)
- annotated slides (after lecture)
- [code (DataHub)](http://datahub.ucsd.edu/user-redirect/git-sync?repo=https://github.com/dsc-courses/dsc90-2022-wi&subPath=lecture/lec01/lec01.ipynb)
- recording (after lecture)

---

## Readings 📖

Required:
- Donoho, [50 years of Data Science](https://www.tandfonline.com/doi/pdf/10.1080/10618600.2017.1384734), Pages 745-749
- Neumann, [History of Pi](../../../resources/readings/lec01/history-of-pi-neumann-chapter-1.pdf), Ch. 1
- Britannica, [Pythagoreanism](https://www.britannica.com/science/Pythagoreanism) (stop at "History of Pythagoreanism")
- Wikipedia, [Quadrature of the Parabola](https://en.wikipedia.org/wiki/Quadrature_of_the_Parabola)
- [YouTube: The History of Calculus - A Short Documentary](https://www.youtube.com/watch?v=6wb60tcilMQ)
<!-- - O'Connor and Robertson, [A history of the calculus](https://mathshistory.st-andrews.ac.uk/HistTopics/The_rise_of_calculus/) -->

Optional:
- [Pythagorean tuning](https://www.youtube.com/watch?v=feeB8ci38jE) and [Pythagorean intervals](https://www.phys.uconn.edu/~gibson/Notes/Section3_2/Sec3_2.htm): interesting if you have a background in music
- [YouTube: Euclid's Elements Book 1: Proposition 47, The Pythagorean Theorem](https://www.youtube.com/watch?v=6Btw3xct24Q): if you'd like to see Euclid's proof of the Pythagorean theorem
- [YouTube: What is the Archimedes' Principle? Memorize](https://www.youtube.com/watch?v=05WkCPORlj4): recommended if you're unfamiliar with Archimedes' principle
- [YouTube: How to Calculate Pi, Archimedes' Method](https://www.youtube.com/watch?v=DLZMZ-CT7YU): good video if you'd like another look at the $$\pi$$ calculations we did in class
- [YouTube: Visual Proof: 1/4 + 1/16 + 1/64 + ... - Sum of Infinite Series](https://www.youtube.com/watch?v=iTdpl-FZD0o): if you'd like another explanation of the sum of geometric series calculation from class

---

## Homework 1 (due Sunday, January 10th at 11:59PM) 📝

**Welcome to your first DSC 90 homework!** Homeworks in DSC 90 are designed to have you engage with the week's content. They will rely on you having completed the readings.

Submit your answers as a PDF to Gradescope by the due date for full credit. We encourage you to discuss the readings and questions with others in the course, but all work must be your own. **Remember to use Campuswire if you need guidance!**

<br>

### Question 1

For both subparts, we're expecting 3-4 sentences.

(a) According to Donoho, in "The Future of Data Analysis", John Tukey stated that the science of data analysis is being shaped by four factors. In your own words, what are those four factors? 

(b) Based on your current understanding, describe how the field of data science is different than the field of statistics. 

### Question 2

In class, we looked at a visual proof of the fact that

$$1 + \frac{1}{4} + \frac{1}{4^2} + \frac{1}{4^3} + ... = \frac{4}{3}$$

Let's try and work through a similar problem. Namely, we'll try and identify the value of the infinite sum

$$1 + \frac{1}{9} + \frac{1}{9^2} + \frac{1}{9^3} + ...$$

(a) What's your best guess as to what the value is? Explain your answer. (If you're familiar with the sum of an infinite geometric series, $$S = \frac{a}{1-r}$$, feel free to use it.)

(b) Make an argument similar to the one in class to justify your answer in part (a). This should involve some drawing – make sure to include your drawings in your PDF submission. (If you're stuck, watch [this video](https://www.youtube.com/watch?v=iTdpl-FZD0o)).

(c) Another way of writing this infinite series is $$\sum_{i = 0}^\infty \frac{1}{9^i}$$. Why do you think we decided to look at this series, as opposed to $$\sum_{i = 0}^\infty \frac{1}{8^i}$$ or $$\sum_{i = 0}^\infty \frac{1}{10^i}$$?

### Question 3

Below in <span style="color:blue;">blue</span> is the parabola $$y = x^2$$, and in <span style="color:red;">red</span> is the line $$y = 2x + 8$$.

<div align=center>
<img src='../../images/hw01-parabola.png' width=350>
</div>

(a) **Without** using integration, determine the area between the given line and parabola.

This will involve a few steps. First, you'll need to find the third point on the triangle that Archimedes specified in _Quadrature of the Parabola_. Some guiding questions: 
- What is the slope of the red line? 
- What is the slope of the tangent line to the parabola at any given point on the parabola? (What is the derivative of the parabola?) 
- At what point on the parabola is the slope of the tangent line equal to the slope of the red line?

Once you've identified the third point, you can use [this online calculator](https://keisan.casio.com/exec/system/1223520411) to find the area of that triangle (unless you'd rather do it yourself for practice). Then, you should be able to use a result from class. Show all of your steps, and remember to ask for help if you need it.

(b) Only if you're familiar with integration, find the area between the given line and parabola using integration, and show that your answer is the same as your answer in part (a).