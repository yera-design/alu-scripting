# ALU Scripting - Regular Expressions

## Project Overview
This project is part of the ALU scripting curriculum. It demonstrates the use of regular expressions (regex) in Ruby to match and extract specific patterns from strings.

## File Description
- **0-simply_match_school.rb**: A Ruby script that accepts one command-line argument, scans it for the exact word "School", and outputs all matches joined together.

## Requirements
- The regular expression must match the literal string `School` (case-sensitive).
- The script must use the `scan` method to find all occurrences.
- The output must be all matches concatenated.

## Usage Examples
```bash
# Match a single occurrence
$ ./0-simply_match_school.rb "School"
School

# Match multiple occurrences
$ ./0-simply_match_school.rb "School Best School"
SchoolSchool

# No match
$ ./0-simply_match_school.rb "school"   # (lowercase s, no output)
$

# With pipe to cat -e to see line endings
$ ./0-simply_match_school.rb "School" | cat -e
School$
