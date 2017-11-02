Comments that contradict the code are worse than no comments. Always make a priority of keeping the comments up-to-date when the code changes!

Comments should be complete sentences. If a comment is a phrase or sentence, its first word should be capitalized, unless it is an identifier that begins with a lower case letter (never alter the case of identifiers!).

Block comments generally consist of one or more paragraphs built out of complete sentences, and each sentence should end in a period.

When writing English, follow [The Elements Of Style](https://faculty.washington.edu/heagerty/Courses/b572/public/StrunkWhite.pdf) by Strunk and White.


# Block Comments

Block comments generally apply to some (or all) code that follows them, and are indented to the same level as that code. Each line of a block comment starts with a # and a single space (unless it is indented text inside the comment).

Paragraphs inside a block comment are separated by a line containing a single # .

### Block Comment Example

```Python
# The main function will parse arguments via the parser variable.  These
# arguments will be defined by the user on the console.  This will pass
# the blah blah blah blah

def main():
  parser = argparse.ArgumentParser()
...

# Define the again() function to ask user if they want to use the calculator again

def again()

    # Take input from user
    calc_again = input('''Do you want to calculate again? Y for YES or N for NO.
    ''')

    # If user types Y, run the calculate() function
    if calc_again == 'Y':
        calculate()
...
```

# Inline Comments

Use inline comments sparingly.

An inline comment is a comment on the same line as a statement. Inline comments should be separated by at least two spaces from the statement. They should start with a # and a single space.

Inline comments are unnecessary and in fact distracting if they state the obvious. Don't do this:

`x = x + 1                 # Increment x`

But sometimes, this is useful:

`x = x + 1                 # Compensate for border`


