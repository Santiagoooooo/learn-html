## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
The action attribute in the <form> tag specifies the URL to which the form data will be sent when the form is submitted. It defines the endpoint of the server where the data entered into the form is processed.
2. What is the purpose of the _method_ attribute in the _form_ tag?
The method attribute in the <form> tag determines how the browser sends form data to the server. 
3. What is the purpose of the _name_ attribute in the _input_ tag?
The name attribute in the <input> tag specifies the name of the input field. 
4. What is the purpose of the _type_ attrbute in the _input_ tag?
The type attribute in the <input> tag indicates the type of data that should be entered by the user and helps the browser to provide the appropriate user interface element for it. 
5. What is the purpose of the _label_ tag?
The <label> tag is used to define a label for an <input> element. It provides accessibility support and improves user interaction with the form element.
6. What is the purpose of the _required_ attribute?
The required attribute is a Boolean attribute that, when present, indicates that the input field must be filled out before submitting the form. 
