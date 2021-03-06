# Weekend Project "Boilerplating" :globe_with_meridians:

## Technical Requirements
This weekend's project should wrap up the topic of boilerplating with Python.
Since the two major subtopics are around Jjinja/Flas and Cookiecutter, two separate
mini-projects shall be implemented:

### Flask Templating
In order to get more familiar with the Jinja syntax, the Flask template should contain the majority of Jinja features, such as:
- [x] Statements 
- [x] Variables 
- [x] Filters (`users | map(attribute="email") | list | join('::')`)
- [x] Tests (`if user.age > 50`)
- [x] Comments (first part of `<body>` tag)
- [x] Template inheritance (`header.html` and `child.html`)
- [x] Super Blocks (`super()` in `child.html`)
- [x] Control Structures (`for user in users`)
- [x] Macros (`appender(name, suffix)` imported from `macros.html`)

### Cookiecutter for containerized Flask App
The cookicutter template should aim to put the Flask app above into a containerized 
CI environment, where the user should be asked about the following Parameter:
- [x] project name
- [x] author
- [ ] (optional) CI (Building, Testing, Coverage, Styling, Documentation, Hosting)
