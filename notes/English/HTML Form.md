# 1. form tag
The `<form>` tag in HTML is used to create an HTML form that allows users to input data and submit it to a server for processing. Forms are an essential part of web development as they enable users to interact with a web page by entering information such as text, numbers, selections, or file uploads.

Here's the basic syntax of the `<form>` tag:

```
<form action="server_script.php" method="post"><!-- Form elements go here --></form>
```


# 2. input tag
The `<input>` tag is a versatile HTML element used to create various types of input fields on web forms. It is a self-closing element, meaning it does not have a closing tag. The `type` attribute of the `<input>` tag determines the type of input field it will create.

Here are some common `type` attributes and examples of how the `<input>` tag is used:

1. Text Input:

```
<label for="username">Username:</label><input type="text" id="username" name="username" placeholder="Enter your username">
```

2. Password Input:

```
<label for="password">Password:</label><input type="password" id="password" name="password" placeholder="Enter your password">
```

3. Checkbox Input:

```
<input type="checkbox" id="checkbox1" name="checkbox1" value="value1"><label for="checkbox1">Option 1</label>
```

4. Radio Button Input:

```
<input type="radio" id="radio1" name="radio" value="option1"><label for="radio1">Option 1</label><input type="radio" id="radio2" name="radio" value="option2"><label for="radio2">Option 2</label>
```

5. Submit Button:

```
<input type="submit" value="Submit">
```

6. Reset Button:

```
<input type="reset" value="Reset">
```

7. File Upload:

```
<label for="file">Select a file:</label><input type="file" id="file" name="file">
```

8. Hidden Input (not visible on the form but used for storing data):

```
<input type="hidden" name="hiddenField" value="hiddenValue">
```

The `name` attribute is used to identify the input field when the form is submitted, and the `value` attribute sets the initial value of the input field. For checkboxes and radio buttons, the `value` attribute represents the value sent to the server if the input is checked.

The `placeholder` attribute can be used to provide a brief hint or example of the expected input for text and password fields.

Input elements can be used to collect user data, perform form submissions, and create interactive web forms. They play a crucial role in allowing users to provide information to websites and web applications.

# 3. label tag
The `<label>` tag is an HTML element used to associate a label with an input element in a web form. It improves the usability and accessibility of web forms by providing a clear label for each form element, making it easier for users to understand the purpose of the input field.

The `<label>` element can be used in two ways:

1. Associating with an input element using the `for` attribute:

```
<label for="username">Username:</label><input type="text" id="username" name="username">
```

In this example, the `for` attribute of the `<label>` tag is set to the `id` attribute of the corresponding input element. When users click on the label, it focuses or activates the associated input element. Similarly, when users click on the input element, the label gets focused as well. This association helps users with motor disabilities or those using assistive technologies to interact with the form more easily.

2. Wrapping the input element inside the label:

```
<label>Username:<input type="text" name="username"></label>
```

In this method, the `<input>` element is placed within the `<label>` element, and the label's text is included directly. Clicking on the label text or the input field activates the input element. This method is especially useful when the label and input are closely related and do not need separate positioning.

Using the `<label>` tag is a best practice for creating accessible web forms, and it helps improve the overall user experience. Properly labeled form elements make it easier for all users, including those with disabilities, to understand the form's purpose and provide the required input. Additionally, it is beneficial for mobile users, as tapping on a larger label area is more convenient than trying to precisely tap on a small input field.

# 4. select tag
The `<select>` tag is an HTML element used to create a dropdown list or selection menu. It allows users to choose one or more options from a list of predefined choices. The `<select>` element is often used in forms and user interfaces to provide a user-friendly way to make selections from a list of options.

Here's how the `<select>` tag is used:

```
<label for="fruits">Select your favorite fruit:</label><select id="fruits" name="fruit"><option value="apple">Apple</option><option value="banana">Banana</option><option value="orange">Orange</option><option value="strawberry">Strawberry</option></select>
```

# 5. output tag
The `<output>` tag is an HTML element used to display the result of a calculation or a script. It is typically used in conjunction with JavaScript to capture and display dynamic content or the output of a function or calculation on a web page.

Here's how the `<output>` tag is used:

```
<form oninput="result.value = parseInt(num1.value) + parseInt(num2.value)"> <label for="num1">Number 1:</label> <input type="number" id="num1" name="num1"><br><label for="num2">Number 2:</label> <input type="number" id="num2" name="num2"><br> <label for="result">Result:</label>  <output name="result" id="result"></output></form>
```

# 6. details tag
The `<details>` tag in HTML is used to create a disclosure widget that allows you to show or hide additional content. It provides a way to create collapsible sections of content, where users can click on a summary to reveal more details. The details element can be used to create an interactive and space-saving way to display additional information, instructions, or options on a web page.

Here's the basic syntax of the `<details>` tag:

```
<details><summary>Summary or heading</summary><!-- Additional content goes here --></details>
```

# 7. legend tag
The `<legend>` tag is an HTML element used in conjunction with the `<fieldset>` element to provide a caption or title for a group of related form elements. It is typically used to create a visual grouping and label for a set of form controls within a form.

Here's how the `<legend>` tag is used in combination with the `<fieldset>` tag:

```
<form> <fieldset><legend>Personal Information</legend><label for="name">Name:</label><input type="text" id="name" name="name">  <br><label for="email">Email:</label><input type="email" id="email" name="email"></fieldset></form>
```


# 8. button tag
The `<button>` tag in HTML is used to create a clickable button on a web page. It allows users to perform actions, trigger events, or submit forms within the web page. The content inside the `<button>` tag represents the text or content displayed on the button.

Here's the basic syntax of the `<button>` tag:

```
<button>Click Me</button>
```


# 9. textarea tag
The `<textarea>` tag is an HTML element used to create a multi-line text input field in an HTML form. It allows users to input and edit larger amounts of text, such as comments, messages, or other textual data.

Here's how the `<textarea>` tag is used:

```
<label for="message">Enter your message:</label><textarea id="message" name="message" rows="4" cols="50"></textarea>
```