Yes or No HTML Project
This project is a simple interactive webpage where users must click "Yes." Each time "No" is clicked, it increases a counter, but "Yes" is required to proceed.

Features
Mandatory "Yes": Clicking "Yes" is essential to pass through the prompt.
No Button Counter: Tracks the number of times the user clicks "No."
Simple and Fun: A playful interaction for user engagement.
Responsive: Works on all devices with a minimal and clean interface.
How It Works
Users are presented with two buttons: "Yes" and "No."
Clicking "No" increments a counter but does not allow any progression.
Clicking "Yes" is mandatory for any further action.
Tech Stack
HTML5: The structure of the page.
CSS3: Basic styling for visual appeal.
JavaScript: Logic for handling button clicks and counting.
Installation and Usage
Step 1: Clone the Repository
git clone https://github.com/yourusername/yes-no-project.git
Step 2: Open the Project
Navigate to the project directory and open the index.html file in your browser:
cd yes-no-project
open index.html
Step 3: Interaction
Click "Yes" to proceed.
Click "No" to increment the counter, but note that you cannot proceed without clicking "Yes."
Code Example
Here's the key logic for counting "No" clicks and enforcing "Yes":

javascript
let noCount = 0;

document.getElementById('yesBtn').addEventListener('click', function() {
    alert('Thank you for saying Yes!');
});

document.getElementById('noBtn').addEventListener('click', function() {
    noCount++;
    alert('You clicked No ' + noCount + ' times. But Yes is required!');
});
Contributing
If you have ideas to make this more fun or functional, feel free to contribute. Open a pull request or issue if you encounter any bugs or have suggestions.

License
This project is licensed under the MIT License.

Connect with Us
Email: abhishek2103.in@gmail.com
