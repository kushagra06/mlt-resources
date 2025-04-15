---
layout: default
title: Grad Students Resource List
---

# Grad School Resource List

This is a seed of a great list of resources to help grad students succeed in grad school.  
Let’s make this a working document. Feel free to add entries. Feel free to reorganize this doc. I would much appreciate comments on what you found useful or unique about an entry. In other words, feel free to own this doc/project a little bit. If you have access, you are trusted you won’t destroy useful information.

***

## Mix

**John W. Simpson-Porco’s page with a number of good pointers.**  
*To be processed/added/included..*

***

## D. S. Bernstein  
**On bridging the theory/practice gap. IEEE Control Systems Magazine, vol.19, no.6, pp.64-70, 1999.**  
*(Rephrased key highlights from the paper)*

- The divide between control theory and practical implementation is acknowledged but difficult to quantify.
- Real-world control design is complex, with many interacting factors, making it hard to isolate and validate the impact of new methods.
- In aerospace, control systems are crucial but high-risk. While essential, their failure can be catastrophic, making well-tested methods preferable to novel techniques, reinforcing resistance to new technology.
- Academic publishing prioritizes novelty, making journal papers terse and written for researchers, not practitioners. They also have long publication delays, further limiting accessibility.
- Broadly, two types of issues are identified:  
  - **Modeling Issues:** Challenges in building accurate system models.  
  - **Control Issues:** Problems in applying control methods in real systems.

### Modeling Issues

- Real-world systems often have unstable dynamics, making control difficult as large deviations can be unrecoverable. The assumption of stability should be questioned.
- There is a key distinction between modeling for control architecture design, which focuses on system setup and component selection, and modeling for controller implementation, which deals with tuning and real-world behavior.
- Robust control ensures performance under uncertainty but relies on modeling. However, real-world changes are unpredictable, so control engineers must manage uncertainties beyond models, reducing dependence on data-driven modeling.
- Statistical analysis is underutilized in control for evaluating identified models and performance, risking inaccurate conclusions.

### Control Issues

- The real world is continuous, but even the fastest of controllers operate in discrete time.
- Real-time computing requires accurate data, and increasing computational power alone won’t improve results if the data is unreliable. Similarly, large-scale offline computations are ineffective without reliable inputs.
- Saturation in control systems occurs when an actuator or system reaches its maximum or minimum limit and cannot function beyond that point.. Recognizing saturation is crucial to prevent performance loss in stable systems and instability in unstable ones.
- Sensor noise limits performance, requires lowering control gains to avoid amplifying noise, and is often unpredictable, making control design challenging.
- Nonlinearities in control systems can be smooth and linearizable or nonsmooth and unpredictable, with the latter being more challenging to identify and manage, especially in precision applications.
- Control engineering often focuses on steady-state behavior, but real-world challenges lie in handling transients and unexpected changes.
- Feedback introduces risks, as small errors can amplify into instability.
- No detail in control can be ignored, as real-world imperfections impact system performance.
- Over-reliance on modeling limits practical application, making simpler, adaptive methods like PID more widely used.
- Bridging the gap between theory and practice requires aligning academic research with real-world constraints and industry needs.

***

## On Research

- Richard Hamming: *You and your research*.  
  https://www.cs.virginia.edu/~robins/YouAndYourResearch.html

***

## On Writing

- **Lawrence Paulson** Computer Laboratory, University of Cambridge:  
  *Researcher, Don't Make Your Readers Scream!*

- **Dimitri Bertsekas:** *Ten Simple Rules for Mathematical Writing*

- **Zhang, Weixiong.** 2014. *“Ten Simple Rules for Writing Research Papers.”* PLoS Computational Biology 10 (1): e1003453. [pdf]

- **Halmos, P. R.** 1983. *“How to Write Mathematics.”* In *Selecta Expository Writing*, 157–86. New York, NY: Springer New York. [pdf]

- **Bruce Francis:** *Elements of Mathematical Style*

- **García-Granda, Santiago.** 2013. *“Writing Science: How to Write Papers That Get Cited and Proposals That Get Funded.”* Crystallography Reviews 19 (1): 53–54. [UofA link: pdf]

- **Trent Uni.** 2003. *“How to Write Mathematics,”* January, 6. [link]

