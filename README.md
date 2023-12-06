# Capita Selecta of Software Engineering (2023/2024)

The repository hosts the material, developed and needed in the lab-sessions of CSSE,
at VUB Brussels. The material is developer by Johannes Härtel.

## Lab-Session 1 (21 November 2023)

This session will give a brief introduction to alternative libraries
used to represent and process data in MSR. We will discuss NumPy, Pandas, Spark, R (vectors), TensorFlow
and PyTorch. The PDF of the presentation can be found [here](session01/slides.pdf).

The second part will be a live demo of a basic data collection on a repository. The code
can be found [here](session01/src).


## Lab-Session 2 (5 December 2023)

In this session, we will take a look at models, and different ways to use them. We will explore conceptual alternatives
in how we can infer parameters. This will get relevant later when we answer our hypothesis about software development or predict bugs.

Slides can be found [here](session02/slides.pdf).
Backup code that illustrates the slides can be found [here](session02/src).

## Lab-Session 3 (upcoming, 12 December 2023)

Please **bring your laptop to lab-session 3** and ensure that the **code from lab-session 1 runs**.

Session 3 will be active. You can follow up on some ideas. The previous code from session 1 can be used as a starting point.
- You can follow up on resolving the problem of **comment length**. Different length comments should be reflected in our metric on comments.
- You can follow up on the idea of **watermarks**. Not all comments matter. Some are repetitive and have no true meaning. You can develop a creative solution.
- You can follow up on providing other metrics that **explain** why a class is commented. Taking a look at access modifications is a suitable option. Do you have other ideas?
- You can follow up on **blaming the developer**. This is complicated since you need to call git's blame. A potential outcome can be the developer with the highest contribution in the file. We can then check if developers have different commenting behavior.