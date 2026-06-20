# AI Security Scanner for Python

**Project Link:** [View Project](http://learn.nextwork.org/projects/ai-security-audit-copy)

**Author:** xerox.freak@outlook.com  
**Email:** xerox.freak@outlook.com

---

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_tz9xp5km)

---

## Introducing Today's Project!

In this project, I'm going to build an AI Security scanner based on python. This will help me learn the vulnerability assessment with AI and Python scripting. I'm interested in this because I have similar experience with the AI and python based projects and this will help learn about distinguish security scanning techniques.

### Key tools and concepts

The key tools I used include were Python, Gemini API, and packages such as Google genai, python-dotenv and Colorama. Key concepts I learnt include prompt structuring, python scripts, fancying the terminal responses.

### Challenges and wins

I did this project today to learn how to use my prompt engineering skills with Gemini for security related projects. Another skill I want to learn is how can I use the prompts not limited to only 'one' file at once and being able to scan more than just code files.

---

## Generating the Gemini API Key

In this step, I'm setting up an API key from Google. I need to do this so I can integrate the API key further with the project of python based Security Scanner and invoke the AI usage.

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_h3ymx6kd)

---

## Setting Up the Python Environment

In this step, I'm setting up Python environment. This is important for this project because the code scripts are easier to function in Python language and the virtual environment invoked will ease out the process of isolated space for Python projects.

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_rb4kj7mz)

### Installing the required packages

Now that I have my virtual environment set up I need to install necessary packages. This is important for my project because the  for securely storing the Gemini API Key and for recognising Gemini calls written in Python.

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_pw6dq3ck)

---

## Connecting to the Gemini API

In this step, I'm connecting to the API Key for Gemini along with the scanner script I will be writing. This is important because the Gemini API will provide the AI engine to validate and obtain new information about vulnerabilities to scan.

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_yw8dt2jh)

### Securing the API key with a .env file

I got an error! My error was not supplying the API Key to access the Google Gemini. Having a .env file is important because Harcoding API Keys directly to the code is dangerous as accidental commit to GitHub or even screenshot can get the key exposed. The quota to test out the API key for the Gemini model can be misused.

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_kn3jm8tb)

### Verifying the connection

I verified the connection by running the scanner.py file. Gemini responded with the results against the Try and Except block added to the scanner.py script file which confirmed that the Gemini API connection is working.

---

## Engineering the Security Prompt

In this step, I'm writing a security prompt that tells Gemini to be an actual security expert. This is important because it will facilitate Gemini to do exactly how to analyze code for vulnerabilities and more.

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_rk9mb7ys)

---

## Building the File Scanner

In this step, I'm adding file scanning so my scanner can call Gemini to Analyze the files being uploaded against vulnerabilities. This is important because the scanner service analyze the code with Gemini via the API calls against know vulnerabilities or threat patterns.

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_jt7px3na)

---

## Running the Security Audit

In this step, I'm testing my scanner by creating a test file with a security flaw. I'll start with one vulnerability first because testing even a single vulnerability will stage improvements at the later stage such as autonomous testing, multi-file scans, multi-vulnerabilities test module scans, batch tests, etc.

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_ub6ry1wf)

### Analyzing the vulnerability report

My scanner detected a total of 4 types of vulnerabilities namely, SQL Injection, Weak Hashing Algorithm, Command Injection and Harcoded credentials. The most surprising vulnerability was SQL Injection, which depicts the parameterization requirements are not be be neglected while parsing user inputs. This shows that AI can help with security by reviewing and scanning codes against known vulnerabilities, pattern recognition, credential thefts, and more.

---

## Adding Color-Coded Severity Ratings

In this project extension, I'm adding few new things such as, the Colorama library for fancying out the terminal output, improving the prompts for grading results. This lets the scanner function more like an actual application and guiding AI to provide better insights and by code (as well terminal) to showcase outputs better.

![Image](http://learn.nextwork.org/grateful_beige_loyal_rhinoceros/uploads/ai-security-audit-copy_mj7rc2vy)

### How the color system works

I added colour to my responses by using the Colorama package and altering my code to handle the colour outputs for Terminal by Defining the severity levels- which are in- turn adapted from the Gemini responses. The Prompt instructions to Gemini were to share outputs as: SEVERITY: [CRITICAL/HIGH/MEDIUM/LOW]
TYPE: [Vulnerability Name]
DESCRIPTION: [One sentence explaining the issue]
IMPACT: [One sentence on potential damage]
FIX: [Code snippet only].

---

## Wrapping Up

This project took me approximately 1.5 hours including documentations and tweaking the code areas as well. The most challenging part was structuring the prompts in respect to vulnerability identifications.

---

---
