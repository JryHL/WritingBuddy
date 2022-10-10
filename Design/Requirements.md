# Requirements

## Non-functional requirements

### Technical
NF1. The program has an uptime of 99% over a week of simulated usage
NF2. The program's functions are fully usable on desktop Firefox and Chromium and mobile Firefox and Chrome.
NF3. The program stores login credentials such that passwords cannot be feasibly retrieved in the case of a database leak
NF4. No function has a response time of more than 3 seconds on an ideal internet connection (localhost)

### Linked to functional requirements
#### F1
F1-NF1. The password requirements should ensure that it takes at least a year to guess passwords via exhaustive search
F1-NF2. The password and username input fields are compatible with third-party password managers

#### F4
F4-NF1. No user should be able to compromise the integrity of the software with a specially-crafted file or file name
F4-NF2. No user should be able to create too many files or create files too rapidly such that uptime and response time requirements are missed

#### F5
F5-NF1. The program should provide an unobstrusive user interface to the user when writing or examining a piece of writing

#### F11
F11-NF1. The program should return search results in close to constant time, even as the number of files grows.

#### F12
F12-NF1. The program should return search results in less than 3s for a data size of 100,000 characters.

#### F15
F15-NF1. The program should be compatible with major third-party grammar checkers, namely Firefox's spellchecker and the Grammarly extension

## Functional requirements

F1. As a **writer**, I want to be able to **create a user account** with a username, email, and password so that I can **create and manage files**.
F2. As a **writer**, I want to be able to **change my password** so that I can **secure my account** or **better remember my password**.
F3. As a **writer**, I want to be able to **delete my account** so that I can **protect my privacy**.
F4. As a **writer**, I want to be able to **create a file** so that I can **make a piece of writing**.
F5. As a **writer**, I want to be able to **view and modify a file** so that I can **perform writing**.
F6. As a **writer**, I want to be able to **delete a file** so that I can **get rid of files I don't need**.
F7. As a **writer**, I want to be able to **organize files into folders** so that I can **find files more easily**.
F8. As a **writer**, I want to be able to **add tags to files** so that I can **find files more easily**.
F9. As a **writer**, I want to be able to **remove tags from files** so that I can **get rid of unneeded tags**.
F10. As a **writer**, I want to be able to **add a tag that has already been added to another file** so that **multiple files can be grouped together**.
F11. As a **writer**, I want to be able to **search for files by their tags** so that I can **find files more easily**.
F12. As a **writer**, I want to be able to **search for files by their content** so that I can **find files more easily**.
F13. As a **writer**, I want to be able to **see readability scores** so that I can **review my work**.
F14. As a **writer**, I want to be able to **adjust fonts, font sizes, and color scheme** so that I can **better review my work**.
F15. As a **writer**, I want to be able to **check my grammar** so that I can **review my work**.

