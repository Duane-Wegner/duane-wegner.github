---
title: "Duane Wegner"
---

# Welcome to My CS-499 ePortfolio

Hello! I am **Duane Wegner**, a Computer Science student at Southern New Hampshire University (SNHU). This ePortfolio showcases my projects, skills, and achievements as part of my CS-499 Capstone.

## About Me

- **Background:** U.S. Army IT Specialist, network and fiber engineering, and current Computer Science student  
- **Skills:** Java, C++, Python, JavaScript, Android development, web development, Git  
- **Career Goal:** To become a software developer or full-stack engineer, building interactive and scalable applications

## Artifact Code Review

<iframe width="560" height="315" src="https://www.youtube.com/embed/SfQXntvhU68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

This video walks through my CS-499 capstone artifact, WhisperingWoods.py a text based console game, highlighting key features, design decisions, and implementation details. It demonstrates how the code functions, the technologies used, and the what improvements will be made throughout my enhancment development.

## Artifact

The artifact I selected is the Python text adventure developed in IT 140. The original source, Artifact File/Whispering-Woods.py, early 2024, served as the foundation for the project enhancement 1. During the CS 499 Capstone in late 2025, I converted this console-based game into a static web application using HTML, CSS, and JavaScript. The enhancement includes key files such as game.html, index.html, css/styles.css, data/rooms.json, and multiple JavaScript modules in the js/ directory. The enhanced version represents a fully modernized, deployable, and interactive version of the original game. 

## Enhancements

### One (Software Design and Engineering)

### The artifact was improved from the original Python version in several ways:

  -	A visual map layer with fog-of-war logic implemented in map.js and styled in css/styles.css.
  -	Inventory UI with SVG icons created in inventory.js.
  -	UX improvements including modal behavior and keyboard navigation managed in js/main.js.
  -	Expanded documentation in README.md and inline comments across modules.

### Did you meet the course outcomes you planned to meet with this enhancement?
  -	Outcome 1 - Professional self-presentation: Met by creating a professional GitHub repository: This first enhancement can be viewed at: https://duane-wegner.github.io/Whispering-Woods/index.html, and the repository is available at https://github.com/Duane-Wegner/Whispering-Woods/tree/Enhancement-1. 
  -	Outcome 2 - Professional communication: Met through README.md and clear in-file comments, demonstrating clear documentation and user communication.
  -	Outcome 3 - Algorithmic design and problem solving: Met via map.js and js/game.js, which implement fog-of-war logic, coordinate normalization, and item pickup mechanics.
  -	Outcome 4 - Use of modern tools and techniques: Met by using ES modules, modular UI files, and a namespaced persistence approach (js/storage.js).
  -	Outcome 5 - Security mindset: Partially met. Admin authentication is local-only (auth.js), and the README.md documents the threat model and limitations.

### Link to enhancement One:
  [Whispering Woods Enhancement One](https://github.com/Duane-Wegner/Whispering-Woods/tree/Enhancement-1)

<br>

### Two (Algorithms and Data Structures)

### The artifact was improved from the previous web version in several ways:
  - Implemented graph algorithms in js/algorithms.js including bfsPath, bfsNearestWithItem, and reachableRooms for efficient map queries.
  - Added developer-facing test and demo pages: js/algorithms-test.html (interactive demo) and js/algorithms-unit-test.html (unit tests).
  - Integrated algorithm results into the UI: a "Highlight Nearest" control in main.js and map highlight styles in css/styles.css that visualize shortest paths.
  - Made game logic inventory-aware so recommendations ignore already-collected items (js/game.js / main.js).
  - Documented algorithm behavior and complexity (Big-O comments) and expanded inline comments to improve readability and maintainability.

 ### Did you meet the course outcomes you planned to meet with this enhancement?
  - Outcome 1 - Professional self-presentation: Met by maintaining a professional, demonstrable repo and providing live demo pages. This enhancement can be viewed on the demo/test pages in the enhancement-2 folder and the repo branch Enhancement-2.
  - Outcome 2 - Professional communication: Met through added documentation and test pages that let reviewers run and inspect algorithm behavior; inline comments explain algorithm choices.
  - Outcome 3 - Algorithmic design and problem solving: Met. BFS-based helpers and inventory-aware search demonstrate algorithmic design and reasoning; complexity is documented (O(V+E) for BFS) and behavior is validated with unit tests.
  - Outcome 4 - Use of modern tools and techniques: Met. The work uses ES modules, modular test pages, DOM visualization, and a small in-browser test harness to validate logic and present results to stakeholders.
  - Outcome 5 - Security mindset: Met through enhancement focuses on algorithms and UX; persistence and admin auth remain client-only and documented as such. Defensive coding and testability continue to support a security-aware development approach.

### Link to enhancement Two:
  [Whispering Woods Enhancement One](https://github.com/Duane-Wegner/Whispering-Woods/tree/Enhancement-2)
<br>

### Three (Databases)

<br>
  

## Connect with Me

- [GitHub Profile](https://github.com/Duane-Wegner)  
- [LinkedIn Profile](https://www.linkedin.com/in/duane-wegner/)
