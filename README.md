# LEARNING-REACT_Combining-Components-basic

Example: https://j6oi4n.csb.app/

## step-by-step summary of how the two description lists were combined:

1. Create the individual description list components: Name and Email. These components should each include the dt and dd elements for their respective description items.

2. Strip the dl element from each of the individual components, so that each component only includes the dt and dd elements.

3. Create the main App component, which will be responsible for combining the two description lists.

4. Import the Name and Email components into the App component.

5. In the App component's render method, wrap the two imported components in a single dl element.

6. Render the App component using ReactDOM.render().

7. The final result will be a single dl element in the browser, with the dt and dd elements for each of the description items.

## Folder structure

Root folder<br>
|- src/<br>
|- components/<br>
|- Name/<br>
|- index.js<br>
|- Name.css (optional)<br>
|- Email/<br>
|- index.js<br>
|- Email.css (optional)<br>
|- public/<br>
|- index.html<br>
|- package.json<br>
|- index.js
