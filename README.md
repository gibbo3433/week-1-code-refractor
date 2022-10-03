# Challenge 1: Code refractor = Horiseon

## On-the-job ticket

Horiseon came to me with their current website code, asking me to update their code to follow accessibility standards so that the new website will be optimized for search engines.

### User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

### Acceptance Criteria

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## Issues identified and corrected

Most of the issues I was faced with was updating the HTML structure to a more semnatic code structure and also how much of an abundance of class selectors were used in the CSS file. I competed my task by reorganising the index.html file into the correct semantic structure and also by adding more user friendly element selectors into the CSS code.

## Future work

CSS:
- Use of a media screen
- :root to change entire selectors if nessccessary

I have added into HTML alt: notes and into CSS also /*notes*/ to help any future edits by making it easier to see what the different elements are in the code and if any collaberation work will be done in the future. 

## Screenshot of completed Horiseon website






Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

Roadmap
If you have ideas for releases in the future, it is a good idea to list them in the README.

Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

Authors and acknowledgment
Show your appreciation to those who have contributed to the project.

License
For open source projects, say how it is licensed.

Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
