Q1: Personal Website (HTML + CSS)
I developed a personal website using HTML and CSS and hosted it on GitHub Pages. The website includes sections that introduce myself, highlight my education, skills, achievements, and provide access to my CV. It also features my profile photo and a collection of local images from my birthplace.

Assumptions:

Profile and local images are organized under the folder assets/images/.

The CV file is named cv.pdf and is linked using an anchor (<a>) tag.

Styling is handled using an external CSS file named styles.css

Q2: User Interaction Tracker (JavaScript)
To fulfill this task, I implemented a JavaScript function that captures and logs all user interactions across the website. It tracks both click events and passive "view" interactions, and logs details like timestamp, event type, and the element involved (e.g., image, paragraph, dropdown) in the browser console.

Assumptions:

All event logs follow the format: Timestamp, Event Type, Target Element.

Mouseover actions are considered as “view” events for passive interactions.

Event listeners are applied using addEventListener on relevant DOM elements.

Q3: Text Analysis Tool
This section includes a large text input area (suitable for input >10,000 words). JavaScript is used to analyze the input and display counts of letters, words, spaces, newlines, and special characters. It also tokenizes the input to count and group pronouns, prepositions, and indefinite articles.

Assumptions:

Predefined sets of pronouns, prepositions, and articles are used for grouping and counting.

The analysis is triggered through a button click, not in real-time.

Output is displayed below the input area in a clearly formatted layout.

General Assumptions:

All necessary resources (images, CV) are located in their appropriate folders, as referenced in the code.

Both Q2 and Q3 functionalities are handled in the same script.js file.

Image and CV filenames are assumed to match exactly with those referenced in the HTML (e.g., profile.jpg, birthplace.jpg, cv.pdf).
