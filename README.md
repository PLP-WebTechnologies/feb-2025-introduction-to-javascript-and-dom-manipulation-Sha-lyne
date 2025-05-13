<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>JavaScript DOM Manipulation</title>
  <style>
    #changeStyle {
      color: green;
      font-weight: bold;
    }

    .highlight {
      background-color: yellow;
      padding: 5px;
    }
  </style>
</head>
<body>

  <header>
    <h1 id="mainHeading">Welcome to My Page</h1>
  </header>

  <nav>
    <p>Explore DOM and JavaScript basics below!</p>
  </nav>

  <main>
    <section>
      <p id="text">This text will change when you click the button.</p>
      <button onclick="changeText()">Change Text</button>
    </section>

    <section>
      <p id="changeStyle">Style will change on click.</p>
      <button onclick="changeStyle()">Change Style</button>
    </section>

    <section>
      <div id="elementContainer"></div>
      <button onclick="addElement()">Add Element</button>
      <button onclick="removeElement()">Remove Element</button>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 JavaScript Demo</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
# Introduction to JavaScript and DOM Manipulation

## Objectives

Write basic JavaScript functions.
Manipulate the DOM dynamically.
Respond to user interactions.

## Instructions

- Create a script.js file and link it to a HTML.
- Structure the document using DOCTYPE, html, head, and body.

>[!NOTE]
>  - Write JavaScript that:
>  - Changes text content dynamically.
>  - Modifies CSS styles via JavaScript.
>  - Adds or removes an element when a button is clicked.


# Tasks
- Create a well-structured HTML5 document.
- Use at least 5 different HTML elements.
- Ensure semantic correctness.

Happy Coding! 💻✨
