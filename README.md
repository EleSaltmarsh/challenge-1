# challenge-1
First challenge for web development bootcamp: refactoring code for increased user accessibility.

## Challenge 

### User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

### Acceptance Criteria

* Semantic HTML elements can be found throughout the source code
* HTML elements follow a logical structure independent of styling and positioning
* Image and icon elements contain accessible `alt` attributes
* Heading attributes fall in sequential order
* Title elements contain a concise, descriptive title

## Results

- Code divided into a header, section, aside, and footer to replace numerous div elements.
- Image defined in CSS style sheet was moved to HTML for easier access to link. Attributes maintained using a class identifier.
- Multiple class identifiers removed from the section and aside where elements shared the same CSS attributes. CSS rules were transferred to parent container or other shared identifier.
- Notes added inside HTML code.
- Page deployed at https://elesaltmarsh.github.io/challenge-1/. 
- Project stored at https://github.com/EleSaltmarsh/challenge-1 with detailed ReadMe.