# Build a Survey Form

## Objective: Build an app that is functionally similar to https://survey-form.freecodecamp.rocks

### User Stories:

- You should have a page title in an _h1_ element with an _id_ of **title**.
- You should have a short explanation in a _p_ element with an _id_ of **description**.
- You should have a _form_ element with an _id_ of **survey-form**.
- Inside the _form_ element, you are **required** to enter your name in an _input_ field that has an _id_ of **name** and a _type_ of **text**.
- Inside the _form_ element, you are **required** to enter your email in an _input_ field that has an _id_ of **email**.
- If you enter an email that is not formatted correctly, you will see an HTML5 validation error.
- Inside the form, you can enter a number in an _input_ field that has an _id_ of **number**.
- The number _input_ should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
- If you enter numbers outside the range of the number _input_, which are defined by the _min_ and _max_ attributes, you will see an HTML5 validation error.
- For the name, email, and number _input_ fields, you can see corresponding _label_ elements in the form, that describe the purpose of each field with the following _ids_: _**id="name-label"**_, _**id="email-label"**_, and _**id="number-label"**_.
- For the name, email, and number _input_ fields, you can see _placeholder_ text that gives a description or instructions for each field.
- Inside the _form_ element, you should have a _select_ dropdown element with an _id_ of **dropdown** and at least two _options_ to choose from.
- Inside the _form_ element, you can select an option from a group of at least two _radio buttons_ that are grouped using the _name_ attribute.
- Inside the _form_ element, you can select several fields from a series of _checkboxes_, each of which must have a _value_ attribute.
- Inside the _form_ element, you are presented with a _textarea_ for additional comments.
- Inside the _form_ element, you are presented with a _button_ with _id_ of **submit** to submit all the _inputs_.