# VersionControl
This repo is for COP4331 Assignment 1: Version Control based on the completed COLORS lab.

# COLORS Lab Overview
The user has access to login to a website that allows them to register colors to their account and search for them afterwards.
The search feature supports partial searches. Colors are saved even when the user logs out and logs back in.

# Files included
- index.html: home login page
- color.html: color page to add colors, search for colors, and logout
- styles.css: styles (fonts, colors, sizing, spacing) to make website accessible
- background.png: background image for the color page
- AddColor.php: API endpoint for adding new color
- Login.php: API endpoint for user login
- SearchColors.php: API endpoint for color search feature
- contacts.php: ignored endpoint file that connects to the other PHPs with API credentials

# Resources Used
- LAMP Droplet (Digital Ocean)
- MySQL (User and color tables - connected on LAMP droplet)
- GoDaddy (Domain service, chosen domain: katieoberle.xyz)

# AI disclosure
Tool: Codex
Version: 5.6 Terra
Scope: General tutoring and code review
Description: I utilized AI for this lab to check my changes to the code as well as tutoring in areas such as MySQL, code protection, 
best practices, and git commands. The tool was generally helpful and efficient in providing me feedback on improvements. Particularly,
I learned how to set up .gitignore rules and connect an ignored PHP to the other endpoints to preserve functionality. It also
warned me about creating more folders than necessary as it would change the links in the HTML files that connect to styles.css.
