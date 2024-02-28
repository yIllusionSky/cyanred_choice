# cyanred_choice
A framework for brushing up questions, allowing you to customize imported questions, export questions, and customize a personalized question bank.

## path
```markdown
software  `--Path to the program`
source  `--Source code path`
```

## Introduction
This project is developed by 倾幻浸尘, who can be found on Bilibili for direct contact. For further inquiries or community engagement, feel free to reach out via QQ: 2106257493 or join the QQ group: 882635854.

## Features
### Basic Features
 * Quantity: Specify how many questions to attempt in a session.
 * Index: Choose the starting point for questions (only applicable for sequential question selection).
 * Pin: Keep the application always on top.

### Question Features
 * Sequential: Attempt questions in a fixed order.
 * Random: Attempt questions in a random order.
 * Mistakes: Revisit previously incorrect questions.
 * Favorites: Work on marked questions.

### Editing Features
 * Creation: Create or import questions using the provided txt and Excel formats (ignore IP and port for now). Multiple .db files can also be imported directly.
 * Editing: Edit all questions (please be patient with large question sets).
 * Selection: Choose question files from the save folder. Note: default will be created if no file exists; ErrorTopic for manually selecting undeterminable questions;  
 * RemoveDuplicates for remaining files after deletion of duplicates.
 * Search: Look up answers to questions.
 * Filter: Identify and filter out duplicate or problematic questions (note that only a subset can be identified algorithmically, not all).

## Features Not Implemented
 * Exams
 * IP and Port Configuration
 * Random Order Selection
 * Encryption
 * Question Export

## Development and Future Plans
The project is developed using C++ with the Qt framework. If you're interested in commercial use, please contact the developer. This Qt project was initiated in early 2022, with future expectations including Android and web adaptation, along with server backend support for question bank downloads.