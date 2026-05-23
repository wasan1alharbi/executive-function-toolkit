# High-Level Guide for Chapter: Technical Implementation/Implementation/Development/Approach

(it can have different names)

The whole purpose of this chapter is to highlight your work, how it was built, and help others recreate it or understand it better. Is every small code change important? NO. But how do you know what is important? Well you might not, and this is based on your project it won't be the same in every case. But I will share an example of how i decided what to include from my project in this section of my dissertation.

## 1. Chapter Overview
This chapter details the technical translation of the system design (established in the section before or maybe same section if you combined them) into a functional prototype. It proves that the abstract concepts are computationally viable and structurally sound.

This is an academic engineering paper, not a software tutorial. Do not describe *how you typed the code*; describe *why the system behaves the way it does* and how it enforces the rules you have set.

## 2. The Narrative flow:
I think it is best to write with the intention that both technical and nontechnical people can understand you. But once issue might be "every sub-section isn't connected to the rest, how do I connect them? how do I know what goes first vs last etc". A helpful approach would be to create a story. Then break that story into sub-sections, each sub-section is a different component of your project, this also prevents the Technical Implementatio section from reading like a disconnected list of features, structure. The reader should follow the system down into the user's experience. (I will share an example below of how I handled mine)

### Recommended Hierarchy:
* **5.1 Introduction:** Briefly state the scope (what was built from scratch vs. inherited, if any) and map out the chapter.
* **5.2 Environment and Technologies:** Present the stack and justify *why* they were chosen. + your approach to development
* **5.3 Foundations:** Explain any foundations if the reader needed to know them first or if there is common parts between all features/components, it is best to just add them here once.
* **5.4-5.x:** each sub-section is for a different component, as many as you need
* **5.x User Interface and Exploration:** (not needed)
* **5.x Summary of Implementation:** (not needed)

## 3. Academic Tone and Writing Style
* **Objective Voice:** Use formal academic language. Avoid informal phrasing like *"I hacked together a script."* Use *"A scheduled process was implemented to automate..."*

## 4. Visual Evidence & Formalization
* **LaTeX Pseudocode:** Use formal algorithms to define execution flows, rather than relying solely on raw code dumps.
* **Architecture Diagrams:** Use digitized block diagrams (UML sequence diagrams, flowcharts) to illustrate asynchronous operations and decision loops.
* **UI Evidence:** Use selective, high-resolution screenshots to prove UX implementation (e.g., the agent profile card showing the 8-field schema).
* BUT as you build the project take screenshots of many things you can, you never know how useful they can be!!!
