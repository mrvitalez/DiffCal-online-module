# CAL01 Online Modules

Self-paced online modules for **Differential Calculus**
(Instr. Ryan M. Vitalez, LPT, Department of Earth and Space Sciences, Rizal Technological University),
following James Stewart, *Calculus*, 8th edition. Students use them on days when class cannot meet in person.

**Entry point:** https://mrvitalez.github.io/DiffCal-online-module/ sends students to the student site, which is a
Google Apps Script web app open only to **@rtu.edu.ph** accounts. The instructor has a separate admin site on the
same deployment (`?page=admin`). Setup: [INSTRUCTOR-SETUP.md](INSTRUCTOR-SETUP.md).

Each module has:

1. **Discussion**: one part per textbook section, with key equations, original figures and common mistakes.
2. **Worked examples**: three solved problems, solutions hidden until opened.
3. **Lecture video**: one free lecture (cited on the page) that pauses for three multiple-choice questions;
   answers are recorded.
4. **Activity**: 8 graded items plus a reflection. Answers can be numbers, exact values (`pi/4`) or formulas
   (`x^2 sin(x) + C`); formulas are checked for equivalence, so any correct form is accepted. The student's RTU
   email is detected automatically; they enter their name, student number and block and section, write solutions
   with a symbol/LaTeX toolbar and live preview, and see their score and per-item results on submit.

| # | Module | Stewart | Video |
|---|--------|---------|-------|
| 1 | Functions and Models | §1.1, §1.2, §1.3 | What is a function? (Khan Academy) |
| 2 | Limits and Continuity | §1.4, §1.5, §1.6, §1.7, §1.8 | Lecture 2: Limits, Continuity; Trigonometric Limits (MIT OpenCourseWare) |
| 3 | Derivatives and Rates of Change | §2.1, §2.2 | Lecture 1: Derivatives, Slope, Velocity, Rate of Change (MIT OpenCourseWare) |
| 4 | Differentiation Formulas and Trigonometric Derivatives | §2.3, §2.4 | Derivatives of sin(x) and cos(x) (Khan Academy) |
| 5 | The Chain Rule and Implicit Differentiation | §2.5, §2.6 | Lecture 4: Chain Rule, Higher Derivatives (MIT OpenCourseWare) |
| 6 | Rates of Change, Related Rates and Linear Approximation | §2.7, §2.8, §2.9 | Lecture 12: Related Rates (MIT OpenCourseWare) |
| 7 | Maximum and Minimum Values and the Mean Value Theorem | §3.1, §3.2 | Lecture 14: Mean Value Theorem; Inequalities (MIT OpenCourseWare) |
| 8 | The Shape of a Graph and Limits at Infinity | §3.3, §3.4 | Lecture 10: Approximations (cont.); Curve Sketching (MIT OpenCourseWare) |
| 9 | Curve Sketching and Optimization | §3.5, §3.7 | Lecture 11: Max-Min Problems (MIT OpenCourseWare) |
| 10 | Newton's Method and Antiderivatives | §3.8, §3.9 | Lecture 13: Newton's Method and Other Applications (MIT OpenCourseWare) |
| 11 | Inverse Functions and Exponential Functions | §6.1, §6.2 | Lecture 5: Implicit Differentiation, Inverses (MIT OpenCourseWare) |
| 12 | Logarithmic Functions and Their Derivatives | §6.3, §6.4 | Lecture 6: Exponential and Log; Logarithmic Differentiation; Hyperbolic Functions (MIT OpenCourseWare) |
| 13 | Exponential Growth and Decay; Inverse Trigonometric Functions | §6.5, §6.6 | Lecture 16: Differential Equations, Separation of Variables (MIT OpenCourseWare) |
| 14 | Hyperbolic Functions and l'Hospital's Rule | §6.7, §6.8 | Lecture 35: Indeterminate Forms - L'Hospital's Rule (MIT OpenCourseWare) |

Problem sets (answered in the notebook, linked from the home page):

- Problem Set 1: Functions and Limits (modules 1, 2)
- Problem Set 2: Derivatives, Part I (modules 3, 4)
- Problem Set 3: Derivatives, Part II (modules 5, 6)
- Problem Set 4: Applications of Differentiation, Part I (modules 7, 8)
- Problem Set 5: Applications of Differentiation, Part II (modules 9, 10)
- Problem Set 6: Inverse Functions, Part I (modules 11, 12)
- Problem Set 7: Inverse Functions, Part II (modules 13, 14)

The discussions, examples and problems are original and follow the order and notation of Stewart's *Calculus*;
no text or figures are copied from the book. Videos: MIT OpenCourseWare (CC BY-NC-SA 4.0).

## Files

```
index.html, modules/      Entry pages that send visitors to the RTU-only student site
assets/config.js          The student site URL (set once by the instructor)
assets/style.css          Shared styles (Deep Teal with Coral theme)
content/                  Lessons, activities, problem sets, manifest and syllabus (no answers)
img/                      Figures and the university seal
apps-script/              Code for the Apps Script project: Code.gs, Student.html, Admin.html, Styles.html
```

The answer key and the video question answers are **not** in this repository. They are seeded from a private
`Seed.gs` file and then kept only in the instructor's Google Sheet.
