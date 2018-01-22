## ITMD 362, Production Problem 01: Form Semantics, Normalized Styles, and Events

In the `index.html` file in this directory, create a form that asks for a user’s email address,
phone number, and date of birth. There should also be a submit button that submits the form in the
absence of JavaScript.

Be sure to:

* Use the best HTML `<input>` types
* Use additional HTML `<input>` attributes to present interfaces suited to the input task,
  especially on mobile devices
* Use semantically associated `<label>` tags that match a `for` attribute with an `id` attribute
* Use some kind of semantic structure in HTML to keep each set of labels and inputs together under
  a shared parent element
* Place the entire form into a semantic grouping element (**not** a `<div>`)
* Load jQuery from the Google CDN if you wish to reference it from your `site.js` file; hint: your
  jQuery script reference must come before your `site.js` reference in your HTML

Then, in the `screen.css` file, do the following:

* Open with a rich set of reset CSS styles (such as Eric Meyer’s used in class demos)
* Include a set of normalization styles for your forms (such as the Form area of Normalize.css)
* Set up a baseline grid for all text on the page, including form elements, labels, and buttons

In the `site.js` file, do **one** of the following:

* Do a “good-enough” check on the user’s email address or phone number, and alert them if the data
  appears to be incorrect when they submit the form (a “good-enough” check is only looking for the
  smallest pattern possible that the data is probably an email address or phone number)
* Ensure that the user is at least 18 years old, based on their date of birth, and alert them if
  they are not when they submit the form

And also in the `site.js` file:

* Capture the `submit` event, prevent its default behavior, and alert users that the form has been
  submitted successfully, assuming their data passed the check you wrote on their data

As with all production problems, be sure that you are doing multiple, granular/atomic commits as you
complete your work.
