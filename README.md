# Holberton SmilingSchool
# Added JavaScript!

## Description

This project adds JavaScript, primarily with the use of jQuery for DOM manipulation, to the previous Bootstrap project found [here](https://github.com/RockoGilbert/holberton-smiling-school).

This project duplicates the full dynamic front-end design of a fully-functional responsive website. The static content can be seen as 3 separate Figma designer files found [here](https://www.figma.com/file/QYQqMYbdpAHL5xTclwJKSI/Homepage?node-id=0%3A1), [here](https://www.figma.com/file/KLAI53jdYpfFNEy0O79ymB/Pricing?node-id=0%3A1), and [here](https://www.figma.com/file/ivg3abH1HLmMayBgjGg1Qf/Courses?node-id=0%3A1).

Content on the page is dynamically loaded from the SmileSchool API found [here](https://smileschool-api.hbtn.info).


## README Navigation

- [Description](#description)
- [Navigation](#navigation)
- [Installation](#installation)
- [Project Rules](#project-rules)
- [Features](#features)


## Installation

### 1. Install

Clone the repository into your system with the command:

```
git@github.com:RockoGilbert/holberton-smiling-school-javascript.git
```

### 2. Open

Choose an HTML file. I recommend [homepage.html](https://github.com/RockoGilbert/holberton-smiling-school-javascript/blob/main/homepage.html)! Install "Live Server" or another server preview extension, run it, and navigate to the open port.

### 3. View

"Holberton SmilingSchool - JavaScript" is now ready to view!

## Project Rules

- You won’t have a lot of instruction, so you are free to implement it the way that you want. The objective is simple: Create a fully functional web page that looks the same as the designer file.
- Your styles.css must be as small as you can. You must use Bootstrap classes as much as you can.
- You have to use JQuery.
- Your scripts.js must contain all of your JavaScript.
- Your JavaScript must be executed only when the document is loaded.

## Features

- Reusable and easily-changeable content
- Decently accessible as defined by [axe Dev Tools](https://www.deque.com/axe/devtools/)
- Working multi-item carousel (using [Slick carousel](https://kenwheeler.github.io/slick/) plugin)
- No static content present in dynamic sections
- Loader is briefly visible if change Network to "Slow 3G"
- Search initialized by:
	- Click on magnifying glass
	- Pressing "enter" while in "keywords" input field
	- New topic selected
	- New sort selected

## Bugs

- Loader should be visible during click on "next" arrow on carousels but couldn't get it working and included "infinite" loop instead
- Latest tutorials only has 4 cards so arrows are not visible on desktop when exactly 4 are displayed (due to Slick carousel)