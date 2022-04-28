# SEA8 - Spring Quest 03 - Thymeleaf

## Challenge: Doctor identification server

To start, Fork this repository then clone it locally.

> Make sure you *Fork properly*, otherwise you won't be able to push anything!

1. Run the project to check that the home page is displaying correctly.
2. You will have noticed that when you submit the form, the page does not yet display the name and number of the doctor you entered. Modify the code of the *doctor.html* page and the associated controller to retrieve this information and correctly display it.
3. If no doctor's name is entered, set the default value to be "John Smith". If no number is entered, set the default value to be 0.
4. The header and footer are currently contained in the *index.html* page. Makes sure to extract these sections and create *header.html* and *footer.html* fragments, for use across both *doctor.html* and *index.html*.

## Validation criterias

- Your project displays the name and number of the doctor entered into the form.
- If no name or number is entered, the display should feedback: "John Smith" and 0
- The link to execute the form action should use a Thymeleaf expression
- The templates *index.html* and *doctor.html* must call two fragments called: *header.html* and *footer.html*
