# Medical Records Validator

## Overview

This Python project validates medical records stored as dictionaries inside a list. It checks whether each record follows the expected format and reports any invalid fields.

## Features

* Validates patient IDs (e.g., P1001, p1002)
* Ensures age is an integer and at least 18
* Validates gender values (male/female)
* Checks diagnosis format
* Verifies medications is a list of strings
* Validates visit IDs (e.g., V2301, v2302)
* Reports invalid records with their position in the dataset

## Technologies Used

* Python 3
* Regular Expressions (`re` module)

## Example Usage

```python
validate(medical_records)
```

### Example Output

```text
Valid format.
```

or

```text
Unexpected format 'age: 15' at position 0.
```

## Project Structure

```text
project/
│
├── main.py
├── README.md
└── sample_data.py
```

