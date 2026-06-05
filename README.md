# 🗳️ Interactive Voting Methods Calculator

Welcome to the **Interactive Voting Methods Calculator**! This project is a live, interactive web application that allows users to input election data (candidates and vote distributions) and instantly see the results calculated across four distinct voting methods. 

Originally prototyped in a Mathematica notebook, the logic has been fully ported to JavaScript to run dynamically in any modern web browser.
**Mathematica users can run the original code by downloading the .nb file from this repository (file created with Mathematica 13.0)**

---

## ✨ Features

*   **Dynamic Data Entry:** Easily add candidates and preference schedules (number of votes per ranking).
*   **Real-Time Computation:** Instantly calculates election results entirely client-side using JavaScript.

---

## 🧮 Supported Voting Methods

This tool evaluates the submitted preference schedules against the following four voting methods:

1.  **Plurality:** The candidate with the most first-place votes wins.
2.  **Borda Count:** Points are assigned based on ranking (e.g., last place gets 1 point, second-to-last gets 2, etc.). The candidate with the highest total points wins.
3.  **Plurality with Elimination (Instant Runoff):** The candidate with the fewest first-place votes is eliminated, and their votes are transferred to the next preferred candidate. This repeats until a candidate achieves a majority.
4.  **Pairwise Comparison (Condorcet Method):** Every candidate is matched head-to-head against every other candidate. The candidate who wins the most pairwise matchups is the winner.

---

## 🚀 Live Demo

The project is hosted via GitHub Pages.

> **[Click here to view the live webpage](https://rifat299.github.io/voting-methods/)** 
---

## 🛠️ Tech Stack

*   **HTML5:** Page structure and input forms.
*   **CSS3:** Styling, floating sections, and the `#27c00a` green color palette.
*   **Vanilla JavaScript:** Core logic, originally translated from Mathematica, handling all dynamic DOM updates and voting algorithms.

---


## 📜 Background

This project started as an educational script inside a **Mathematica notebook** focusing on different vote counting methods. Firstly I tried to host the webpage on github with Wolfram API integration for executing calculation part. But the entire process was going too hard to receive responses from wolfram cloud along with their monthly limit of API usages. To make the tool accessible to everyone without requiring Mathematica software, it was rewritten entirely in JavaScript, expanding the scope to include Plurality with Elimination and Pairwise Comparison.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Rifat299/voting-methods/issues) if you have any suggestions or find any bugs.
