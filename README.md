# RegistrationFormFCC
# HTML


1. `<!DOCTYPE html>`: This is a document type declaration for an HTML5 document.

2. `<html lang="en">`: This is the opening tag for the HTML document, specifying that the document is in English.

3. `<head>`: This is the opening tag for the head section of the document, which contains meta-information about the document.

   - `<meta charset="UTF-8">`: This meta tag specifies the character encoding of the document as UTF-8.
   - `<title>Registration Form</title>`: This tag sets the title of the webpage.
   - `<link rel="stylesheet" href="styles.css" />`: This tag links an external stylesheet (`styles.css`) to the HTML document for styling.

4. `<body>`: This is the opening tag for the body section of the document, which contains the content of the webpage.

   - `<h1>Registration Form</h1>`: This tag displays the main heading of the form.
   - `<p>Please fill out this form with the required information</p>`: This tag displays a paragraph of text instructing users to fill out the form.
   - `<form method="post" action='https://register-demo.freecodecamp.org'>`: This tag creates a form with a method of "post" and an action of "https://register-demo.freecodecamp.org", which specifies where the form data should be sent when submitted.

5. Inside the form:
   - `<fieldset>`: This tag groups related form elements together.
   - `<legend>Account type (required)</legend>`: This tag provides a title for the fieldset.
   - `<label for="first-name">Enter Your First Name: <input id="first-name" name="first-name" type="text" required /></label>`: This tag creates a label for an input field for the first name, which is required.
   - Similar labels and input fields exist for last name, email, new password, account type (radio buttons), profile picture (file input), age (number input), referrer (dropdown select), and bio (textarea).

6. `<label for="terms-and-conditions">`: This tag creates a label for a checkbox input for accepting terms and conditions.

   - `<input class="inline" id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" />`: This tag creates a checkbox input that is required to be checked.

7. `<input type="submit" value="Submit" />`: This tag creates a submit button for the form.

8. `</form>`: This tag closes the form.

9. `</body>`: This tag closes the body section of the document.

10. `</html>`: This tag closes the HTML document.

# CSS


1. `body`: This selector targets the `<body>` element of the HTML document.

   - `width`: Sets the width of the body to 100% of the viewport.
   - `height`: Sets the height of the body to 100% of the viewport height.
   - `margin`: Sets the margin of the body to 0.
   - `background-color`: Sets the background color of the body to #1b1b32.
   - `color`: Sets the text color of the body to #f5f6f7.
   - `font-family`: Sets the font family for the text in the body to Tahoma.
   - `font-size`: Sets the font size for the text in the body to 16px.

2. `h1, p`: This selector targets all `<h1>` and `<p>` elements in the document.

   - `margin`: Sets the top and bottom margins of the `<h1>` and `<p>` elements to 1em and left and right margins to auto, centering the elements horizontally.
   - `text-align`: Centers the text of the `<h1>` and `<p>` elements.

3. `form`: This selector targets all `<form>` elements in the document.

   - `width`: Sets the width of the form to 60% of the viewport width, with a maximum width of 500px and a minimum width of 300px.
   - `margin`: Sets the top and bottom margins of the form to 0 and left and right margins to auto, centering the form horizontally.
   - `padding-bottom`: Sets the bottom padding of the form to 2em.

4. `fieldset`: This selector targets all `<fieldset>` elements in the document.

   - `border`: Sets the border of the fieldset to none.
   - `padding`: Sets the top and bottom padding of the fieldset to 2rem and the left and right padding to 0.
   - `border-bottom`: Sets the bottom border of the fieldset to 3px solid #3b3b4f.

5. `fieldset:last-of-type`: This selector targets the last `<fieldset>` element in the document.

   - `border-bottom`: Removes the bottom border of the last fieldset.

6. `label`: This selector targets all `<label>` elements in the document.

   - `display`: Sets the display property of the label to block, making it a block-level element.
   - `margin`: Sets the top margin of the label to 0.5rem and the bottom margin to 0.

7. `input, textarea, select`: This selector targets all `<input>`, `<textarea>`, and `<select>` elements in the document.

   - `margin`: Sets the top margin of the input, textarea, and select elements to 10px and the bottom, left, and right margins to 0.
   - `width`: Sets the width of the input, textarea, and select elements to 100%.
   - `min-height`: Sets the minimum height of the input, textarea, and select elements to 2em.

8. `input, textarea`: This selector targets all `<input>` and `<textarea>` elements in the document.

   - `background-color`: Sets the background color of the input and textarea elements to #0a0a23.
   - `border`: Sets the border of the input and textarea elements to 1px solid #0a0a23.
   - `color`: Sets the text color of the input and textarea elements to #ffffff.

9. `.inline`: This selector targets elements with a class of "inline".

   - `width`: Unsets the width property, allowing elements with this class to use their default width.
   - `margin`: Sets the right margin of elements with this class to 0.5em and the left margin to 0, creating space between inline elements.
   - `vertical-align`: Aligns inline elements vertically.

10. `input[type="submit"]`: This selector targets `<input>` elements with a type attribute of "submit" in the document.

    - `display`: Sets the display property of the input to block, making it a block-level element.
    - `width`: Sets the width of the input to 60% of the parent element's width.
    - `margin`: Sets the top and bottom margins of the input to 1em and left and right margins to auto, centering the input horizontally.
    - `height`: Sets the height of the input to 2em.
    - `font-size`: Sets the font size of the input to 1.1rem.
    - `background-color`: Sets the background color of the input to #3b3b4f.
    - `border-color`: Sets the border color of the input to white.
    - `min-width`: Sets the minimum width of the input to 300px.

11. `input[type="file"]`: This selector targets `<input>` elements with a type attribute of "file" in the document.

    - `padding`: Sets the padding of the input to 1px top and bottom and 2px left and right.

12. `.inline`: This selector targets elements with a class of "inline".

    - `display`: Sets the display property of the element to inline.