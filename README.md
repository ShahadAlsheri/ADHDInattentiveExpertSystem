# ADHD Expert System (Inattentive Type)

An interactive Expert System implemented in Python using the **Experta** library. 
It evaluates the likelihood of ADHD (Inattentive Type) in children, adolescents, and adults based on user-provided symptoms and additional criteria.

## Project Overview

This system simulates a rule-based expert system:

- Collects user input on ADHD-related symptoms.
- Checks additional exclusion criteria (stress-related, sudden adult onset, duration, multiple settings).
- Uses defined rules to provide a diagnostic suggestion:
  - Likely ADHD (Inattentive Type)
  - Unlikely ADHD
  - Possible other conditions (requiring clinical evaluation)
- Provides a summarized assessment report at the end.


## Features

- **Interactive symptom questionnaire:** 12 core symptoms + 4 additional criteria.
- **Rule-based reasoning:** Uses Experta to apply exclusion and diagnosis rules.
- **Dynamic assessment:** Adjusts minimum symptom threshold based on age.
- **Clear output:** Summarizes diagnosis, total symptoms reported, and minimum required.
- **User-friendly:** Prompts user step by step, ensuring accurate input collection.

## Requirements

- Python 3.7+
- [Experta](https://pypi.org/project/experta/) library

Install Experta via pip:

```bash
pip install experta