- **Hamalainen, W.** 2006. *“Scientific Writing for Computer Science Students,”* January, 1–130. [pdf]

- **Goldreich, O.** 2004. *“How to Write a Paper.”* Njit.edu, January.  
  https://www.wisdom.weizmann.ac.il/~oded/R2/re-writing.pdf

- **Sand-Jensen, Kaj.** 2007. *“How to Write Consistently Boring Scientific Literature.”* Oikos 116 (5): 723–27. [pdf]

- **Albert R Meyer:** *Mathematics for Computer Science*, 520 pages. Scope: From proofs, logic, set theory, discrete math, finite state machines and such, to elementary probability. All the very basic stuff that anyone in CS is expected to know. 2010. [pdf]

- **Terence Tao:** *What is good mathematics?* 2017 [link]

- **Kevin P. Lee:** *A Guide to Writing Mathematics* [pdf]

***

## On Presentations

- **On presentations by Lawrence Paulson**

- **Patrick Winson (MIT) on YouTube:** *How to Speak?*  
  *Csaba’s note: As far as I remember, what he says does not quite apply to ML theory seminars, or if you are lecturing in a classroom setting. However, otherwise, it is very good advice.*

***

## How to Learn Mathematics

*(Section 1.4 from Alan U. Kennington, “Mathematical logic reconstructed”, [download])*

### 1.4.1 REMARK:
The asterisk learning method focuses attention on difficult points which need it most. This is the "asterisk method of learning" which I discovered in 1975. It worked!

1. Find somewhere quiet. Turn off the radio (and your portable digital music player). A library reading room is best if it is a quiet library reading room. Preferably have a large table or desk to work on.  
2. Open the book or lecture notes which you wish to study.  
3. Start copying the relevant part of the book or lecture notes to a (paper) notebook by hand. If you are studying a book, you should paraphrase or write a summary of what you are reading. If you are studying lecture notes, you should copy everything and add explanations where required.  
4. Whenever you copy something, ask yourself if you really understand it completely. In other words, you must understand every word in every sentence. As long as you are completely comfortable with what you are copying, keep going.  
5. If you read something which is difficult to understand, stop and think about it until you understand it clearly. If a mathematical expression is unclear, determine which set or class each term in the expression belongs to. All sub-expressions in a complex expression must belong to some set or class. Every operator and function in an expression must act only on variables in the domain of definition of the operator or function. Draw arrow diagrams for all functions, domains and ranges. Draw diagrams of everything!  
6. If you find something that you really can't understand after a long time, copy it to your notebook, but put an asterisk in the margin. This means that you have copied something that you did not understand.  
7. While you continue copying, keep going back to the lines which are marked with an asterisk to see if you can understand them. If you find an explanation later, you can erase the asterisk.  
8. When you have finished copying enough material for one sitting, look over your notes to see if you can understand the lines which still have an asterisk. If you have no asterisks, that means that you have understood everything. So you can progress to the next section or chapter of the text.  
9. If you still have one or more asterisks left in your notes after a day or more, you should keep trying to understand the lines with the asterisks. Whenever you get some spare time and energy, just look at the lines with asterisks on them. These are the lines that need your attention most.  
10. If you discuss your work with other people, especially with teachers or tutors, show them your notes and the lines with the asterisks. Try to get them to explain these lines to you.  

If you keep working like this, you will find that your study becomes very efficient. This is because you do not waste your time and energy studying things which you have already understood.  
I used to notice that I would spend most of my time reading the things which I did understand. To learn efficiently, it is necessary to focus on the difficult things which you do not understand. That's why it is so important to mark the incomprehensible lines with an asterisk.  
Copying material by hand is important because this forces the ideas to go through the mind. The mind is on the path between the eyes and the hands. So when you copy something, it must go through your mind! It is also important to develop an awareness of whether you do or do not really understand something. It is important to remove the mental blind spots which hide the difficult things from the conscious mind.  
When copying material, it is important to determine which is the first word where it becomes difficult. Read a difficult sentence until you find the first incomprehensible word. Focus on that word. If a mathematical expression is too difficult to understand, read each symbol one by one and ask yourself if you really know what each symbol means. Make sure you know which set or space each symbol belongs to. Look up the meaning of any symbol which is not clear.
