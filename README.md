### WELCOME TO ASSIGNMENT-006
# ENGLISH <img width="25px" src="./assets/logo.png" /> JANALA
 **📅 Deadline For 60 marks**: 16th March , 2025 ( 11:59 pm ⏱️)

**📅 Deadline For 50 marks**: 17th March , 2025 ( 11:59 pm ⏱️)

**📅 Deadline For 30 marks**: Any time after  17th March , 2025

---
⚡ API Endpoints
---
1. Get ⚡ All Levels
```bash
https://openapi.programming-hero.com/api/levels/all
```
2. Get ⚡ Words by Levels <br/>
https:// openapi.programming-hero.com/api/level/{id}
```bash
https://openapi.programming-hero.com/api/level/5
```
3. Get ⚡ Words Detail <br/>
https:// openapi.programming-hero.com/api/word/{id}
```bash
https://openapi.programming-hero.com/api/word/5
```
4. Get ⚡ All  Words <br/>

```bash
https://openapi.programming-hero.com/api/words/all
```

# Requirements 



# Vocabulary Learning App

## Features

### Navbar
- [X] Create a navbar with a logo and brand name on the left
- [ ] Create three buttons with icons: FAQ, Learn, and Logout
- [ ] Create functionality to jump to the FAQ section when clicking the FAQ button
- [ ] Create functionality to jump to the Vocabulary section when clicking the Learn button
- [ ] Create a fixed navbar at the top with a bottom border

### Banner
- [ ] Create a banner with a title and paragraph along with a login form on the left
- [ ] Create an image on the right
- [ ] Align elements as per the Figma design

### FAQ Section
- [ ] Create an FAQ section containing relevant questions and answers

### Footer
- [ ] Create a footer that includes the logo and social icons as per Figma
- [ ] Create functionality to redirect users to the profile when clicking on social icons

### Vocabulary Section
- [ ] Create a center-aligned heading
- [ ] Create dynamically generated buttons for each lesson that will be displayed on page load
- [ ] Create a default text that will be displayed in the Vocabulary section initially
- [ ] Create functionality to display all words for a selected lesson in a card format, showing:
  - [ ] Word
  - [ ] Word meaning & pronunciation
  - [ ] Two buttons with relevant icons as per Figma
- [ ] Create a "No Word Found" message if no words exist for a lesson
- [ ] Create functionality to highlight the active lesson button

### Vocabulary Details
- [ ] Create functionality to open a modal when clicking the details icon
- [ ] Create a modal that displays:
  - [ ] Word with pronunciation
  - [ ] Example sentence
  - [ ] Synonyms
  - [ ] A "Learn Complete" button to close the modal

### ES6 Questions (README.md)
- [ ] Create a section explaining the difference between `var`, `let`, and `const`
- [ ] Create a section explaining the difference between `map()`, `forEach()`, and `filter()`
- [ ] Create a section explaining arrow functions and how they are different from regular functions
- [ ] Create a section explaining how JavaScript Promises work
- [ ] Create a section explaining how closures work in JavaScript

## Challenge Requirements

### Custom Navigation System
- [ ] Create functionality to hide everything on landing except the Banner and Footer
- [ ] Create a functional login form:
  - [ ] Show an alert if the user does not enter a name
  - [ ] Show an alert if the password is not "123456"
  - [ ] Show a success alert, hide the Banner, and display the Navbar, Vocabulary Section, and FAQ Section when the user enters a valid name and password
- [ ] Create functionality to hide the Navbar, Vocabulary Section, and FAQ Section and show only the Banner and Footer when clicking "Logout"
- [X] Create smooth scrolling for FAQ & Learn buttons

### Handling Invalid Data
- [ ] Create functionality to avoid displaying falsy values like `undefined` or `null`
- [ ] Create functionality to display relevant words if no data is found

### Loading Spinner
- [ ] Create a loading spinner that will be displayed instead of words in the Vocabulary section for every request

## Optional: Be a Perfectionist
- [ ] Create an integration of SweetAlert instead of normal alerts
- [ ] Create functionality for voice pronunciation of vocabulary words
- [ ] Create and integrate a local Bengali font for Bangla words
