## Tip_Calculator:-
###
# Hosted Link:-https://tulasidurga1.github.io/Tip_Calculator/
# HTML (index.html):

### This is the HTML structure for the tip calculator web page.
-It includes metadata, a title, and a link to an external CSS file (style.css) for styling.<br>
-The page has a container div with a class "container" that holds the calculator interface.<br>
-Inside the container, there's a "Welcome" heading, a section for entering the bill amount, a section for selecting service quality, a section for entering the number of people sharing the bill, and a "Calculate" button.<br>
-The JavaScript code is included at the bottom of the HTML file using the <script> tag with the "index.js" source file.
JavaScript (index.js):<br>

 # The JavaScript code begins by selecting the container element with the class "area" and the "Calculate" button using the document.querySelector() method.

- An event listener is added to the "Calculate" button (calculate). When the button is clicked, the code inside the event listener function is executed.<br.

- Inside the event listener function, a new empty paragraph element (<p>) is created and stored in the div variable. This div will be used to display the calculated tip amount.<br>

- The content of the div is cleared (div.innerText = "") to ensure that it's empty before displaying the result.<br>

-The code then retrieves the bill amount (amount), the number of people sharing the bill (totalPeople), and the selected service quality (service) from the corresponding input elements in the HTML.<br>

-The tip amount is calculated using the formula amount * service / totalPeople, and the result is set as the text content of the div.<br>

-Finally, the calculated tip amount is displayed within the div, and the div is appended as a child to the container (container.appendChild(div)), which means it will appear on the web page.<br>

-In summary, this code creates a simple web page where users can enter the bill amount, select the quality of service, and specify the number of people sharing the bill. When the "Calculate" button is clicked, it calculates the tip amount based on these inputs and displays it on the page.<br>






